# Squid-Engine
### HTML5 Game Engine
[robdoesWEB.com](http://robdoesweb.com)

## Structure
+ game_core
 - game.js - Main game loop: each game will inherit this game loop and expand it and customize it
 - entity.js - Basic entity class, game loop updates all entities and renders them
 - config.js - each game will overwrite it's configuration file

### Overview

  Squid-Engine is a 2D game development system utilizing HTML5 Canvas, and Node.js with socket.io for real-time multiplayer.
