# ATS_MINI VERSION HISTORY

Unless otherwise stated, the latest version should be used

The zip file contains a pdf document with programming instructions and further details about the firmware

## V1.01 (05/03/2025): ATS_MINI_v1_01_8M.zip (Latest)

- Changed app_id to force stock firmware to reset EEPROM
- Added “MODE” configuration per band
- Added hold off timer to try and improve tuning speed

## V1.00 (03/03/2025): ATS_MINI_v1_00_8M.zip

- Added 1MHz step for FM
- Added GPIO1 output control for external RF switch (0 = FM)
- Replaced rx.frequencyUp() and rx.frequencyDown() calls with alternative code to improve band limit behaviour
 

## V0.30 (01/03/2025): ATS_MINI_v0_30_8M.zip

- Modified Calibration to per band, range +/- 2000 Hz

## V0.28 (27/02/2025): ATS_MINI_v0_28.zip

This version was compiled for the ESP32-S3 (N16R8) and will not work on receivers that have the ESP32-S3 (N8R2). Subsequent releases are compiled for 8MB Flash, which should be compatible with both ESP32-S3 module types currently being fitted to the receivers

- First release
