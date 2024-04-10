# ha-addons-ebusd2
ebusd2 addon for http://home-assistant.io

Based on [LukasGrebe/ha-addons](https://github.com/LukasGrebe/ha-addons)

Adds second ebusd addon so you can communicate with another ebusd adapter from your home assistant installation.

## How to Install
1. In Supervisor go to the Add-on Store,
2. In the overflow menu click "Repositories"
3. Add `https://github.com/piotrtobolski/ha-addons-ebusd2`
4. Wait for the ebusd Add-on to show up or click reload in the same overflow menu
5. Install eBUSd.
6. 6. Follow Documentation, Setup and Install of the Add-on


## [ebusd](https://github.com/piotrtobolski/ha-addons-ebusd2/tree/main/ebusd) 

This Add-on runs [ebusd](http://ebusd.eu), a daemon for handling communication with eBUS devices connected to a 2-wire bus system (“energy bus” used by numerous heating systems), in [Home Assistant OS](https://www.home-assistant.io/installation/raspberrypi). You can simply plugin a ebus hardware interface into your RaspberryPi, and install the addon to run ebusd.


# Thanks ...

Thank you to

- https://github.com/LukasGrebe
- https://github.com/m-reuter
- https://github.com/john30
- https://github.com/ludeeus
- Https://github.com/tim-devel
