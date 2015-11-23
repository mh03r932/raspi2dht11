Humidity Logger with two DHT 11 sensors 
==================================
All this project aims to do is using the Adafruit Python DHT Sensor Library to use two sensors to create a log with humidiy measurements.

To this end I created the google_spreadsheet_twosens.py and this repo exists primarily to store this for me.


If you are thinking about a similar project you should start here:
https://github.com/adafruit/Adafruit_Python_DHT.
or here:
https://learn.adafruit.com/dht-humidity-sensing-on-raspberry-pi-with-gdocs-logging/software-install-updated




Adafruit Python DHT Sensor Library
==================================

Python library to read the DHT series of humidity and temperature sensors on a Raspberry Pi or Beaglebone Black.

Designed specifically to work with the Adafruit DHT series sensors ----> https://www.adafruit.com/products/385

Currently the library is only tested with Python 2.6/2.7.

For all platforms (Raspberry Pi and Beaglebone Black) make sure your system is able to compile Python extensions.  On Raspbian or Beaglebone Black's Debian/Ubuntu image you can ensure your system is ready by executing:

````
sudo apt-get update
sudo apt-get install build-essential python-dev
````

Install the library by downloading with the download link on the right, unzipping the archive, and executing:

````
sudo python setup.py install
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution
