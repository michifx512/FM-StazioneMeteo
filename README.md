# FM-StazioneMeteo
 Progetto extrascolastico Stazione Meteo 

### Components
- ESP32
- Figaro CDM4161A - Pre-calibrated module for carbon dioxide 

## Planned features: 
- [x] ESP32
- [x] Co2 Sensor
- [x] Temperature and Humidity Sensor
- [ ] Pressure Sensor
- [ ] Windspeed Sensor
- [ ] Wind Direction
- [ ] RTC
- [ ] SD card reader (data save and server stuff)
- [ ] Solar panel
- [ ] Lithium Battery
- [ ] [optional] light and sound sensors

## Code features
- [ ] WebServer with data, graphs, file download
- [ ] Multi-Core programming
  - [ ] ULP Coprocessor triggering Main Processor every N Minutes
  - [ ] Server on one processor while also measuring every N Minutes

### useful links: 
Windspeed DIY Sensor (Anemometer)
- ["DIY 3D Printed IoT Weather Station Using an ESP32" YouTube](https://www.youtube.com/watch?v=tBGwyXPJZEQ)
- ["Homemade Arduino Wind-speed Sensor" YouTube](https://www.youtube.com/watch?v=_pW03IMpZCo)

ULP Coprocessor Programming
- ["ULP Coprocessor Programming" Expressif.com](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/system/ulp.html)


## Components table
|Type|Name|
|----|----|
|ESP 32||
|CO2 Sensor|Figaro CDM4161A|
|Temp & Humidity||
|Pressure Sensor||
|||
...
