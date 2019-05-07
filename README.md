# ![LOGO](logo.png) Sandbox **flow**ground Connector

## Description

A generated **flow**ground connector for the Sandbox API (version v1).

Generated from: https://api.apis.guru/v2/specs/getsandbox.com/v1/swagger.json<br/>
Generated at: 2019-05-07T17:40:53+03:00

## API Description

Sandbox API

## Authorization

Supported authorization schemes:
- API Key
## Actions

### searchActivity

*Tags:* `Activity`

#### Input Parameters
* `fromTimestamp` - _optional_ - Timestamp to start search from, epoch time in milliseconds.
* `sourceSandboxes` - _optional_ - Comma-separated list of Sandbox names to search.
* `keyword` - _optional_ - A keyword to search activities by, will match any part of the ActivityMessage.
* `allTypes` - _optional_ - Flag to return all types of activity, defaults to just Requests
* `maxResults` - _optional_ - Maximum number of results to return

### getSandboxes

*Tags:* `Sandbox`

#### Input Parameters
* `filterType` - _optional_

### createSandbox

*Tags:* `Sandbox`

### deleteSandbox

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

### getSandbox

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

### updateSandbox

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

### forkSandbox

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

### deleteSandboxState

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

### getSandboxState

*Tags:* `Sandbox`

#### Input Parameters
* `sandboxName` - _required_ - Name of the Sandbox

## License

**flow**ground :- Telekom iPaaS / getsandbox-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
