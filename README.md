<p align="center"><img src ="http://www.sigfox.com/themes/custom/sigfox/images/logo-2016.svg" width="300"></p>

## Sigfox HidnSeek - Movement Sensor

This code example shows you how to use the HidnSeek GPS Tracker to trigger upon movement. You might want to use this to track/alert you if your bag/suitcase is moved or how many times a door has been opened.

### Prerequisites

##### Hardware

* HidnSeek GPS Enabled Tracker
* Micro USB Cable

##### Software

* Arduino IDE (Windows, MacOS or Linux)
* Associated Install/Setup Libraries

### Introduction

The example uses a counter to store the number of times that the device's accelerometer is triggered between transmitting a message (once every 10 minutes if the accelerometer has triggered). It only broadcasts once every 10 minutes to meet the ETSI requirement for duty cycle of unlicensed frequencies.

The sensitivity of the accelerometer can be adjusted in accordance to the 'MMA8653.h' library.

### Future Improvements

Currently this example doesn't support any power saving features that you might employ on a typical battery powered projects.

* Power Saving / Deep Sleep Modes (Low Power Lib could be used as the HidnSeek has a ATMega328P)
* Example of an app/web app to alert you to its movement.

If you want to try and help out with improvement or suggestion, please fork this repo and make a pull request!
