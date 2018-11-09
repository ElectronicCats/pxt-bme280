[![Build Status](https://travis-ci.org/ElectronicCats/pxt-bme280.svg?branch=master)](https://travis-ci.org/ElectronicCats/pxt-bme280) 

# BME280

A package to use BME280 Digital Pressure and Humidity Sensor in MakeCode  

Author Original: shaoziyang  
Date:   2018.Mar  

Modified: Andrés Sabas  
Date:   Octuber 2018 

## I2C Address  

- 0x76/0x77  

## API
![](https://github.com/ElectronicCats/pxt-bme280/raw/master/example_maker.png)
![](https://github.com/ElectronicCats/pxt-bme280/raw/master/example_microbit.png)

- `function pressure()` : get pressure in pa  

- `function temperature()` : return temperature in Celsius.

- `function humidity():` return humidity in percent

- `function PowerOn()`: turn on BME280.

- `function PowerOff()`: goto sleep mode  

- `function Address(addr: BME280_I2C_ADDRESS)`  
set BME280's I2C address. addr may be:  
  - BME280_I2C_ADDRESS.ADDR_0x76
  - BME280_I2C_ADDRESS.ADDR_0x77

## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  

## Maintainer

[Electronic Cats](https://github.com/ElectronicCats) invests time and resources providing this open source design, please support Electronic Cats and open-source hardware by purchasing products from Electronic Cats!

## Supported targets

* for PXT/maker
* for PXT/micro:bit

```package
bme280
```