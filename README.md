pyOBDlib
========

A fork of pyOBD (http://www.obdtester.com/pyobd), however only the ELM327 communications were brought over and the wx GUI was removed.

## Install
I've only tested this on Mac OSX 10.7 but it should work on more platforms:
* Install pyserial 2.6: http://pypi.python.org/pypi/pyserial/

## Getting Started
 * Pass the USB-Serial interface as the fisrt command-line argument, for example:
	$ python obd_io.py /dev/tty.usbserial-A6008a3j
