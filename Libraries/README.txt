Export the files and replace them with your original libraries.

Existing libraries
- TFT_eSPI
- SmartRC-CC1101-Driver-Lib-master

When using Arduino IDE for uploading the code, make sure to install the correct version of the standard libraries (dependancies):
	TFT_eSPI@^2.5.43            Use .zip file (uncompressed)
	RF24@^1.4.11                https://github.com/nRF24/RF24/archive/refs/tags/v1.4.11.zip
	IRremoteESP8266@^2.8.6      https://github.com/crankyoldgit/IRremoteESP8266/archive/refs/tags/v2.8.6.zip
	NimBLE-Arduino@^1.4.3       https://github.com/h2zero/NimBLE-Arduino/archive/refs/tags/1.4.3.zip
	Adafruit PN532@^1.3.4       https://github.com/adafruit/Adafruit-PN532/archive/refs/tags/1.3.4.zip
	rc-switch@^2.6.4            https://github.com/sui77/rc-switch/archive/refs/tags/2.6.4.zip
  XPT2046 Touchscreen@^1.4    https://github.com/PaulStoffregen/XPT2046_Touchscreen/archive/refs/tags/v1.4.zip
	ArduinoJson@^7.2.0          https://github.com/bblanchon/ArduinoJson/archive/refs/tags/v7.2.0.zip
	PCF8574 library@^2.4.0      https://github.com/xreef/PCF8574_library/archive/refs/tags/v2.4.0.zip
	arduinoFFT@^1.6.1           https://github.com/kosme/arduinoFFT/archive/refs/tags/v1.6.1.zip
	SmartRC CC1101 Driver Lib   Use .zip file (uncompressed)
	Adafruit NeoPixel@^1.12.3   https://github.com/adafruit/Adafruit_NeoPixel/archive/refs/tags/1.12.2.zip

Dependancies can either be installed directly via the Arduino IDE app's Library Manager or by downloading each file and placing them in the correct directory depending on the OS used:
  MacOS:   ~/Documents/Arduino/libraries/
  Windows: ~\<YourUsername>\Documents\Arduino\libraries\
  Linux:   ~/Arduino/libraries/
