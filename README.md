# ams-srv-build
Utilities for testing and building of the [AMS - Advanced Module System](https://github.com/kulhanek/ams) package.

## AMS Servers Features:
* iSoftRepo web service
* module usage collector

## Building and Installation

### Testing Mode
```bash
$ git clone --recursive https://github.com/kulhanek/ams-srv-build.git
$ cd ams-srv-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./04.build-inline.sh      # build the code inline in src/
```

### Production Build
```bash
$ git clone --recursive https://github.com/kulhanek/ams-srv-build.git
$ cd ams-srv-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./10.build-final.sh       # install dir: /opt/ams-servers/8.0
```




