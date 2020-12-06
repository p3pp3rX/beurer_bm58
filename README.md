# beurer_bm58
Import data from Beurer BM 58.

Apparently there are at least two versions of the BM 58 out there:

* Connected via USB-Serial converter (New ttyUSB device created) -> [This is for you](https://github.com/DaveDavenport/BPM)
* Connected as HID device: "0c45:7406 Microdia" -> This script might work for you

Reads out data from both users.
Multiuser support taken from https://github.com/dicer/beurer_bm58

Copy "10_beurer.rules" file to your udev directory to able to read data as member of the group users.
