Python script to control the EPROM Emulator.

Requires python 3.8, and the following libraries:
* pySerial (pip install pyserial)
* pySimpleGui (pip install pysimplegui) - for the beta GUI support to work

parameters like type of memory, hex file etc should be provided via command line.

There is "beta" GUI support - brings GUI parameter selection, just run the script without parameters and GUI will show up (of course only works in GUI environments :))


Example of parameters and output:

#python.exe EPROM_NG_v1.5h.py -mem 27256 -spi y -auto n 27256.HEX com4
Running EPROM EMU NG python script version 1.5h

Using serial port COM4, emulating: 27512 EPROM

-- attempting to get sync --

-> HW: 1.4 @ 115200, FW: 1.6, SPI: 0, Auto: 0, Last EPROM: 6, mygeekyhobby.com 2020 :)

-- prcessing file --
-> Emulator Running.
