# Pong-with-C

A recreation of the classic **Pong** retro game from 1972, **developed in C**.<br/><br/>
The game features **smooth rendering of graphics using SDL3**, with **text displayed via SDL3_ttf** for additional customization. Players can adjust various aspects of the game, such as paddle size and ball velocity, by modifying simple constants in the code.<br/>
**The game runs seamlessly, offering a nostalgic experience with customizable elements for added replayability**.<br/>

# Libraries
* **SDL3**
* **SDL3_ttf**
<br/><br/>


# Compiling
```gcc -o pong pong.c -lm -lSDL3_ttf `pkg-config sld3 --cflags --libs` ```
