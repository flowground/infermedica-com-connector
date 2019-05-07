# ![LOGO](logo.png) Infermedica **flow**ground Connector

## Description

A generated **flow**ground connector for the Infermedica API (version v2).

Generated from: https://api.apis.guru/v2/specs/infermedica.com/v2/swagger.json<br/>
Generated at: 2019-05-07T17:42:26+03:00

## API Description

Empower your healthcare services with intelligent diagnostic insights of Infermedica API.

## Authorization

This API does not require authorization.

## Actions

### List all conditions

> Returns a list of all available conditions.

*Tags:* `conditions`

### Get condition by id

> Returns details of a single condition specified by id parameter.

*Tags:* `conditions`

#### Input Parameters
* `id` - _required_ - condition id

### Query diagnostic engine

> Suggests possible diagnoses and relevant observations based on provided patient information.

*Tags:* `diagnosis`

### Query diagnostic engine for explanation

> Explains which evidence impact probability of selected condition.

*Tags:* `explain`

### Get database information

> Returns information about data used by diagnostic engine.

*Tags:* `info`

### List all lab tests

> Returns a list of all available lab tests.

*Tags:* `lab_tests`

### Get lab test by id

> Returns details of a single lab test specified by id parameter.

*Tags:* `lab_tests`

#### Input Parameters
* `id` - _required_ - lab test id

### Find observation matching given phrase

> Returns a single observation matching given phrase.

*Tags:* `lookup`

#### Input Parameters
* `phrase` - _required_ - phrase to match
* `sex` - _optional_ - sex filter
    Possible values: male, female.

### Find mentions of observations in given text

> Returns list of mentions of observation found in given text.

*Tags:* `parse`

### List all risk factors

> Returns a list of all available risk factors.

*Tags:* `risk_factors`

### Get risk factor by id

> Returns details of a single risk factor specified by id parameter.

*Tags:* `risk_factors`

#### Input Parameters
* `id` - _required_ - risk factor id

### Find observations matching given phrase

> Returns list of observations matching the given phrase.

*Tags:* `search`

#### Input Parameters
* `phrase` - _required_ - phrase to match
* `sex` - _optional_ - sex filter
    Possible values: male, female.
* `max_results` - _optional_ - maximum number of results
* `type` - _optional_ - type of results

### Query diagnostic engine for related symptoms

> Suggests possible symptoms based on provided patient information.

*Tags:* `suggest`

#### Input Parameters
* `max_results` - _optional_ - maximum number of results

### List all symptoms

> Returns a list of all available symptoms.

*Tags:* `symptoms`

### Get symptoms by id

> Returns details of a single symptom specified by id parameter.

*Tags:* `symptoms`

#### Input Parameters
* `id` - _required_ - symptoms id

### Query diagnostic engine for triage level

> Estimates triage level based on provided patient information.

*Tags:* `triage`

## License

**flow**ground :- Telekom iPaaS / infermedica-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
