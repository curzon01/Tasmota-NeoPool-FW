# Tasmota with NeoPool sensor module

This repository contains binary files for [Tasmota v16.0.0 Theo](https://github.com/arendst/Tasmota/tree/v16.0.0), which are based on the original version and do not include default values or presets, but do include support for the [NeoPool](https://tasmota.github.io/docs/NeoPool/) sensor module for Sugar Valley pool controls.

## Tasmota with NeoPool

### Files for initial flash

> [!WARNING]
> These files are for the **initial flash** of an ESP only.
> Do **not** use them for OTA or file upload updates.

For the initial flash of an ESP32/ESP8266, using [ESP_Flasher](https://github.com/Jason2866/ESP_Flasher) is recommended.
Choose the file that matches your ESP chip type:

| Chip type            | File | Example devices |
| -------------------- | ---- | --------------- |
| ESP32 (all types)    | [tasmota32-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool.factory.bin) | M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite) |
| ESP32-S3 (all types) | [tasmota32s3-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool.factory.bin) | M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3), [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite) |
| ESP32-C3 (all types) | [tasmota32c3-origin-neopool.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool.factory.bin) | |
| ESP8266 (all types)  | [tasmota-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool.bin) | |

### Files for updating Tasmota

To update an existing Tasmota device, use the WebUI function [**Firmware Upgrade**](https://tasmota.github.io/docs/Upgrading/) → [**Upgrade by file upload**](https://tasmota.github.io/docs/Upgrading/#upgrade-by-file-upload) and choose the file that matches your ESP chip type:

| Chip type            | File | Example devices |
| -------------------- | ---- | --------------- |
| ESP32 (all types)    | [tasmota32-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool.bin) | M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite) |
| ESP32-S3 (all types) | [tasmota32s3-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool.bin) | M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3), [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite) |
| ESP32-C3 (all types) | [tasmota32c3-origin-neopool.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool.bin) | |
| ESP8266 (all types)  | [tasmota-origin-neopool.bin.gz](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool.bin.gz) | |


## Tasmota with NeoPool for debugging (compiled with DEBUG_TASMOTA_SENSOR enabled)

Same as before, but with `DEBUG_TASMOTA_SENSOR` enabled. This provides additional debugging output when used with [WebLog 4](https://tasmota.github.io/docs/Commands/#weblog), [FileLog 4](https://tasmota.github.io/docs/Commands/#filelog), [MQTTLog 4](https://tasmota.github.io/docs/Commands/#mqttlog), [SysLog 4](https://tasmota.github.io/docs/Commands/#syslog) or [SerialLog 4](https://tasmota.github.io/docs/Commands/#seriallog).

### Files for initial flash

> [!WARNING]
> These files are for the **initial flash** of an ESP only.
> Do **not** use them for OTA or file upload updates.

For the initial flash of an ESP32/ESP8266, using [ESP_Flasher](https://github.com/Jason2866/ESP_Flasher) is recommended.
Choose the file that matches your ESP chip type:

| Chip type            | File | Example devices |
| -------------------- | ---- | --------------- |
| ESP32 (all types)    | [tasmota32-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool-dbg.factory.bin) | M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite) |
| ESP32-S3 (all types) | [tasmota32s3-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool-dbg.factory.bin) | M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3), [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite) |
| ESP32-C3 (all types) | [tasmota32c3-origin-neopool-dbg.factory.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool-dbg.factory.bin) | |
| ESP8266 (all types)  | [tasmota-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool-dbg.bin) | |

### Files for updating Tasmota

To update an existing Tasmota device, use the WebUI function [**Firmware Upgrade**](https://tasmota.github.io/docs/Upgrading/) → [**Upgrade by file upload**](https://tasmota.github.io/docs/Upgrading/#upgrade-by-file-upload) and choose the file that matches your ESP chip type:

| Chip type            | File | Example devices |
| -------------------- | ---- | --------------- |
| ESP32 (all types)    | [tasmota32-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32-origin-neopool-dbg.bin) | M5Stack [Atom Lite](https://docs.m5stack.com/en/core/ATOM%20Lite) |
| ESP32-S3 (all types) | [tasmota32s3-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32s3-origin-neopool-dbg.bin) | M5Stack [Atom S3](https://docs.m5stack.com/en/core/AtomS3), [Atom S3 Lite](https://docs.m5stack.com/en/core/AtomS3%20Lite) |
| ESP32-C3 (all types) | [tasmota32c3-origin-neopool-dbg.bin](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota32c3-origin-neopool-dbg.bin) | |
| ESP8266 (all types)  | [tasmota-origin-neopool-dbg.bin.gz](https://github.com/curzon01/Tasmota-NeoPool-FW/raw/refs/heads/main/Tasmota-NeoPool/tasmota-origin-neopool-dbg.bin.gz) | |
