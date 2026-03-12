Andrés Botero
=============

I’m a software and game developer with diverse experience and interested in low level engine programming.

Check the engine I'm working on: https://github.com/botero-dev/sdl-odin-boilerplate


A. Work Experience:
-------------------

### Current: Senior Embedded Enginer at Qubika
I work with a Qubika partner in the customer diagnostics team. We develop a suite of tools to test and benchmark custom hardware through the stages of development of the product.


### 1. Battle Road, 2022-2025:

We’re making a 3D globe scale game board for wargaming. This project is being developed on top of Godot Engine. I implemented the system for drawing a 3D globe that loads tiles from different data sources at different LODs, and puts all of this together into a beautifully rendered 3D globe. I also worked on some other tools related to 3D polygon drawing, OpenStreetMap buildings rendering, and loading vector data from GeoServer to Godot’s navmesh system.

- https://www.youtube.com/watch?v=N215eneOTN8


### 2. Halfwit Heroes, Almighty Idiots at Pump Action Games, 2020-2022:

Led the game development from prototyping phase to late production. I did the implementation of early systems, like 3D movement and behavior tree AI. Also implemented progression and tutorial systems, save games and back end connection. Unfortunately the game was canceled by the publisher.

- https://www.youtube.com/watch?v=RVSA4TGc7fw&t=157s
- https://www.youtube.com/watch?v=SZOb6B0kMA8&t=297s

### 3. Orbit Outlaws at Innovations Media, 2018-2019 :

I led the project from a small limited experience to a dynamic experience with different game modes, vehicle configurations, multiplayer support, while improving performance and making systems simpler and extensible.

- https://www.youtube.com/watch?v=YU-JoHlD3X4


### 4. Quantum Replica at On3D Studios, 2016-2017:

I supported the development of game development, implemented some of the movement system, minigames, UI and mission system. I also did a bit of engine development for porting to consoles and improving loading screen animations and handling per-platform button icons.

- https://www.youtube.com/watch?v=G1kT2wGcXWg

### 5. Older Flash projects:
I did multiple experiences in Flash that I don’t have links to show, but mainly consist on:
- AR projects in Flash with FLARToolkit
- A mobile project in Flash with Adobe AIR


B. Personal Projects:
---------------------

### SDL+Odin Cross Platform Engine: https://github.com/botero-dev/sdl-odin-boilerplate

Following my personal interest on graphics development and low level engineering. I was compelled to write an engine from scratch using Odin language and SDL low level library.

Here, I'm implementing every building block to make an engine. For now I'm implementing a 2D engine with input handling, UI navigation, asset loading, etc. This engine is also aimed at multi platform development, as SDL allows publishing to PC, mobile, TV and web devices with a single codebase.


### 1. Game: BoliFrog, 2022, in development, Godot. https://instagram.com/bolifrog

BoliFrog is a new take on traditional colombian game Bolirana. It plays similar to american game Skeeball, but our version of bolirana has score tracking with new rulesets, ability to choose characters and play different gamemodes in teams or free for all.

BoliFrog connects to the arcade machine hardware, it detects the player's scored balls, and other physical buttons to configure the game mode. It also connects to a RBG LED strip to give feedback to the player beyond the game screen.


### 2. Game: SkyForce, 2023, in development, Godot.

Skyforce is a prototype for a RC drone and airplane simulator. We intend to make it a platform that serves many players. Starting from intruducing and training pilots that are just getting in the field, up to collectors that would like to have their digital collection of beautifully crafted models, and also for competitive players that want to put their skills to test with other players.


### 3. Game: Rootarium, for GGJ2023, Godot. https://kichex.itch.io/rootarium

Rootarium is a cozy 2D pixel art game made for Global Game Jam 2023. The jam theme was “Roots”


### 4. Game: Saphi y el llamado de la tierra, 2023. Unity. https://saphiland.itch.io/saphi-y-el-llamado-de-la-tierra 

Saphi and the Call of Nature is a game about exploring agricultural heritage in Colombia. You play as a capybara, Saphi, to find the ways of the extinct human race for growing food and working in community to get to peace and abundance. This game applied for government funding in Colombia,

### 5. Game: BoomTown, for Gamedev Colombia Jam 2020. Godot. https://kichex.itch.io/boomtown 

Boomtown is a 3D game made in Godot for a game jam. The theme for the jam was “Chain Reaction”


### 6. Plugin: Blender Datasmith Exporter, 2020, Blender, Python: https://0xafbf.gumroad.com/l/blender-datasmith-content

Datasmith Blender Exporter is a plugin that lets you export full scenes from Blender to Unreal Engine using Datasmith format. This exporter lets you transfer full scenes, including scene hierarchy, instanced static meshes, textures and materials with complex node setups, and meshes with modifiers.


### 7. App: AB Launcher. in development. 2023. Godot.

Interface that lets you launch games and see information for many games in a database. This is part of a large project that intends to showcase many games made in Colombia.


### 8. Tools: AB Tools. 2023. Bash and Powershell.

Series of tools made to automate repetitive tasks around game development and publishing. Simplifies the handling of project versioning and engine version management when building games in Unity and Godot.


### 9. App: Bemote, iOS, Windows, Mac 2012: https://www.youtube.com/watch?v=FtamROcbz6o

This was a iOS application that allowed you to control a computer’s volume level. It used Bonjour (mDNS + DNS-SD) to discover computers in the same network. It required a separate helper app. It was done with native development for the platforms it was available (Objective-C for iOS app and Mac helper, C# for Windows)



C. Godot Engine Contributions:
------------------------------

https://github.com/godotengine/godot/pulls?q=is%3Apr+author%3A0xafbf


D. Experiments:
---------------

- I once tried to implement a 3D engine from scratch with Vulkan and GLFW. I got to the point of loading textures and OBJ models.
- I migrated this engine from C++ to Odin language, additionally implemented font loading and basic UI rendering in Odin. https://github.com/0xafbf/abengine
- I once implemented a IMGUI system on top of Godot 3: https://github.com/0xafbf/godot-imgui
- I have implemented python scrapers to download music files from websites
- Some time ago I implemented a python script to batch download satellite images from colombian mapping provider.
- I have solved close to 50 problems of Project Euler in python

