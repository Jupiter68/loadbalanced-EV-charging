# loadbalanced-EV-charging
Charging an EV maximally on solar energy taking into account SOC, scheduled departure and the weather forecast:

## Smart home platform is based on loxone
- solar plant power measurements
- scheduled departure
- calculations of desired charging power and charging start time 
-- function of scheduled departure, estimated solar production, starting SOC, desired SOC

## EV integration is via openHAB Tesla Binding
- reading of the SOC 
- start charging
- stop charging

## Knowledge of the cloud cover forecast is via the openHAB FMI Weather Bindings
- estimate of expected solar production

## RS-485 serial communication is via openHAB MODBUS Binding
- openHAB on a Raspberry PI4 with a USB-RS485 adapter
    
## Interaction between openHAB and Loxone is via openHAB Loxone Binding

## Charging station is based on a Smart EVSE solution
- SMART EVSE charging station
- notification of the desired charging current via serial rs-485
    
  
 


