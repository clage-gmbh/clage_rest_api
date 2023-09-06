<p align="center"><img src="https://www.clage.com/assets/gfx/logo.svg" alt="CLAGE GmbH" width="150"> <i>REST</i></p>

# CLAGE GmbH devices REST API

## Hardware

CLAGE GmbH devices that do support [WLAN](https://en.wikipedia.org/wiki/Wireless_LAN) do also provide a [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) API, which is used by the [CLAGE Smart Control APP](https://play.google.com/store/apps/details?id=de.clage.smartcontrol) too.
This API sometimes is called "Homeserver API" but you do not need a dedicated HSX hardware if your CLAGE device is supporting WLAN:

* [E-comfort instant water heater
**DSX Touch**](https://www.clage.com/en/products/e-comfort-instant-water-heaters/DSX-Touch) *continuous-flow water heater supporting REST API over WLAN*
* new announced [**ISX**](https://www.haustechnikdialog.de/News/27889/Neue-E-Durchlauferhitzer-auf-der-ISH-2023) *will provide REST API and [Modbus RTU](https://github.com/clage-gmbh/clage_modbus)*

## Documentation

Unfortunately, the documentation is currently only available as a **[PDF in German](doc/CLAGE_HomeServer_API_v1.3.4.pdf)**. We will change that.

As an english reference you can have a look at the [third party examples](#third-party) already implemented and [usage examples in the Wiki](../../wiki#usage)

## APPs

REST API was originally developed for the smartphone APP **CLAGE Smart Control**:

* [Google Play](https://play.google.com/store/apps/details?id=de.clage.smartcontrol)
* [Apple App Store](https://apps.apple.com/de/app/clage-smart-control/id1212749880)

## Third Party

Due to the open documentation, the interface has already been integrated into various other systems.

> **Disclaimer:** The CLAGE GmbH does not provide any service for third-party software.
We do not guarantee the accuracy, reliability, or suitability of this software and are not responsible for any damages or losses resulting from its use.
By using third-party software, you agree that we are not liable for any direct, indirect, incidental, special, or consequential damages arising from the use of third-party software.
You acknowledge that you use third-party software at your own risk and that you are solely responsible for any consequences that may arise.

* **[ioBroker](https://www.iobroker.net/):** [TheBam1990/ioBroker.clage-dsx](https://github.com/TheBam1990/ioBroker.clage-dsx) *ioBroker connection to clage dsx wather Heater*

* **[Home Assistant](https://www.home-assistant.io/):** [klacol/homeassistant-clage_homeserver](https://github.com/klacol/homeassistant-clage_homeserver) *Home Assistant integration for the water heater CLAGE DSX Touch*

* **[EisBaer SCADA](https://www.busbaer.de/en):** [included](https://www.busbaer.de/de/news?story=269882)

* **[wibutler](https://dbt-platform.com):** included

* **[Python](https://www.python.org/):** [klacol/clage_homeserver](https://github.com/klacol/clage_homeserver) *Python client for accessing the Clage Waterheater via the local https-Rest-API-Endpoint*
