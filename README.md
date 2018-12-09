# Off-Grid-EVSE-Control

This unit will be physically attached to a Victron BMV via the serial interface, it will have a few functions.

Main Functions:
1- Provide MQTT messages to allow the EVSE to vary output current based on incoming power (voltage, current etc).
2- Provide MQTT messages to allow other power consumers to shut down if main battery SOC drops.
