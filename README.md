# Cozy Theme

A warm, cozy dark theme for VS Code that's easy on the eyes during long coding sessions.

## Preview

![Cozy Theme Preview](./preview.png)

## Color Palette

| Role        | Color                                                        | Hex       |
| ----------- | ------------------------------------------------------------ | --------- |
| Background  | ![#1a1521](https://place-hold.it/16/1a1521/1a1521) | `#1a1521` |
| Foreground  | ![#d4c5b9](https://place-hold.it/16/d4c5b9/d4c5b9) | `#d4c5b9` |
| Accent      | ![#e8a87c](https://place-hold.it/16/e8a87c/e8a87c) | `#e8a87c` |
| Keywords    | ![#c491cf](https://place-hold.it/16/c491cf/c491cf) | `#c491cf` |
| Functions   | ![#7ca8cf](https://place-hold.it/16/7ca8cf/7ca8cf) | `#7ca8cf` |
| Strings     | ![#8fbc6f](https://place-hold.it/16/8fbc6f/8fbc6f) | `#8fbc6f` |
| Constants   | ![#d4a055](https://place-hold.it/16/d4a055/d4a055) | `#d4a055` |
| Tags        | ![#c47070](https://place-hold.it/16/c47070/c47070) | `#c47070` |
| Regex/Cyan  | ![#6fbcb0](https://place-hold.it/16/6fbcb0/6fbcb0) | `#6fbcb0` |

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
   git clone https://github.com/dalelarroder/cozy-theme ~/.vscode/extensions/cozy-theme
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
npm install
npm run package    # creates a .vsix file
npm run publish    # publishes to VS Code Marketplace
```

## License

[MIT](./LICENSE)
