cmatrix
=======

![cmatrix Termimal Effect](https://raw.githubusercontent.com/levithomason/cmatrix/master/screenshot.jpg)

The original Matrix screen saver effect for your Mac terminal.

# Install
Download the [cmatrix binary](https://github.com/levithomason/cmatrix/blob/master/cmatrix) and add it to your path.


# Usage
This is a direct port of the original obtained from MacPorts.  Original docs:

**Options:**  
```
-a: Asynchronous scroll, more like the movie/original screensaver 
-b: Partial bold text mode 
-B: All bold text mode 
-f: Force the linux $TERM type to on 
-l: Linux support for linux console matrix.fnt font 
-n: No bold text mode 
-o: Use "old-style" scrolling - less like the movie, more like the Win/Mac screensaver. 
-s: "Screen saver" mode.  Any key aborts (default is "eye candy" mode, must abort with control C) 
-x: X window mode, use if your xterm is using mtx.pcf 
-u [update]: Update delay (0-9, default 4). 
-C [color]: Use color for matrix (default green).
```

**Keystrokes available while running (not available in -s mode):**  
```
a: Toggle asynch mode 
b: Enable partial bold text 
B: Enable all bold text 
n: Disable bold text 
0-9: Change update delay
! @ # $ % ^ & ): Change the color of the matrix to the corresponding color:
    ! - red
    @ - green
    # - yellow
    $ - blue
    % - magenta
    ^ - cyan
    & - white
    ) - black
```

# Credit
This is a direct port from Chris Allegretta's original [cmatrix](http://www.asty.org/cmatrix/).

# Limitations
The original Linux font options and type face do not work on Mac.
