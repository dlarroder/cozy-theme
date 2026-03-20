# Cozy Theme

A warm, cozy dark theme for VS Code that's easy on the eyes during long coding sessions.

## Preview

![Cozy Theme Preview](./preview.png)

## Color Palette

| Role        | Color | Hex       |
| ----------- | ----- | --------- |
| Background  | ![Background](https://img.shields.io/badge/-%20%20%20%20%20-110c17?style=flat-square&labelColor=110c17) | `#110c17` |
| Foreground  | ![Foreground](https://img.shields.io/badge/-%20%20%20%20%20-d4c5b9?style=flat-square&labelColor=d4c5b9) | `#d4c5b9` |
| Accent      | ![Accent](https://img.shields.io/badge/-%20%20%20%20%20-e8a87c?style=flat-square&labelColor=e8a87c) | `#e8a87c` |
| Keywords    | ![Keywords](https://img.shields.io/badge/-%20%20%20%20%20-c491cf?style=flat-square&labelColor=c491cf) | `#c491cf` |
| Functions   | ![Functions](https://img.shields.io/badge/-%20%20%20%20%20-82b8cc?style=flat-square&labelColor=82b8cc) | `#82b8cc` |
| Strings     | ![Strings](https://img.shields.io/badge/-%20%20%20%20%20-c49a8a?style=flat-square&labelColor=c49a8a) | `#c49a8a` |
| Constants   | ![Constants](https://img.shields.io/badge/-%20%20%20%20%20-d4a055?style=flat-square&labelColor=d4a055) | `#d4a055` |
| Tags        | ![Tags](https://img.shields.io/badge/-%20%20%20%20%20-e8a87c?style=flat-square&labelColor=e8a87c) | `#e8a87c` |
| Components  | ![Components](https://img.shields.io/badge/-%20%20%20%20%20-d480b8?style=flat-square&labelColor=d480b8) | `#d480b8` |
| Regex/Cyan  | ![Regex](https://img.shields.io/badge/-%20%20%20%20%20-6fbcb0?style=flat-square&labelColor=6fbcb0) | `#6fbcb0` |

## Installation

### From VS Code Marketplace

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for `Cozy Theme`
3. Click **Install**
4. Open **Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P`)
5. Select **Preferences: Color Theme** → **Cozy Theme**

### From Source

1. Clone this repository into your VS Code extensions directory:
   ```bash
   git clone https://github.com/dlarroder/cozy-theme ~/.vscode/extensions/cozy-theme
   ```
2. Restart VS Code
3. Select the theme via **Preferences: Color Theme** → **Cozy Theme**

## Development

1. Open this folder in VS Code
2. Press `F5` to launch a new VS Code window with the theme loaded
3. Edit `themes/cozy-color-theme.json` to tweak colors
4. Reload the development window (`Ctrl+R` / `Cmd+R`) to see changes

## Packaging & Publishing

```bash
bun install
bun run package    # creates a .vsix file
bun run publish    # publishes to VS Code Marketplace
```

## License

[MIT](./LICENSE)
