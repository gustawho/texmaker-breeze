# texmaker-breeze
 An attempt to integrate Texmaker with Breeze, the default visual style in KDE Plasma 5.x.

## Installation
Dependencies:
* Breeze icon theme
* poppler-qt5
* qt5-webkit
* qt5-script
* desktop-file-utils

Enter the directory where you cloned this repo and run:
```bash
qmake-qt5 PREFIX=/usr texmaker.pro
make
sudo make INSTALL_PATH=/ INSTALL_ROOT=/ PREFIX=/usr install
```
If you're on Arch Linux and you don't want to build the package yourself, just install it from my repository:

```bash
[gustawho]
Server = http://gustawho.x10.mx/repo/x86_64/
```
Key-ID: 2C575D76

x86_64 only!

There you can also grab the PKGBUILD and edit it for your needs.

## Screenshots
![Main Window](http://gustawho.x10.mx/files/light.png)
![Dark variant](http://gustawho.x10.mx/files/dark.png)

