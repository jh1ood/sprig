:octopus: Sprig is a yet another rig control program for ICOM IC-7410.

:octopus: http://spinorlab.wordpress.com/ic-7410-rig-control/
```
% gcc -Wall -std=c99 main.c -o sprig -I/usr/include/alsa -lm -lasound -lfftw3 `pkg-config --cflags --libs gtk+-2.0`
```
![click_ani.gif](https://raw.github.com/wiki/jh1ood/sprig/img/click_ani.gif)
