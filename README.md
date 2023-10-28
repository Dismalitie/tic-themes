# tic80-themes
Sprite and tile themes for TIC80

You can try these themes as a demo with the `demo.exe` file in each theme folder.
**Note:** When you press the escape key to view the theme, you need to navigate to the "sprites" tab.

# How do I install TIC-80 themes?
To install a TIC-80 theme, follow these steps.

**1.** Download a theme's `sprites.tth` and `tiles.tth`.

**2.** Open TIC-80 and enter:
```cmd
folder
```

**3.** Create a new folder called "tic-themes" or download this repo.

**4.** Put your theme's `sprites.tth` and `tiles.tth` files in the folder.

**5.** Go back to TIC-80 and enter:
```cmd
cd themes
```

**6.** Enter configuration mode by entering:
```cmd
config
```

**6.5** It is advised that you create a backup of the default theme by doing:
```cmd
export sprites backup.sprites
```
```cmd
export tiles backup.tiles
```

**7.** Run the import commands for the spritesheet and tilemap (we're using the guilded theme as an example):
```cmd
import sprites guilded.sprites.tth
```
```cmd
import tiles guilded.tiles.tth
```

**8.** Run:
```cmd
edit
```

**9.** Press `ctrl+s` to apply and save!
# tic-themes
 
