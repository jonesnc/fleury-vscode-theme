# Fleury Theme for VSCode

A Visual Studio Code theme based on Ryan Fleury's 4coder color scheme, featuring warm orange-gold tones.

## Colors

| Element | Color |
|---------|-------|
| Background | `#020202` |
| Default text | `#b99468` (warm tan) |
| Comments | `#666666` (gray) |
| Keywords | `#f0c674` (pale yellow) |
| Strings/Constants | `#ffa900` (orange) |
| Functions | `#de451f` (orange-red) |
| Macros | `#2895c7` (blue) |
| Types | `#edb211` (gold) |
| Operators | `#bd2d2d` (red) |
| Preprocessor/Modules | `#dc7575` (coral) |
| Declarations | `#c9598a` (pink) |
| Punctuation | `#7a6b5a` (muted brown) |

## Installation

### Manual Installation

1. Copy the `fleury-vscode-theme` folder to your VSCode extensions directory:
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
   - **macOS/Linux:** `~/.vscode/extensions/`

2. Restart VSCode

3. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)

4. Type "Color Theme" and select "Preferences: Color Theme"

5. Select "Fleury Theme" from the list

### Building from Source

```bash
npm install -g vsce
cd ~/Projects/fleury-vscode-theme
vsce package
```

Install the generated `.vsix` file in VSCode.

## Reference

Original theme files preserved in `reference/`:
- `theme-fleury.4coder` - Ryan Fleury's 4coder theme (primary reference)
- `4coder_default_colors.cpp` - Original 4coder default colors
- `4coder_default_colors.h` - Color slot definitions

## License

Inspired by Ryan Fleury's 4coder theme.
