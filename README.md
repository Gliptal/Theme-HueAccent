HueAccent
======

A minimal Sublime Text theme, based on a single color shared by all interfaces elements. The theme is based on the following rules:

- Full white (255,255,255) is used for selected details, such as strings and icons.
- Theme color is used for selected UI elements, such as tabs and rows.
- Gray is used for non selected details.
- Slightly darker or lighter versions of the theme color are used where needed.

Available colors right now are:

- Blue
- Green
- Water
- Yellow

Check the Bug and Requests section of this README if you'd like more colors added, or feel free to edit my theme and add them yourself (check the Editing section).

Installing
======

1. If you haven't done already, install [Package Control](https://sublime.wbond.net/installation).
2. Look for "Theme - HueAccent" in the available packages list and install it (CTRL-SHIFT-P > Package Control: Install Package).
3. Edit you Preferences.sublime-settings file (Preferences > Settings - User) adding:
  - `"theme": "HueAccentBlue.sublime-theme",` for Blue color.
  - `"theme": "HueAccentGreen.sublime-theme",` for Green color.
  - `"theme": "HueAccentWater.sublime-theme",` for Water color.
  - `"theme": "HueAccentYellow.sublime-theme",` for Yellow color.
4. Restart Sublime Text

Images
======

- Blue

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/Blue.png)

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/BluePCK.png)

- Green

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/Green.png)

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/GreenPCK.png)

- Water

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/Water.png)

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/WaterPCK.png)

- Yellow

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/Yellow.png)

![](https://raw.githubusercontent.com/Gliptal/Theme-HueAccent/master/images/YellowPCK.png)


Editing
======

Editing the theme is fairly simple:

1. Reach `Theme - HueAccent.sublime-package` inside your Sublime Text `/Installed Packages`. Inside `/themes` copy one of the .sublime-theme files and rename it.
2. Download and install [Package Resource Viewer](https://github.com/skuroda/PackageResourceViewer) using Package Control.
3. Using said plugin, find and edit the .sublime-theme file you previously created.
4. Remember to change your "theme" entry in your preferences to your new .sublime-theme file name.

The `accents` file in the `\settings` directory is also a good reference containing the colors used for each version of the theme.

Bugs and Requests
======

You can submit bugs and requests using the [Issues](https://github.com/Gliptal/Theme-HueAccent/issues) section of this Theme's GitHub. If for any reason you are unable to use that resource, you can find me on Twitter @MattiaAffabris. If not even Twitter is an option, e-mail me at affa [at] outlook [dot] it.

If you like this theme and decide to use it, please let me know using any of the above methods.

Credits
======

Credits go to Allan Hortle and his excellent Centurion Theme you can find here: [Centurion](https://github.com/allanhortle/Centurion). HueAccent is a modified version of his theme.


