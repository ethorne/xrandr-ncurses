# Xrandr-ncurses
Easily manage your screens with i3

<img src="img/screen.png" alt="drawing" width="600"/>

NOTE: I forked this from [here](https://github.com/ldevillez/xrandr-ncurses?files=1)

## dependency
* ncurses

## What does it do ?
* Choose the screens that you want to use
* reloads the background

## Installation
* `make build` (optional)
* Add in your I3 config
```
  bindsym $mod+shift+m exec \
    gnome-terminal --geometry=78x24 --class=window_licker -x sh -c\
    'exec /home/erik/Repositories/xrandr-ncurses/xrandr-ncurses-app'
```

## TODO
Increase extensibility so that anyone can use this with just a bit of configuration.

Enjoy !
