# Changelog

Firmware for the MFRESP8266 hardware.

## [0.0.4] 2022-01-13 

### Changed
- Change header file from .hpp to .h and replace include guards with #pragma once
- Replace png files with svg files.
- Change default MQTT_HOST to mqtt.dh.ctb.co.at

## [0.0.3] 2021-11-13

### Bugfix
- ESP_OTA_GitHub [DynamicJsonDocument NoMemory](https://github.com/yknivag/ESP_OTA_GitHub/issues/7)
- Optimizing free heap memory

## [0.0.2] 2021-11-08

### Changed
- Update [ArduinoJson library](https://github.com/bblanchon/ArduinoJson) to V6.x
- [Load and save configuration](https://github.com/bblanchon/ArduinoJson/issues/1473#issuecomment-760970337) for ArduinoJson to V6 
- Update [Bootstrap] (https://getbootstrap.com/) v4.4.1 to v4.5.3
- Update [jQuery] (https://jquery.org/) v3.4.1 to v3.5.1

### Deleted
- Delete not used files in html folder

### Added
- Add data folder
- Add certs.ar and config.json file to data folder

### ESP_OTA_GitHub
- Update certs-from-mozilla.py from [esp8266/Arduino](https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/examples/BearSSL_CertStore/certs-from-mozilla.py)
- [Fixed compile error and warnings](https://github.com/yknivag/ESP_OTA_GitHub/pull/6) in ESP_OTA_GitHub library

## [0.0.1] 2021-11-07

### Changed
- Split mfresp8266 in doc-user, doc-dev, firmware and hardware.
- WifiManager timeout increased to 10 minutes.

## [0.0.0] 2020-05-24
- Initial working version
