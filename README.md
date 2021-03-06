# Simple Snake Game with Python

After 4 years, I finally did the Snake game. Since I started programming (almost 4 years ago), I dreamed of doing this game, but I never did it.  
Now the game has 2 versions: Procedural programming version, and Object Oriented Programming version.

![demo](https://media.giphy.com/media/QfX2QFjuN2LfNGkWLa/giphy.gif)
---

## TO-DO list
**Code:**  
- [x]  Generic programming version
- [x]  Object Oriented Programming version
- [x] Add a settings.json to edit the settings of the game  
- [x] Comment the code



**Game stuff:**  
- [x] Collision with the borders of the window
- [x] Scores
- [x] Change the font  

## How to change game settings
In the folder, there is a file called `settings.json`. Inside of this file, there are settings that can be changed.
- `"scale" : 10` - This changes the scale of the whole game (the size of the grids).
- `"initial_snake_size" : 5` - This changes the initial snake size. How many squares you want the snake to begin with
- `"fruit_color" : [0, 255, 255]` - Set the color of the fruit. By default it is cyan, but you can change to any color in RGB
- `"snake_color" : [255, 255, 255]` - Changes the snake color
- `"frame_rate" : 15` - This changes the framerate of the game. the higher, the faster.
- `"song_path" : "./song2.wav"` - This is the place where you can change the song that is played. There is 2 songs in the main directory: `song.ogg` and `song2.wav`. `song.ogg` is a song from Super Mario Land and `song2.wav` is just a song that I found on the https://modarchive.org/ called "android - city of the night".
- `"screen_size" : 300` - This setting changes the width of the screen. Don't worry about the height because the game has an aspect ratio.
- `"collide_on_walls" : false"` - Change if the player will lose if it collides with the walls or not (this option is only available for the object oriented version yet)

## Controls
|Key  | command |
|--|--|
| ↑ | up |
| ↓ | down |
| ← | left |
| → | right |
| R | restart when dead |


### Extra info
Made with Python 3.6.9 64 bit on Linux  
Using Visual Studio Code  
Modules required:  
 - Pygame : `pip install pygame`
