## Sungrow modbus registers for use in ioBroker

`Multiple device IDs` needs to be checked in the adapter since the battery now has its own modbus address. Also, you need to have updated your battery firmware, for example to version 21. The firmwares can be found [here](https://github.com/sungrow-firmware/firmware). 
If your battery does not show up as a seperate entity in your cloud portal or WinetS adapter, do a firmware update of your WinetS adapter and Sungrow hybrid inverter, and then do a manual firmware update of your hybrid inverter using the appropriate battery firmware from the repository linked above.

The battery specific registers are taken from [here](https://github.com/mkaiser/Sungrow-SHx-Inverter-Modbus-Home-Assistant/blob/main/modbus_sungrow.yaml).
