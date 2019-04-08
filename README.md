# desktop-file-memos
A desktop classification app on Linux.

# build depends
- qt5-default
- libqt5x11extra5-dev
- libx11-dev
- libglib2.0-dev

# build && test
- mkdir build && cd build
- qmake ..
- make
- ./desktop-file-memos

## auto start && and start in menu
- sudo cp desktop-file-memos /usr/bin
- sudo cp desktop-file-memos.desktop /etc/xdg/autostart
- sudo cp desktop-file-memos.desktop /usr/share/applications

# screenshot

## demo
![demo](https://github.com/Yue-Lan/desktop-file-memos/blob/master/screenshot/demo.png)
## start in menu
![start in menu](https://github.com/Yue-Lan/desktop-file-memos/blob/master/screenshot/manual-start.png)
## tray menu
![tray menu](https://github.com/Yue-Lan/desktop-file-memos/blob/master/screenshot/tray-icon-menu.png)
## titlebar menu
![titlebar menu](https://github.com/Yue-Lan/desktop-file-memos/blob/master/screenshot/titlebar-menu.png)
