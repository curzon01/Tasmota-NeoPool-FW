# Precompiled Tasmota with NeoPool

This repository contains precompiled Tasmota based on the origin [Tasmota v15.3.0.3 Susan (development branch commit 58b7d85)](https://github.com/arendst/Tasmota/tree/58b7d85c9e763ee7dfd11e6cd1e05ec702a0f4bb) without any defaults and presettings but including the [NeoPool](https://tasmota.github.io/docs/NeoPool/) sensor module for Sugar Valley pool controllers.

## Firmware files for initial flash

<b>These files are for initial flashing an ESP only. Do not use these for OTA or file upload updates.</b>

To **initial flash** an ESP32/ESP8266 it is recommended using [ESP_Flasher](https://github.com/Jason2866/ESP_Flasher), use one of the files listed below that corresponds to your ESP chip type:

### Tasmota including NeoPool


- [tasmota32-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool.factory.bin)
<br>for ESP32 chip types (like M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite))
- [tasmota32s3-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool.factory.bin)
<br>for ESP32 S3 chip types (like M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3) or [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite))
- [tasmota32c3-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool.factory.bin)
<br>for ESP32 C3 chip types
- [tasmota-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool.bin)
<br>for ESP8266 chip types

### Tasmota including NeoPool with TASMOTA_SENSOR_DEBUG enabled

Same as before but includes TASMOTA_DEBUG_SENSOR enabled with additonal debugging output when using with [WebLog 4](https://tasmota.github.io/docs/Commands/#weblog), [FileLog 4](https://tasmota.github.io/docs/Commands/#filelog), [MQTTLog 4](https://tasmota.github.io/docs/Commands/#mqttlog), [SysLog 4](https://tasmota.github.io/docs/Commands/#syslog) or [SerialLog 4](https://tasmota.github.io/docs/Commands/#seriallog).

- [tasmota32-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool-dbg.factory.bin)
<br>for ESP32 chip types (like M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite))
- [tasmota32s3-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool-dbg.factory.bin)
<br>for ESP32 S3 chip types (like M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3) or [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite))
- [tasmota32c3-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool-dbg.factory.bin)
<br>for ESP32 C3 chip types
- [tasmota-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool-dbg.bin)
<br>for ESP8266 chip types


## Firmware files for updating Tasmota

To update an existing Tasmota device via WebUI [Firmware Upgrade](https://tasmota.github.io/docs/Upgrading/)/[**Upgrade by file upload**](https://tasmota.github.io/docs/Upgrading/#upgrade-by-file-upload), use one of the files listed below that corresponds to your ESP chip type:

### Tasmota including NeoPool

- [tasmota32-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool.bin)
<br>for ESP32 chip types (like M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite))
- [tasmota32s3-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool.bin)
<br>for ESP32 S3 chip types (like M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3) or [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite))
- [tasmota32c3-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool.bin)
<br>for ESP32 C3 chip types
- [tasmota-origin-neopool.bin.gz](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool.bin.gz)
<br>for ESP8266 chip types

### Tasmota including NeoPool with TASMOTA_SENSOR_DEBUG enabled

Same as before but includes TASMOTA_DEBUG_SENSOR enabled with additonal debugging output when using with [WebLog 4](https://tasmota.github.io/docs/Commands/#weblog), [FileLog 4](https://tasmota.github.io/docs/Commands/#filelog), [MQTTLog 4](https://tasmota.github.io/docs/Commands/#mqttlog), [SysLog 4](https://tasmota.github.io/docs/Commands/#syslog) or [SerialLog 4](https://tasmota.github.io/docs/Commands/#seriallog).

- [tasmota32-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool-dbg.bin)
<br>for ESP32 chip types (like M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite))
- [tasmota32s3-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool-dbg.bin)
<br>for ESP32 S3 chip types (like M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3) or [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite))
- [tasmota32c3-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool-dbg.bin)
<br>for ESP32 C3 chip types
- [tasmota-origin-neopool-dbg.bin.gz](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool-dbg.bin.gz)
<br>for ESP8266 chip types
