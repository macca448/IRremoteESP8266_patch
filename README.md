# IRremoteESP8266 v2.8.6 patch

###  This patch adds support for the ESP32 Arduino Core v3.x (IDF v5.x)

The current IDE offering of `IRremoteESP8266 (v2.8.6)` does not support `ESP32 Arduino Core 3.x Timer API`.
The patched version of [`IRrecv.cpp`](https://github.com/macca448/IRremoteESP8266_patch/tree/main/IRRemoteESP8266_patch) offered here will add ESP32 v3.x support.

### How to apply this patch  

####  1.  If you haven't already install IRremoteESP8266 (v2.8.6) via Arduino IDE Library Manager - NOTE: The following image shows an error free compile of my [IR-Blaster](https://github.com/macca448/ESP-IR-Blaster) project using an `ESP32 v3.x` and `IRsend.h` along with current versions of all other included libraries.  

   ![](https://github.com/macca448/IRremoteESP8266_patch/blob/main/assets/images/IDE_compile.jpg))  

<br>
  
####  2.  Next navigate to `> Documents > Arduino > libraries > IRremoteESP8266 > src` and delete or replace `IRrecv.cpp` with [this](https://github.com/macca448/IRremoteESP8266_patch/tree/main/IRRemoteESP8266_patch) version

 ![](https://github.com/macca448/IRremoteESP8266_patch/blob/main/assets/images/IRrecv_cpp_location.jpg)

<br>
   
####  3.  Thats it you're done and you can start to capture or send IR codes. Here's an image of an error free compile for the example sketch `IRrecvDumpV2.ino` which I physcally used to successfully test this [patch](https://github.com/macca448/IRremoteESP8266_patch/tree/main/IRRemoteESP8266_patch)  
  
  ![](https://github.com/macca448/IRremoteESP8266_patch/blob/main/assets/images/IDE_compile_IRrecv.jpg)





