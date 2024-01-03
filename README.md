# T-Display LVGL demo

## Intro
This is a simple LVGL demo project customized to work on the following boards:

* [T-Display](https://www.lilygo.cc/dzufeq)
ESP32, ST7789 SPI 135x240 LCD, 4MB/16MB Flash
* [T-Display-S3 AMOLED](https://www.lilygo.cc/rpcnf9)
ESP32-S3, RM67162 QSPI 240x536 LCD, 16MB Flash, 8MB PSRAM

The project uses LovyanGFX for T-Display and Arduino GFX for T-Display-S3 AMOLED.

## Compilation
Compile for T-Display:

```pio run -e t-display```

Compile and upload:

```pio run -e t-display -t upload```

Compile for T-Display-S3 AMOLED:

```pio run -e t-amoled```

Compile and upload:

```pio run -e t-amoled -t t-amoled```

