# XKB-French-QWERTY-Keyboard-Layout
 - For PC-105 US standard keyboard.
 - Work well on Ubuntu, Debian and CentOS.
 - For Windows and Mac OS version, see below.

### How it looks ?

![qwerty-fr layout](http://marin.jb.free.fr/qwerty-fr/qwerty-fr-keymap.gif)


### How to use on Debian / Ubuntu ?

```
cd /tmp
git clone https://github.com/hqro/XKB-French-QWERTY-Keyboard-Layout .
sudo cp /usr/share/X11/xkb/symbols/us /usr/share/X11/xkb/symbols/us.qwerty-fr
cat us_qwerty-fr | sudo tee -a /usr/share/X11/xkb/symbols/us_qwerty-fr
```

### How to install on Debian / Ubuntu ?

```
setxkbmap us qwerty-fr
sudo service keyboard-setup restart
```

### How to use on Mac OS X ?

```
cd /tmp
git clone https://github.com/hqro/XKB-French-QWERTY-Keyboard-Layout .
cp -R ./MACOS/qwerty-fr.bundle ~/Library/Keyboard Layouts/
```

### How to use on Windows ?

 - Download [this zipped archive](http://marin.jb.free.fr/qwerty-fr/win-qwerty-fr.zip)
 - Extract it and run **setup.exe**
