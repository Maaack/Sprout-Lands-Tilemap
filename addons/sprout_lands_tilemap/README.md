# Sprout Lands Tilemap
For Godot 4.3. Made in collaboration with [Cup Nooble](https://cupnooble.itch.io/).

[Example on itch.io](https://maaack.itch.io/harvest-hill-gwj-62-edition)  
![Example Screenshot](/addons/sprout_lands_tilemap/media/Example_Screenshot_1.png)  

## Use Case
Start building worlds with the free [Sprout Lands Asset Pack](https://cupnooble.itch.io/sprout-lands-asset-pack) right away.

## Requirements
1. Download and run [Godot](https://godotengine.org/).
2. Start a new project and have it open.
  
## Installation

### GitHub


1.  Download the latest release version from [GitHub](https://github.com/Maaack/Sprout-Lands-Tilemap/releases/latest).  
2.  Extract the contents of the archive.
3.  Move the `addons/sprout_lands_tilemap` folder into your project's `addons/` folder.  
4.  Open/Reload the project.  
5.  Enable the plugin from the Project Settings > Plugins tab.  
    If it's enabled for the first time,
    1.  A dialogue window will appear asking to copy the example scenes out of `addons/`.

## Usage

The example scene can be opened and worked in directly. If you'd rather start from scratch, here are the instructions.

1. Start a new scene with a Node2D.  
![Clicking on 2D Scene](/addons/sprout_lands_tilemap/media/Usage_Screenshot_1.png)
2. Instantiate a custom scene as a node.  
![Instatiate a Custom Scene](/addons/sprout_lands_tilemap/media/Usage_Screenshot_2.png)
3. Locate `SproutLandsTileMap.tscn` and open it. 
![Open Custom Scene](/addons/sprout_lands_tilemap/media/Usage_Screenshot_4.png)
4. Confirm the new node is added and selected in the scene tree.
![Confirm new node](/addons/sprout_lands_tilemap/media/Usage_Screenshot_5.png)
5. Open the TileMap editor, (if it is not open already).  
![Selecting TileMap Editor](/addons/sprout_lands_tilemap/media/Usage_Screenshot_6.png)
6. Select to draw terrains.  
![Selecting to draw terrains](/addons/sprout_lands_tilemap/media/Usage_Screenshot_7.png)
7. Select a terrain to draw (ex. Grass)  
![Selecting Grass Terrain](/addons/sprout_lands_tilemap/media/Usage_Screenshot_8.png)
8. Draw the terrain (ex. Grass) in the scene view.  
![Drawing Grass](/addons/sprout_lands_tilemap/media/Usage_Screenshot_9.png)

### Intermediate Usage

You may noticed that only one kind of tile can occupy any given space, while some tiles have transparency and should be placed over others. For this, there are layers that can be changed in the TileMap editor.  
![Changing TileMap Layers](/addons/sprout_lands_tilemap/media/Usage_Screenshot_10.png)  
The names are merely for convenience and do not enforce any rules themselves.

## Links
[Attribution](/addons/sprout_lands_tilemap/ATTRIBUTION.md)  
[Code License](/addons/sprout_lands_tilemap/LICENSE.txt)  
