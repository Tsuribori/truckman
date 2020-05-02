## Truckman [![PyPI version](https://badge.fury.io/py/truckman.svg)](https://badge.fury.io/py/truckman)

Simpler backing-up of named Docker volumes to tar archives and unpacking of them
into new named Docker volumes.

### Save a volume

`truckman --save volume_name > archive.tar`

### Load a volume

`truckman --load archive.tar --name volume_name`
