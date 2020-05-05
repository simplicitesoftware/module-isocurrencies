<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`ISOCurrencies` module definition
=================================

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=simplicite-modules-ISOCurrencies&metric=alert_status)](https://sonarcloud.io/dashboard?id=simplicite-modules-ISOCurrencies)

### Introduction

Currencies (ISO 4217)

### Import

To import this module:

- Create a module named `ISOCurrencies`
- Set the settings as:

```json
{
	"type": "git",
	"origin": {
		"uri": "https://github.com/simplicitesoftware/module-isocurrencies.git"
	}
}
```

- Click on the _Import module_ button

### Load data

Sample data is provided as a module's dataset.

Open this dataset and click on the _Apply_ button after having imported the module and made a full clear cache.

`ISOCurrency` business object definition
----------------------------------------

ISO 4217 currency

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      | 
| ------------------------------------------------------------ | ---------------------------------------- | -------- | --------- | -------- | -------------------------------------------------------------------------------- |
| `isoCurName`                                                 | char(100)                                | yes      | yes       |          | Currency name                                                                    |
| `isoCurCode`                                                 | char(3)                                  | yes*     | yes       |          | Currency code (3 letters)                                                        |
| `isoCurNum`                                                  | int(3)                                   |          | yes       |          | Currency number (3 digits)                                                       |

