# LipoMeter_5s (hardware)
A measurementsystem to check the voltages and currentflow of a lipobattery up to 5 cells over I2C.
CAUTION: THIS IS UNDER HEAVY CONSTRUCTION AND NOT IN PRODUCTION STATE!
# changelog
## v0.1 (latest)
- [x] voltage measurement over I2C (ADS7830 IC)
- [x] temp measurement with a Ds18b20 IC
problems:
- board gets fried when current is drawn from battery!
## v0.2
- temp measurement with NTC
- current measurement with an ACS712-30
- opto-isolation if I2C connection
