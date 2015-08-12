# gen-asset-tracker
Generic asset tracker device with multiple communications interfaces. This is also sometimes referred to as a hybrid tracking systems in the industry due to the fact that it can communicate on more than one communications device, depending on the conditions.

# License
The Generic asset tracker device is licensed under the GNU Affero General Public License V3.0

Alternatively, for users who do not wish to make their design modifications public, a Commercial License will be made available as an option at a later stage. Currently I am not in a position to really lay out the terms of the Commercial License, but it will follow in the next few weeks.

# Introduction
This project is an open source implementation of a generic asset tracking platform.

Full specifications will follow later, but for now the general requirements are:
* determine position/location with onboard GPS
* sensor inputs and output
* report position log, sensor statusses to a backend useing one of the following possible communciations interfaces
  * GSM/GPRS
  * Iridium satellite modem
  * WIFI connection
  * proprietary 433MHz/868MHz/2.4GHz RF interfaces
  * Bluetooth interface
  * Possible NFC
* RFID interface on device
* Possible IP67 rating
* Run for a period of two years from a battery pack
* Onboard accelerometer/movement sensor
* Onboard storage to log data and events
* Scripting features
* and many more as the project evolves

If you are interested in assisting please do not hesitate to contact me.

