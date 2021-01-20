# loadbalanced-EV-charging
Maximum charging of an EV based with solar energy taking into account SOC, scheduled departure and the weather forecast

Smart home platform is based on loxone
-> solar plant power measurements
-> scheduled departure

EV integration is via OPENHAB Tesla Binding
-> reading of the SOC 
-> start charging
-> stop charging

Knowledge of the cloud cover forecast is via the OPENHAB FMI Weather Bindings
-> estimate of expected solar production

RS-485 serial communication is via OPENHAB MODBUS Binding

Interaction between OPENHAB and Loxone is via OPENHAB Loxone Binding

Charging station is based on a Smart EVSE solution
-> notification of the desired charging current via serial rs-485


