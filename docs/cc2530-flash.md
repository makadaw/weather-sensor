# How to flash CC2530

## cc-tools

Install

```
brew install autoconf automake libusb boost pkgconfig libtool
git clone https://github.com/dashesy/cc-tool.git
./bootstrap
./configure
make
```

Flash

```
sudo ./cc-tool -e -w <hex path>
```

## Setup

How to connect pins:

![Pin out](smartrf04eb-pinout.jpg)

Pins on cable is mirrored!

![Pins for cable](cable-pins.jpeg)

![Example](pins-example.jpeg)
