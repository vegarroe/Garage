# Garage
Garage node
HW: Wemos D1 mini
Communication: wifi

This project i made to control my garage door ower wifi with mqtt as the protocol.

Interface to garage door is digital and uses the folowing inputs and outputs (seenfrom the garage door sideof the interface):
1 DI for up
1 DI for down
1 DO for moving (pulse of 0.5 Hz)

To supervise actual state two external end switches are instlalled:
1 DO for cosed
1 DO for open (future signal)

To supervise temperature and humidity in the garage:
1 AM2302/XXX22 sensor
