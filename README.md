# **Kozy Theme** 🪴 <br /> Light theme is here!!

[![Version](https://img.shields.io/badge/VSCODE-V1.12%2B-normal?style=flat)](https://code.visualstudio.com/updates/v1_12) [![Author](https://vsmarketplacebadge.apphb.com/version/Artezio.kozy-theme.svg)](https://github.com/Artezi0/Kozy)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/Artezio.kozy-theme?color=normal&label=DOWNLOADS)](https://marketplace.visualstudio.com/items?itemName=Artezio.kozy-theme)

Inspire by the Solarized theme, made this Visual Studio Code color theme extension that will make your editing window look cozy. I've made 3 variants right now and I'll keep expanding it

**Note** that I haven't fully tested this extension on all available languages. But I will keep updating it if needed. If threre is a problem please let me know.<br>

<br />

# **Installation**

1. Open the **Extensions** sidebar in VS Code. `View → Extensions`
2. Search for `Kozy Theme`, choose "Kozy Theme" by **Artezio**
3. Click **Install** to install it
4. Navigate to File > Preferences > Color Theme > **Kozy** (or any of the variants listed)

<br />

# **Screenshot**
### Kozy Theme
![Screenshot](images/kozy%20(1).svg)

### Kozy Darker Theme
![Screenshot](images/kozy%20(3).svg)

### Kozy Light Theme
![Screenshot](images/kozy%20(2).svg)

Display font using [JetBrains Nerd Font](https://www.nerdfonts.com/) and file icons using [City of Light Icons](https://github.com/Yummygum/city-lights-icons-vsc). 

<br />

# **Tweaks**

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

<br />

<!-- # **Color Pallete**
#### For Kozy theme and Kozy darker theme
| Color&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Hex |
| ---------- | ------------------------------------------------------------ | 
| ![#2F3E47](https://via.placeholder.com/15/2F3E47/2F3E47?text=+) `#2F3E47` | Charcoal |
| ![#263138](https://via.placeholder.com/15/263138/263138?text=+) `#263138` | Gunmetal |
| ![#1A242A](https://via.placeholder.com/15/1A242A/1A242A?text=+) `#1A242A` | Charleston Gree |
| ![#182026](https://via.placeholder.com/15/182026/182026?text=+) `#182026` | Eerie Black |
| ![#DBE4FF](https://via.placeholder.com/15/DBE4FF/DBE4FF?text=+) `#DBE4FF` | Lavender Web |
| ![#EAEDF6](https://via.placeholder.com/15/EAEDF6/EAEDF6?text=+) `#EAEDF6` | Ghost White |
| ![#B6B3AE](https://via.placeholder.com/15/B6B3AE/B6B3AE?text=+) `#B6B3AE` | Silver Chalice |
| ![#63A0B5](https://via.placeholder.com/15/63A0B5/63A0B5?text=+) `#63A0B5` | Maximum Blue |
| ![#69B1B4](https://via.placeholder.com/15/69B1B4/69B1B4?text=+) `#69B1B4` | Blue Jeans |
| ![#7A7FDB](https://via.placeholder.com/15/7A7FDB/7A7FDB?text=+) `#7A7FDB` | Violet Blue Crayol |
| ![#A4A6CB](https://via.placeholder.com/15/A4A6CB/A4A6CB?text=+) `#A4A6CB` | Blue Bell |
| ![#F09971](https://via.placeholder.com/15/F09971/F09971?text=+) `#F09971` | Light Salmon |
| ![#EE6D6D](https://via.placeholder.com/15/EE6D6D/EE6D6D?text=+) `#EE6D6D` | Fuzzy Wuzzy |
| ![#E6422D](https://via.placeholder.com/15/E6422D/E6422D?text=+) `#E6422D` | Cinnabar |
| ![#F0743A](https://via.placeholder.com/15/F0743A/F0743A?text=+) `#F0743A` | Mandarin |
| ![#E6A631](https://via.placeholder.com/15/E6A631/E6A631?text=+) `#E6A631` | Honey Yellow |
| ![#C2A83E](https://via.placeholder.com/15/C2A83E/C2A83E?text=+) `#C2A83E` | Metalic Gold |
| ![#A5B034](https://via.placeholder.com/15/A5B034/A5B034?text=+) `#A5B034` | Straw |
| ![#39A960](https://via.placeholder.com/15/39A960/39A960?text=+) `#39A960` | Go Green |

<br />

#### For Kozy Lighter theme
| Color&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Hex |
| ---------- | ------------------------------------------------------------ | 
| ![#FDFAE4](https://via.placeholder.com/15/FDFAE4/FDFAE4?text=+) `#FDFAE4` | Beige |
| ![#F7EDD2](https://via.placeholder.com/15/F7EDD2/F7EDD2?text=+) `#F7EDD2` |Cornsilk |
| ![#EAD9B9](https://via.placeholder.com/15/EAD9B9/EAD9B9?text=+) `#EAD9B9` | Dutch White |
| ![#CBBA9A](https://via.placeholder.com/15/CBBA9A/CBBA9A?text=+) `#CBBA9A` | Khaki Web |
| ![#5F6A79](https://via.placeholder.com/15/5F6A79/5F6A79?text=+) `#5F6A79` | Black Coral |
| ![#394956](https://via.placeholder.com/15/394956/394956?text=+) `#394956` | Charcoal |
| ![#B16286](https://via.placeholder.com/15/B16286/B16286?text=+) `#B16286` | Mulberry |
| ![#F57D7D](https://via.placeholder.com/15/F57D7D/F57D7D?text=+) `#F57D7D` | Light Coral |
| ![#F1563A](https://via.placeholder.com/15/F1563A/F1563A?text=+) `#F1563A` | Orange Soda |
| ![#F0743A](https://via.placeholder.com/15/F0743A/F0743A?text=+) `#F0743A` | Mandarin |
| ![#F9C74F](https://via.placeholder.com/15/F9C74F/F9C74F?text=+) `#F9C74F` | Maize Crayola |
| ![#C2A83E](https://via.placeholder.com/15/C2A83E/C2A83E?text=+) `#C2A83E` | Metallic Gold |
| ![#98971A](https://via.placeholder.com/15/98971A/98971A?text=+) `#98971A` | Citron |
| ![#689D6A](https://via.placeholder.com/15/689D6A/689D6A?text=+) `#689D6A` | Russian Green |
| ![#39A960](https://via.placeholder.com/15/39A960/39A960?text=+) `#39A960` | Go Green |
| ![#4CC977](https://via.placeholder.com/15/4CC977/4CC977?text=+) `#4CC977` | Emerald |
| ![#0B7974](https://via.placeholder.com/15/0B7974/0B7974?text=+) `#0B7974` | Pine Green |
| ![#48B1AB](https://via.placeholder.com/15/48B1AB/48B1AB?text=+) `#48B1AB` |  Verdigris |
| ![#55B6BB](https://via.placeholder.com/15/55B6BB/55B6BB?text=+) `#55B6BB` | Maximum Blue Crayola |
| ![#7A7FDB](https://via.placeholder.com/15/7A7FDB/7A7FDB?text=+) `#7A7FDB` | Violet Blue Crayola | -->

**Made By Artezio** <br /> Find me on 
[Instagram](https://instagram.com/artezio_),
[Twitter](https://twitter.com/Artezio0),
[Github](https://github.com/Artezi0)





