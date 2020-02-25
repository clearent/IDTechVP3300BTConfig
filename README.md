![Screenshot](docs/clearent_logo.jpg)

# IDTech VP3300 Bluetooth Configuration

:warning: Use configuration files from the config/prod folder when configuring readers to be used in the live environment.

## Firmware capability

[Contactless Configuration Willow - 02-03-2020](config/prod/willow_tap_prod_20200203.json) + [Firmware .151](https://github.com/clearent/IDTechVP3300BTConfig/blob/master/firmware/VP3300%20Bluetooth%20NEO%20v1.01.151_USBHID.txt)

[Contactless Configuration Willow - 02-03-2020](config/prod/willow_tap_prod_20200203.json) + [Firmware .090](https://github.com/clearent/IDTechVP3300BTConfig/blob/master/firmware/VP3300%20Bluetooth%20NEO%20v1.01.090_USBHID.txt)

:warning: Willow is compatible with firmware version .090 only because the framework has extra logic to address
an idtech contactless issue. Firmware version .151 is recommended instead.


## Release Notes

Date: 3-6-2019

VP3300 BT Unencrypted

* Sleep mode is extended to 255 seconds

* Test Config File: config/test/good_betty_03062019.json

* Firmware file: firmware/VP3300 Bluetooth NEO v1.01.090_USBHID.txt

Date: 11-20-2019

Added support for contactless

* Test Config File: config/test/winnie_tap_20191120.json

* Firmware file: firmware/VP3300 Bluetooth NEO v1.01.151_USBHID.txt

Date: 12-10-2019

* Modified the FFFC tag on the MasterCard contactless configuration group so Apple Card will work.

* Test Config File: config/test/winnie_tap_20191210.json

Date: 12-11-2019

* Introduced two folders, one for test, one for prod.
* Updated the Ca Public keys to be the LIVE keys.

* Prod Config File: config/prod/winnie_tap_prod_20191211.json

