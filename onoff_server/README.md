| Supported Targets | ESP32 |
| ----------------- | ----- |

ESP BLE Mesh Node demo
==========================

This demo shows how BLE Mesh device can be set up as a node with the following features:

- One element
- Two SIG models
	- **Configuration Server model**: The role of this model is mainly to configure Provisioner device’s AppKey and set up its relay function, TTL size, subscription, etc.
   - **OnOff Server model**: This model implements the most basic function of turning the lights on and off.

The default purpose of this demo is to enable the advertising function with 20-ms non-connectable interval in BLE 5.0. You can disable this function through menuconfig: `idf.py menuconfig --> Example Configuration --> This option facilitates sending with 20ms non-connectable interval...`
