## RNS-E CarPC


## Overview

rnsecarpc will provide some useful scripts and howtos to turn your Audi RNS-E navigation system into a recent media engine.
The heart of the environment will be a Raspberry Pi using a PiCan2 board to interact with the CAN-bus of the RNS-E unit.
That way you will be able to control Kodi directly via the RNS-E knobs, so that no additional input device is required.

Kodi will be used as the main interface and some python scripts will run in the background to read and write to the CAN bus.


## Features

- Control Kodi via RNS-E
- Dedicated RNS-E skin for Kodi
- Display useful car telemetry taken from CAN bus


## Cabling schema

![Alt text](/screenshots/schema.jpg?raw=true "Cabling schema")


## Requirements

- RNS-E (see below for models)
- Raspberry Pi (tested on Pi3, to be tested on Pi zero W soon)
- PiCan2 CAN-bus board
- Multimedia Adapter IMA Interface (79€)

## RNS-E models
- RNS-E 192 w/o rear camera -> Working OK
- RNS-E 192 w/ rear camera -> Partly OK
- RNS-E 193 w/ rear camera + AMI -> untested


## Part list
- RNS-E w/o AUX+Camera: http://amzn.to/2moT8wH
- RNS-E w/ AUX+Camera: Kufatec 35538 + Kabelsatz 35951
- Raspberry Pi3: http://amzn.to/2lkW24I
- Pi3 case (might need modification): http://amzn.to/2lH3O9U
- PiCan2: http://amzn.to/2lGRlEM
- SD card: http://amzn.to/2llmcnG
- stepdown module (for 12v > 5v constant power): http://amzn.to/2moYvfp
- RNS-E unlocking brackets: http://amzn.to/2ll34WW
- Quadlock extension (only required if not having a rear camera): http://amzn.to/2lGKn0R
- HDMI to RCA converter: http://amzn.to/2lllRBB
- HDMI cable: http://amzn.to/2laXVQp
- RCA cable: http://amzn.to/2llcbXv
- USB cable: http://amzn.to/2lGUClW


## Future outlook

- OBD2 readings
- Powertrain CAN-bus readings
- Driftbox features, G-meter, etc.
- Navigation (e.g. via NavIt)



## Remarks

Software and guides will be uploaded very soon.
Cabling, part list and software are currently under heavy rework and subject to change.
If you have questions, do not hesitate to contact us either here or on the facebook page.


Further information:
- https://www.facebook.com/rnsecarpc
- https://www.youtube.com/watch?v=OYD36QduiVg
