# Device Protocol Description

## Device Operation

The device is not designed to float

## Device Protocol

> Send commands and you will get a response.

### Request version information

* **Version**: `5.3+`
* **Bytes**: `FB FE 00 00`
* **Response**: 68 25 FB
* **Broadcast**: FF FF FF FF 2E 3F

This command results in the version information be extracted from the device and sent over t the main server of the data center. Once executed, it cannot be stopped or returned back to the origins.

### Set Voltage Limits

* Version: **`5.2+`**
* Bytes: **`FB FE 00 00`**
* Response: **68 25 FB**
* Broadcast: **FF FF FF FF 2E 3F**

This command results in the version information be extracted from the device and sent over t the main server of the data center. Once executed, it cannot be stopped or returned back to the origins.

**Error Codes**
* Test