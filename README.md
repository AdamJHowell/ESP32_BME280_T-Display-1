# ESP32_BME280_T-Display
This is an Arduino sketch for the Xinyuan-LilyGO TTGO-T-Display ESP32 Devkit which uses a HT30 sensor to measure temperature and humidity, publish those values to a MQTT broker, and print the values to the TFT screen.

## Hardware

ESP32 with TFT: https://www.banggood.com/TTGO-T-Display-ESP32-CP2104-CH340K-CH9102F-WiFi-bluetooth-Module-1_14-Inch-LCD-Development-Board-LILYGO-for-Arduino-products-that-work-with-official-Arduino-boards-p-1522925.html

BME280 sensor: https://www.aliexpress.us/item/2251832676107058.html

## Libraries

LilyGo's TFT display library: https://github.com/Xinyuan-LilyGO/TTGO-T-Display

Adafruit's BME280 library: https://github.com/adafruit/Adafruit_BME280_Library

Nick O'Leary's MQTT client: https://github.com/knolleary/pubsubclient

Benoît Blanchon's ArduinoJson: https://arduinojson.org/


## Software

Online site to convert an image to the byte array format needed by the graphics library: http://www.rinkydinkelectronics.com/t_imageconverter565.php
