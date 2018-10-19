# iterm2-control

Script which can control appearance of iTerm2 from commandline

## Installation

Clone in to your home directory
    
    $ curl -s -o iterm2-control https://raw.githubusercontent.com/fondberg/iterm2-control/master/iterm2-control && chmod +x iterm2-control
    $ ./iterm-control -h
    
## Usage
    Usage: itermControl [options...]
    Options:
    -f, --foreground        Hex color of foreground in the format of FFFFFF
    -b, --background        Hex color of background in the format of FFFFFF
    -o  --opacity           Opcacity of the terminal 0.0 - 1.0
    -c, --tabcolor          Color of tab title in the format of a text color (red, blue, green, white, et.c)
    -t, --title             Title text of the terminal
    -d, --default           Use default values and set everything


## Default values

FG="ffeeff"
BG="003300"
OP="0.1"
TAB="green"
TXT="Special term"
SETCOLOR=0

## Contributors

[Niklas Fondberg](http://github.com/fondberg)

------------
Copyright (c) 2018 Niklas Fondberg <niklas.fondberg@gmail.com. All rights reserved.
