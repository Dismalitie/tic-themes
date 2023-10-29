# tic-themes
Sprite and tile themes for TIC80

You can try these themes as a demo with the `demo.exe` file in each theme folder.

**Note: When you press the escape key to view the theme, you need to go to settings and enabled dev mode. Then press escape twice and navigate to the sprites tab.**

# How do I install TIC-80 themes?
To install a TIC-80 theme, follow these steps.

**1.** Download a theme's `config.tic` file.

**2.** Open TIC-80 and enter:
```cmd
folder
```

**3.** Create a new folder called "tic-themes" or download this repo.

**4.** Put your theme's `config.tic` file in the folder.

**5.** Go back to TIC-80 and enter:
```cmd
cd themes
```

**6.** Enter configuration mode by entering:
```cmd
config
```

**7.** Make note of the path that appears at the top of the screen (e.g `.local/be42d6f/config.tic`)

**8.** Make a backup of the default themes by running:
```cmd
save default
```
**9.** Close TIC-80.

**10.** Replace the default `config.tic` (located in the path you took note of earlier e.g `.local/be42d6f/config.tic`) file with your theme's `config.tic` file.

**11.** Run TIC-80!