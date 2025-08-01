# IRremoteESP8266 v2.8.6 patch

###  This patch adds support for ESP32 Arduino Core v3.x (IDF v5.x)

The current IDE offering of [IRremoteESP8266)](https://github.com/crankyoldgit/IRremoteESP8266) being `v2.8.6` does not support the `ESP32 Arduino Core 3.x Timer API`. 

This patched version of [IRrecv.cpp](https://github.com/macca448/IRremoteESP8266_patch/tree/main/IRRemoteESP8266_patch) will add ESP32 v3.x support to IRremoteESP8266 (v2.8.6).

Install [IRremoteESP8266 (v2.8.6)](https://github.com/crankyoldgit/IRremoteESP8266) via the IDE or manually if you prefer then navigate to ***Documents > Arduino > libraries > IRremoteESP8266 > src*** and replace `IRrecv.h` with this [patched version](https://github.com/macca448/IRremoteESP8266_patch/tree/main/IRRemoteESP8266_patch)

<br>

- **Here is a [pictorial readme](https://github.com/macca448/IRremoteESP8266_patch/blob/main/pictorial_readme.md) if you prefer.**
