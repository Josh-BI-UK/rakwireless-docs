---
release_date: 01/13/2023
version: "2.1.2"
release_note_description: Unified operative system for the WisGate Edge line that provides a feature-rich environment to access and configure the LoRaWAN gateway. The latest version of WisGateOS 2 is based on the latest version of the OpenWRT kernel for better security. WisGateOS 2 uses a simplified user interface that makes it easier to use and program. Integrated with WisDM, which allows the remote management of gateways and firmware. With extension functionality, the user can add extra features and functions to their gateways.
download_link: https://downloads.rakwireless.com/LoRa/WisGateOS2/WisGateOS2_2.1.2.zip
logo: /assets/images/release-notes/WisGateOS2.png

---

<rk-release-notes/>

---


::: tip 📝 NOTE

WisGateOS 2 is available only for version 2 WisGtate Edge gateways.
The supported models are as follows:
 - WisGate Edge Pro version 2: RAK7289V2, RAK7289CV2, RAK7289V2H, RAK7289CV2H
 - WisGate Edge Lite 2 version 2:  RAK7268V2, RAK7268CV2, RAK7268V2H, RAK7268CV2H
 - WisGate Edge Prime version 2: RAK7240V2, RAK7240CV2, RAK7240V2H, RAK7240CV2H

:::


##### Added

| No. | Feature                             | Description | Reference |
| --- | ----------------------------------- | ----------- | --------- |
| 1   | Support full duplex for V2 hardware | -           | -         |

##### Fixed

| Daily Build No. / Bug No. | Description                                                         |
| ------------------------- | ------------------------------------------------------------------- |
| -                         | [AS923] After connecting to TTN, it cannot join normally.           |
| -                         | Downlink are rejected by the forwarder sometimes.                   |
| -                         | Fix the BS backup certification issue when connecting to ThingPark. |