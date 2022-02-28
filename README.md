![logo](logo.png)

if you're looking for the windows branch, [click here](https://github.com/peipacut/MouseRemoval/tree/main)

> Throughout the ages, society has aimed to eliminate the mouse from daily computing one step at a time, first there was vim for text editing, then there was vimium for browsers, and now, the final solution to removing that mouse once and for all: introducing MouseRemoval!

Now slightly more improved!

## Dependencies
Ensure you have the following to run MouseRemoval
- Python 
- [pynput](https://pypi.org/project/pynput/)

## Use
Just run it through the command line, make sure you're in the same directory as the file
```
python3 MouseRemoval.py
```
use <kbd>b</kbd> to terminate the program

### Configuration
Unlike its windows counterpart, pynput mouse removal does not use a config file. Your best bet is to edit the source directly. All keybinds are stored in the `DEFAULT_BINDS` dictionary.

### Limitations
- enabling mouse mode consumes *all* keyboard input. Things like alt dragging are now impossible
- pynput's input grabbing tends not to play well with other applications that grab input (like rofi or dmenu). A fix is currently being looked into.

## Disclaimer
This is a program that literally manipulates your mouse and blocks keyboard input. MouseRemoval isn't designed to be malicious but sometimes shit can hit the fan when you're not looking. I take no responsibility for any damages caused by this program.
