# Home Assistant Smart MAIC integration

The Smart MAIC integration listens for energy data from the device via MQTT protocol and exposes sensors as well as controls.

Tested with:
* [Розумний лічильник електроенергії c WiFi D101, однофазний, стандартна версія](https://store.smart-maic.com/ua/p684214708-umnyj-schetchik-elektroenergii.html)
* [Розумний лічильник електроенергії c WiFi D103, трифазний, розширена версія](https://store.smart-maic.com/ua/p679987290-umnyj-schetchik-elektroenergii.html)
* [Розумний лічильник імпульсів з WiFi smart-MAIC D105](https://store.smart-maic.com/ua/p811449534-umnyj-schetchik-impulsov.html)

## Highlights

### Have your energy sensors at a glance

<img src="https://github.com/krasnoukhov/homeassistant-smart-maic/assets/944286/09ef657e-0918-40bd-a204-60f09e2e2ba7" alt="sensors" width="400">

### Sync consumed energy with an external meter from the UI

<img src="https://github.com/krasnoukhov/homeassistant-smart-maic/assets/944286/1165462c-2d8b-4809-aaa4-4abaa477f79b" alt="number" width="400">

### Control the dry switch

<img src="https://github.com/krasnoukhov/homeassistant-smart-maic/assets/944286/d4740c85-174b-41f2-bf46-70aa1b3402af" alt="switch" width="400">

### Use the UI to set up integration

<img src="https://github.com/krasnoukhov/homeassistant-smart-maic/assets/944286/af16666a-e517-416d-a7c3-3a44a7af43a4" alt="setup" width="400">

## Installation

### Via HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=krasnoukhov&repository=homeassistant-smart-maic&category=Integration)

* Search for "Smart MAIC" on HACS tab in Home Assistant
* Click on three dots and use the "Download" option
* Follow the steps
* Restart Home Assistant

### Manual Installation (not recommended)

* Copy the entire `custom_components/smart-maic/` directory to your server's `<config>/custom_components` directory
* Restart Home Assistant
