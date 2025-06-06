📷 ESP32-CAM & ESP32 TFT Display Interface
This repository contains code for interfacing an ESP32-CAM module with an ESP32 + TFT display setup. The ESP32-CAM streams video or image data, while the second ESP32 receives and displays it on a TFT screen.

🔧 Features:

ESP32-CAM setup for camera capture and data transmission

ESP32 + TFT display ST7735 for live feed display

Communication over Wi-Fi

Designed for robotics or remote monitoring projects

Lightweight, optimized code for real-time image display

🚀 Great for DIY surveillance, remote robots, or creative IoT displays.

When uploading code to ESP-32 CAM, the esp32 board library in board manager needs to be version 1.0.4.
When uploading code to ESP-32 with the connected tft display, the esp32 board library in board manager needs to near the latest versions.

When you download the TFT_eSPI library you need to change its User_Setup, with the provided one above, make sure that your tft display uses ST7735.

[Arduino Websockets]
https://github.com/gilmaimon/ArduinoW...

[Arduino JPEGDecoder library (OLD)]
https://github.com/Bodmer/JPEGDecoder

[Arduino TJpg_Decoder library (NEW)]
https://github.com/Bodmer/TJpg_Decoder

[TFT_eSPI]
https://github.com/Bodmer/TFT_eSPI
