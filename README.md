# astra-linux-orel-qt5

Docker image for [Qt 5](https://www.qt.io/) development under 
[Astra Linux Orel](https://astralinux.ru/products/astra-linux-common-edition/).

Installed components:
- build-essential
- qt5-default
- qtdeclarative5-dev
- qml-module-qtquick-controls
- libqt5serialport5-dev
- qtscript5-dev
- zlib1g-dev 

This image can be used either interactively or as part of a CI build.

For interactive use: 
```
$ docker run -it --rm -v $(pwd):/home/dev arogov/astra-linux-orel-qt5
```

