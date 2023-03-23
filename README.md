# swolemak
A Swedish Colemak DH layout for the /usr/share/X11/xkb/symbols/se file. 

```
1 2 3 4 5 6 7 8 9 0 + '
 q w f p b j l u y ö å ~
  a r s t g m n e i o ä '
 z x c d v < k h , . -
 ```

If installed manually, the layout variant needs to be added to /usr/share/X11/xkb/rules/evdev.xml.

To install using the script: 

    WARNING: Running this multiple times will probably cause problems. And please backup your files before you do.

```
wget https://raw.githubusercontent.com/hedeben/swolemak/main/swolemak.sh
sudo sh ./swolemak.sh
```
