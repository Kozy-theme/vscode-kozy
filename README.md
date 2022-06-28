<!-- Cover -->

<div align='center'> 
<img src='https://i.ibb.co/C7yWm5x/Icon.png' alt='logo'>
<br>

# Kozy Theme 🌱

[![Version](https://img.shields.io/badge/VSCODE-V1.12%2B-normal?style=flat)](https://code.visualstudio.com/updates/v1_12) [![Author](https://vsmarketplacebadge.apphb.com/version/Artezio.kozy-theme.svg)](https://github.com/Artezi0/Kozy)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/Artezio.kozy-theme?color=orange&label=Downloads)](https://marketplace.visualstudio.com/items?itemName=Artezio.kozy-theme)
</div>

<br>

<div align='justify'>
Inspired by the Solarized theme, made this Visual Studio Code color theme extension that will make your editing window look cozy. I've made 3 variants right now and I'll keep expanding it.

<br>
<br>

**Note** that I haven't fully tested this extension on all available languages. But I will keep updating it if needed. If threre is a problem please let me know.
</div>

## Installation

1. Open the **Extensions** sidebar in VS Code. `View → Extensions`
2. Search for `Kozy Theme`, choose "Kozy Theme" by **Artezio**
3. Click **Install** to install it
4. Navigate to File > Preferences > Color Theme > **Kozy** (or any of the variants listed)

## Screenshot
### Kozy Theme
![Screenshot](images/Screenshot%20(1).png)

### Kozy Darker Theme
![Screenshot](images/Screenshot%20(2).png)

### Kozy Light Theme
![Screenshot](images/Screenshot%20(3).png)

Display font using [JetBrains Nerd Font](https://www.nerdfonts.com/) and file icons using [City of Light Icons](https://github.com/Yummygum/city-lights-icons-vsc). 

## Tweaks

If you want to play around with new colors, use the setting `workbench.colorCustomizations` to customize the currently selected theme. For example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#ffff",
  "activityBar.background": "#ffff",
  "sideBar.background": "#ffff",
  "tab.activeBorder": "#ffff",
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations": {
    {
        "name": "Comment",
        "scope": "comment",
        "settings": {
            "foreground": "#2F3E47",
		    "fontStyle": "italic"
        }
    }
}
```

<br >

**Made By Artezio** <br /> Find me on 
[Instagram](https://instagram.com/artezio_),
[Twitter](https://twitter.com/Artezio0),
[Github](https://github.com/Artezi0)





