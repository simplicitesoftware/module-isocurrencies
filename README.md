<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://www.simplicite.io/resources//logos/logo250.png)
* * *

`ISOCurrencies` module definition
=================================

Currencies (ISO 4217)

`ISOCurrency` business object definition
----------------------------------------

ISO 4217 currency

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      | 
| ------------------------------------------------------------ | ---------------------------------------- | -------- | --------- | -------- | -------------------------------------------------------------------------------- |
| `isoCurName`                                                 | char(100)                                | yes      | yes       |          | Currency name                                                                    |
| `isoCurCode`                                                 | char(3)                                  | yes*     | yes       |          | Currency code (3 letters)                                                        |
| `isoCurNum`                                                  | int(3)                                   |          | yes       |          | Currency number (3 digits)                                                       |

### Custom actions

No custom action

