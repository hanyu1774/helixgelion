# nvimgelion-for-helix
A colorscheme for the Helix code editor using colors from Evangelion.
This is a direct port of the nvimgelion colorscheme by nyngwang for Neovim.
* See original repo: [nyngwang/nvimgelion](https://github.com/nyngwang/nvimgelion)

## Installation
### 1. Locate your Helix config directory
- **Windows**: `C:/Users/<username>/AppData/Roaming/helix`
- **Linux**: `home/<username>/.config/helix`
If the `/helix` folder doesn't exist, then create it.

### 2. Install the theme
1. Create a `themes` folder if it doesn't exist
2. Download `nvimgelion.toml` and place it in the `themes` folder
### 3. Enable the theme
**Permanent:**
- Edit or create `config.toml` in your Helix directory
- Add: `theme = "nvimgelion"`

**Temporary:**
- In Helix editor: `:theme nvimgelion`
- Or use `:theme` + `TAB` to browse available themes
