## Korners
Rounded window corners for KDE Plasma 5+.

![After](https://raw.githubusercontent.com/53n531/korners/master/screenshot.png)

## How to build:
 
 Install the build dependencies:
 ```
 sudo pacman -S cmake extra-cmake-modules qt5-tools
 ```
 
 
Clone this repository:
```
git clone https://github.com/liempo/korners.git
```

Build and install:
```
cd korners; mkdir qt5build; cd qt5build; cmake ../ -DCMAKE_INSTALL_PREFIX=/usr -DQT5BUILD=ON && make && sudo make install && (kwin_x11 --replace &)
```

It should be now activated.

For better results turn off the border size in:
System Settings --> Application Style --> Window Decoration
