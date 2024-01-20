# ams-isoftstat-build
Utilities for testing and building of the [ams-isoftstat](https://github.com/kulhanek/ams-isoftstat) package.

## Building and Installation

### Testing Mode
```bash
$ git clone --recursive https://github.com/kulhanek/ams-isoftstat-build.git
$ cd ams-isoftstat-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./04.build-inline.sh      # build the code inline in src/
```

### Production Build
```bash
$ git clone --recursive https://github.com/kulhanek/ams-isoftstat-build.git
$ cd ams-isoftstat-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./10.build-final.sh       # install dir: /opt/ams-isoftstat/9.0
```




