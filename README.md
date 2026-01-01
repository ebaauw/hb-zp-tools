<span align="center">

# Homebridge ZP Tools
[![Downloads](https://img.shields.io/npm/dt/hb-zp-tools.svg)](https://www.npmjs.com/package/hb-zp-tools)
[![Version](https://img.shields.io/npm/v/hb-zp-tools.svg)](https://www.npmjs.com/package/hb-zp-tools)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

</span>

## Homebridge ZP Tools
Copyright © 2016-2026 Erik Baauw. All rights reserved.

This repository provides a standalone installation of the command-line tools from [Homebridge ZP](https://github.com/ebaauw/homebridge-zp):

Tool      | Description
--------- | -----------
`zp `     | Interact with Sonos ZonePlayer from the command line.

Each command-line tool takes a `-h` or `--help` argument to provide a brief overview of its functionality and command-line arguments.

### Prerequisites
None; Homebridge ZP communicates with a Sonos ZonePlayer using its local SOAP/HTTP API.
This API is self-documented on each ZonePlayer.
Issue `zp description -S` to see a JSON version.

### Installation
```
$ sudo npm -g i hb-zp-tools
```
