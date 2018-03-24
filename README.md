# WaterWorld / IoTHackathon2018

## Description

WaterWorld is a motion sensor water feature (future shower head) to conserve water & save money on water bills. This project is inspired by existing shower heads like [this one] (https://www.costco.ca/Akuaplus-A-Motion-Sensor-Shower-Head.product.100356527.html) and [this] (https://www.amazon.com/Adjustable-Multi-color-Temperature-Sensor-Shower/dp/B00XDT1RIE)  

## Technologies used / Prerequisites

* [PIR sensor](https://www.adafruit.com/product/189)
* [Adafruit Power Relay FeatherWing](https://www.adafruit.com/product/3191)
* [Arduino IDE](https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/using-arduino-ide)
* [Git](https://git-scm.com/)

## Further Sources

* [Door Sensor](https://www.adafruit.com/product/375)
* [Adafruit Parts Pal](https://www.adafruit.com/product/2975)

## Installation

* `$ git clone https://github.com/IoTHackathon2018/WaterWorld.git`

## Specifications

| Behavior |  Input   |  Output  |
|----------|:--------:|:--------:|
|Water feature is off|Power Relay keeps water off|Water is off|
|Water feature turns on with motion|PIR sensor is triggered on by motion|Water flows|
|Water feature turns off|Hand moves away from water flow|Water turns off|

## Further Specifications
|Shower door sensor alerts motion sensor|Shower door is opened, triggering motion sensor|Motion sensor is ready to detect motion|
|Shower door sensor alerts led lights|Shower door is opened, triggering led lights|LED lights turn on|
|LED lights change colors|Shower door is opened, triggering led lights|LED lights change color|


## Known Bugs
* N/A

### Support and contact details
  _jincamou@gmail.com_ _stephaniespears1@gmail.com_

### License
  _MIT_ &copy; _2018_ **Azure Hippe** **Cody Long** **jin camou** **Max Smiley** **Stephanie Spears**
