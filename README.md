# arduino-libg722

## Introduction

The G.722 module is a bit exact implementation of the ITU G.722 specification
for all three specified bit rates - 64000bps, 56000bps and 48000bps. It passes
the ITU tests.

To allow fast and flexible interworking with narrow band telephony, the
encoder and decoder support an option for the linear audio to be an 8k
samples/second stream. In this mode the codec is considerably faster, and
still fully compatible with wideband terminals using G.722.

## History

The code was originally written by Milton Anderson <milton@thumper.bellcore.com>
from BELLCORE, and has been modified by the Chengxiang Lu and Alex Hauptmann
from the Speech Group, School of Computer Science, Carnegie Mellon University,
to be fairly fast and efficient, while retaining high fidelity.

Steve Underwood <steveu@coppice.org> improved the code a lot later on and
contributed it into several popular open source projects.

Librarized by Sippy Software, Inc.

## Arduino Library

You can download the library as zip and call include Library -> zip library. Or you can __git clone__ this project into the Arduino libraries folder e.g. with

```
cd  ~/Documents/Arduino/libraries
git clone pschatzmann/arduino-libg722
```

The use of git is recommended because you can easily update to the latest version just by executing the git pull command in the project folder.

## Documentation

I recommend to use this library together with my [Arduino Audio Tools](https://github.com/pschatzmann/arduino-audio-tools). 
This is just one of many __codecs__ that I have collected so far: Further details can be found in the [Encoding and Decoding Wiki](https://github.com/pschatzmann/arduino-audio-tools/wiki/Encoding-and-Decoding-of-Audio) of the Audio Tools.

## License

This code is mostly Public Domain. Library test code is under BSD 2-clause
license.

See LICENSE for copyright details and each individual file for specifics.
