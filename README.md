# Korners
Rounded window corners for KDE Plasma 5+.

![After](https://raw.githubusercontent.com/alex47/KDE-Rounded-Corners/master/screenshot.png)

# How to build:
```
git clone https://github.com/53n531/korners

cd korners; mkdir qt5build; cd qt5build; cmake ../ -DCMAKE_INSTALL_PREFIX=/usr -DQT5BUILD=ON && make && sudo make install && (kwin_x11 --replace &)
```

It should be now activated.

For better results turn off the border size in:
System Settings --> Application Style --> Window Decoration
