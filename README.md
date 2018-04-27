# Arduino-LDR-Application

## Description
This project utilizes the Arduino ESP32 Espressif to create a light-sensing IoT device to automatically upload sensor readings to an app. 

## Prerequisites
### Hardware
For this project, it is necessary to acquire a microcontroller which is programmable by the Arduino IDE and compatible with the ESP32 Espressif and wifi.

The microcontroller presented in this project is the [Adafruit HUZZAH32 - ESP32 Feather](https://learn.adafruit.com/adafruit-huzzah32-esp32-feather/overview).

A photoresistor is used in this project, but other sensors like a phototransistor or photodiode can be used depending on light reading requirements.

A resistor between 1000 Ohms and 10,000 Ohms is recommended for the voltage divider circuit, that will be discussed later.

All parts will be placed on a breadboard and connected by jumper wires.

**Our Parts List**
* Adafruit HUZZAH32 - ESP32 Feather
* Eboot Photoresistor
* Adafruit 3.7v 2000mAh Litium Ion Battery
* 2"x3"x4" Precision 3D Printed Container
* 1000 ± 1% Ohm Elegoo Resistor
* Dupont Jumper Wires - 2 Male to Female, 4 Male to Male
* Breadboard - Self-Adhesive (2 power busses, 10 columns, 30 rows)



### Software
The [Arduino IDE](https://www.arduino.cc/en/Main/Software) will be needed in order to program the IoT device.

The [Thinger.io](https://github.com/thinger-io/Arduino-Library) arduino library should be added.

The [Autodesk Fusion 360](https://www.autodesk.com/products/fusion-360/overview?mktvar002=724861&mkwid=sOICwxb1H|pcrid|226118724187|pkw|autodesk%20fusion%20360|pmt|e|pdv|c|slid||pgrid|52893102612|ptaid|kwd-488376946792|&intent=US-Fusion360-BR&utm_medium=cpc&utm_source=google&utm_campaign=GGL_FUSION360_US_BR_SEM_EXACT%3EBrand&utm_term=autodesk%20fusion%20360&utm_content=sOICwxb1H|pcrid|226118724187|pkw|autodesk%20fusion%20360|pmt|e|pdv|c|slid||pgrid|52893102612|ptaid|kwd-488376946792|&gclid=Cj0KCQjw8YXXBRDXARIsAMzsQuXhwh4B2E9o9E_S_hIudQVvcd4p0aYrDlxUHR1Ml3hEM7ls09GC-zUaAnlCEALw_wcB&dclid=CLSc1Z_X2doCFUfawAodU7cOsw) software is used to design files to be printed by a 3D printer.

**Our Software**
* Arduino IDE
* Thinger.io
* Autodesk Fusion360
