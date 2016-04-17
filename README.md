# Raspberry Pi easy drawing with c and cairo
- Provides a simple framework for basic drawing with cairo and gtk+ 3.0
- All gtk+ functions are hidden away in main.c
- No knowledge about gtk+ is required
- You can concentrate on writing your own cairo drawing in application.c

Just replace the simple example with your own code

- define your main window in application.h
- Code your cairo drawing in application.c
 
The framework provides functions

- to draw using cairo
- to initialize your code
- to exit your code
- a periodically called function (only executed if required)
- a function called if the mouse is clicked

Some nice examples of cairo snippets can be found at
  http://http://cairographics.org/samples/

To compile, you need to install gtk+ with the command

```
  sudo apt-get install libgtk-3-dev
```

Compile with

```
  make
```

Execute with

```
  ./application
```

Please help to improve this program by tweeting to
**http://twitter.com/r_richarz** or opening an issue on this repository
if you have any problem or suggestion.
  
