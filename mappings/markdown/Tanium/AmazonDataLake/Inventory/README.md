# Event Dossier: Tanium
### Tanium Platform endpoint data in JSON
- **Description**: Translates Tanium Platform data via Tanim Connect to OCSF.
- **Event References**:
  - https://help.tanium.com/bundle/aws-integration/page/AWS-Integration/Appendix_OCSF_Mapping.htm

 ### OCSF Version: 1.1.0
 - `category_uid`: `5`
 - `category_name`: `Configuration/Inventory`
 - `class_uid`: `5001`
 - `class_name`: `Device Inventory Info`
 - `metadata.profiles`: `[host]`
 - `metadata.version`: `1.1.0`
 - `metadata.product.vendor_name`: `Tanium`

 ### Mapping:
 - This does not reflect any transformations or evaluations of the data. Some data evaluation and transformation will be necessary for a correct representation in OCSF that matches all requirements.


| OCSF                       | Raw             |
| -------------------------- | ----------------|
|`metadata.product.name`|`Tanium Platform`|
|`metadata.product.vendor_name`|`Tanium`|
|||
|`device.uid`|`Computer ID`|
|`device.hostname`|`Computer Name`|
|`device.risk_score`|`Risk Score`|
|`device.os.name`|`Operating System`|
|`device.ip`|`IP Address`|
|`device.mac`|`MAC Address`|
|`device.hw_info.chassis`|`Chassis Type`|
|`device.hw_info.serial_number`|`Computer Serial Number`|
|`device.hw_info.cpu_type`|`CPU`|
|`device.hw_info.is_managed`|`true`|
|||
|`actor.user.name`|`Primary User`|
|`actor.user.domain`|`Domain Name`|
