# Thyme after Thyme project requirements
-------------------
## Aim
The aim of this project is to provide an extensible four zone garden watering controller, drawing water from a water butt or mains supply.

# Desired features
- 12Vdc pump control
- Pump flow monitoring
- Four controllable watering zones
- Tank level monitoring
- Home Assistant integration
- External I2C bus for remote sensors
- 6 MOSFET outputs
- 6 digital inputs

# Nice to have features
- Small screen for at-a-glance status
- Isolated inputs/outputs

## Hardware requirements
- ESP32 main microcontroller
- Five 12V solenoid valves (four zones, one aux for either mains water into manifold or tank top-up)
- MOSFET general purpose outputs (1A per channel)
- Differential I2C bus for external devices
- Ultrasonic level sensing
