
<p align="center">My Channel</br><b>
| <a href="https://discord.gg/GCehyym">Discord</a> | <a href="https://youtube.com/channel/UC3sLb7eZCu72iv3G1yUhUHQ">YouTube</a> |</b></p>

---
## Debian on Termux Android

---
Announcement :

For android 12 in [Termux v0.119.1](https://apkcombo.com/termux/com.termux/) fixed.

---
• Install Apps on Android
- [x] [Termux](https://github.com/termux/termux-app/releases)
- [x] [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

## Installation

Copy and paste this command to Termux :
> pkg update && pkg upgrade

* Install Debian
```
pkg install wget -y ; wget https://raw.githubusercontent.com/wahasa/Debian/main/install.sh ; chmod +x install.sh ; ./install.sh
```

* Start Debian
```
debian
```

* Stop Debian
```
exit
```

* Remove Debian
```
rm -rf debian-fs
```

---
Basic commands Ubuntu
> apt update : Update list package.</br>
> apt upgrade : Upgrade package.</br>
> apt search (pkg) : Search package.</br>
> apt install (pkg) : Install package.</br>
> apt autoremove (pkg) : Delete package.</br>
> apt -h : Help all commands

---
## [Desktop Environment](https://github.com/wahasa/Debian/issues/8)

on Debian, run this command :

> apt update && apt upgrade

* [Install Desktop-xfce](https://youtu.be/Es9ncg6vBSk)

```
apt install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/Desktop/de-xfce.sh && chmod +x de-xfce.sh && ./de-xfce.sh
```

* [Install Desktop-lxde](https://youtu.be/_Q0FZd6ZUyo)
```
apt install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/Desktop/de-lxde.sh && chmod +x de-lxde.sh && ./de-lxde.sh
```

* [Install Desktop-lxqt](https://youtu.be/qywRCj1cOKw)
```
apt install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/Desktop/de-lxqt.sh && chmod +x de-lxqt.sh && ./de-lxqt.sh
```

* [Install Desktop-kde](https://youtu.be/XFO2GIPvmiY)
```
apt install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/Desktop/de-kde.sh && chmod +x de-kde.sh && ./de-kde.sh
```

---
Note :
- [x] Soundfix
- [x] Browserfix [Click here,.](https://github.com/wahasa/Debian/issues/5#issuecomment-1175778341)
- [x] Install LibreOffice [Click here,.](https://github.com/wahasa/Debian/issues/9#issuecomment-1321005437)

Visit problem now in : [Issues](https://github.com/wahasa/Debian/issues)

---
## VNC Viewer

* Start VNC Server

on Debian, run this command to start :

```
vnc-start
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Debian Desktop
```

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on Debian, run this command to stop :

```
vnc-stop
```
</br>

---
<p align="center">Good Luck</p>

---
