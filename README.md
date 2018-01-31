
[![HIH6020](HIH6020_I2C.png)](https://store.ncd.io/product/hih6020-humidity-and-temperature-sensor-%C2%B14-5-rh-%C2%B11-0c-i2c-mini-module/)

# HIH6020

Honeywell HumidIcon Digital Humidity/Temperature Sensors are digital output-type relative humidity and temperature sensors combined in the same package.These sensors provide an accuracy level of ±4.5% RH. They possess industry-leading long-term stability and reliability, true temperature-compensated digital I2C, energy efficiency, and ultra-small package size and options.
This Device is available from www.ncd.io 

[SKU: HIH6020_I2CS]

(https://store.ncd.io/product/hih6020-humidity-and-temperature-sensor-%C2%B14-5-rh-%C2%B11-0c-i2c-mini-module/)
This Sample code can be used with Arduino.

Hardware needed to interface HIH6020 sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/hih6020-humidity-and-temperature-sensor-%C2%B14-5-rh-%C2%B11-0c-i2c-mini-module/">HIH6020 Humidity and Temperature Sensor</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

HIH6020:

Honeywell HumidIcon Digital Humidity/Temperature Sensors are digital output-type relative humidity and temperature sensors combined in the same package.These sensors provide an accuracy level of ±4.5% RH. They possess industry-leading long-term stability and reliability, true temperature-compensated digital I2C, energy efficiency, and ultra-small package size and options.

Applications:

• HVAC

• Weather stations

• Air compresser

• Respiratory therapy

• Indusrial incubators/microenvironments

How to Use the HIH6020 Arduino Library
The HIH6020 is very easy to interface as following.

1.Address calling:The following command is used to call the address of HIH6020 to start the transmission.

            hih.getAddr_HIH6020(HIH6020_DEFAULT_ADDRESS);   // 0x27

2.Temperature measurement:The following command is used to measure the temperature in celcius.

             cTemp = hih.Measure_Temperature();
            
3.Humidity measurement:The following command is used to measure the humidity in %RH.

             humidity = hih.Measure_Humidity();
