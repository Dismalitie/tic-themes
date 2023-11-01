# tic-themes
Sprite and tile themes for TIC80

**Note: When you press the escape key to view the theme, you need to go to settings and enabled dev mode. Then press escape twice and navigate to the sprites tab.**

# How do I install TIC-80 themes?
To install a TIC-80 theme, follow these instructions.

**1.** Download tic-tweaker.

**2.** Open TIC-80 and enter:
```cmd
folder
```

**3.** Create a new folder called "tic-themes" or download this repo.

**4.** Go to TIC-80 and run:
```cmd
config
```
**5.** Copy or mkae not of the path that is shown in the message (e.g ".local/be42d6f/config.tic").

**6.** Close TIC-80 and open tic-tweaker.

**7.** Select a theme from the dropdown list, and input the path you copied earlier (step 5) into the text box.

**8.** Press apply and "Yes" in the dialogue box.

**9.** Open TIC-80

**10.** Enjoy your theme!

# How do I make my own theme?
tic-tweaker automatically indexes themes located in the themes folder. There is just 2 requirements for it to work with tic-tweaker:
```ini
[+] [inf.dsc]
[+] [config.tic]
```
`*.tth` files aren't necesssary and are only there as a fallback or if you want to apply the themes manually.

**1.** Open TIC-80 and run:
```cmd
config
edit
```

**2.** Go to the sprites tab.

**3.** Customize the sprites with the editor as you please.

**4.** Save with `ctrl+s`.

**5.** Run:
```cmd
folder
```

**6.** Navigate to `tic-themes > themes` and create a new folder with the name you want. **IT MUST NOT CONTAIN SPACES OR SPECIAL CHARACTERS**

**7.** Create a new file called `inf.dsc` open it with notepad or any other text editor and write a short description.

**8.** Go back to TIC-80 and run:
```cmd
surf
```
**9.** Navigate to `tic-themes > themes > (name of your theme)` and press escape.

**10.** Run
```cmd
save config
```

tic-tweaker will now index your theme. If you make a theme, you can fork this repo and add it, then send a pull request.
