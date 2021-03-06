![logo](logo.png)

> Throughout the ages, society has aimed to eliminate the mouse from daily computing one step at a time, first there was vim for text editing, then there was vimium for browsers, and now, the final solution to removing that mouse once and for all: introducing MouseRemoval!

linux version now available with the [pynput branch](https://github.com/peipacut/MouseRemoval/tree/pynput)! more information is provided on the branch's readme

## Dependencies
Ensure you have the following to run MouseRemoval
- Python 
- [Keyboard](https://pypi.org/project/keyboard/)
- [Mouse](https://pypi.org/project/mouse/)

The other two packages can be installed using pip

## Use
Just run it through the command line, make sure you're in the same directory as the file
```
python3 MouseRemoval.py
```

Sometimes just double clicking the python file works too. 

Pressing <kbd>alt</kbd>+<kbd>f4</kbd> should terminate the program (it very rarely fails!)

### Configuration
You can change the keybinds and available speeds by editing the config file in the project root. Make sure this file is in the same folder as the python file.
Most of it is pretty straightforward, you can also use `#` to start a comment

MouseRemoval uses vim style keybinds for movement, to use the arrow keys add this to your config
```
left : left
right : right
up : up
down : down 
```

### Missing features
- Custom speed management

## Disclaimer
This is a program that literally manipulates your mouse and blocks keyboard input. MouseRemoval isn't designed to be malicious but sometimes shit can hit the fan when you're not looking. I take no responsibility for any damages caused by this program.
