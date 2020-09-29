# FT6X36 (FT6236/FT6336/FT6436L/FT6436)
This is an ESP-IDF component forked from library [FT6X36](https://github.com/strange-v/FT6X36) for self-capacitive touch panel controllers produced by FocalTech Systems.

## ATTENTION!
Only basic functionality is currently implemented. Has been tested only on ESP32 using a 2.7" e-ink display (GDEW027W3-T).

## Annotation
The [Adafruit_FT6206_Library](https://github.com/adafruit/Adafruit_FT6206_Library) was used as a base for the FT6X36 library. Many things were added/improved/rewritten based on a datasheet for the controller.

## References

The reading part of I2C was mostly stealed from [LVGL for ESP-IDF](https://github.com/lvgl/lv_port_esp32). Hats off to the great work of this library and FT6X36.
