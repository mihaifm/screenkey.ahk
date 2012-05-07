## Screenkey.ahk

Screenkey.ahk is a tool that displays the keys that you type on the screen.
It can be useful for screencasts or remote help.

You can run it as an [Autohotkey]http://www.autohotkey.com/) script or run the compiled exe directly.

### Customization

There are a few customization options that can be tweaked at the top of the script:

Font settings:

    fontSize = 20
    fontName = Verdana
    fontStyle = Bold

Maximum number of keys that can be displayed on the screen at any time:

    numButtons := 5

Gui transparency:

    transparent := true

Distance from the buttons to the edge of the window
    
    winMargin := 25

Speed typing settings:

    useSpeedTimer := true
    speedTimer := 1000

When `useSpeedTimer` is true, previous keys will be cleared when typing new keys after the specified interval (`speedTimer`)
This is handy when trying to show key combos.


