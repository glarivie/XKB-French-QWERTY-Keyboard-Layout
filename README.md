# XKB-French-QWERTY-Keyboard-Layout
Work well on Ubuntu, Debian and CentOS, etc...

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

It's done !
