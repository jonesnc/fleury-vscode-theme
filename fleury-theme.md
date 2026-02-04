# Fleury Theme Color Summary

## UI Elements
- **Bar**: `#000000` - Black
- **Base**: `#fcaa05` - Orange-yellow
- **Pop1**: `#de8150` - Light orange
- **Pop2**: `#FF0000` - Red
- **Background**: `#020202` - Near black
- **Margin**: `#222425` - Dark gray
- **Margin Hover**: `#63523d` - Brown
- **Margin Active**: `#63523d` - Brown

## List Items (alternating colors)
- **List Item**: `#222425`, `#020202` - Dark gray / near black alternating
- **List Item Hover**: `#362e25`, `#222425` - Brown / dark gray alternating
- **List Item Active**: `#63523d`, `#222425` - Brown / dark gray

## Cursor & Selection
- **Cursor**: `#00EE00`, `#e0741b`, `#1be094`, `#ba60c4` - Green / orange / teal / purple (multi-cursor)
- **At Cursor**: `#0C0C0C` - Very dark gray
- **Highlight Cursor Line**: `#1E1E1E` - Subtle dark gray
- **Highlight**: `#303040` - Dark blue-gray
- **At Highlight**: `#FF44DD` - Bright pink
- **Mark**: `#494949` - Gray

## Syntax Highlighting
- **Text Default**: `#b99468` - Tan/beige
- **Comment**: `#666666` - Gray
- **Comment Pop**: `#2ab34f`, `#db2828` - Green / red (alternating)
- **Keyword**: `#f0c674` - Yellow-orange
- **String Constant**: `#ffa900` - Bright orange
- **Char Constant**: `#ffa900` - Bright orange
- **Int Constant**: `#ffa900` - Bright orange
- **Float Constant**: `#ffa900` - Bright orange
- **Bool Constant**: `#ffa900` - Bright orange
- **Preprocessor**: `#dc7575` - Pink-red
- **Include**: `#ffa900` - Bright orange

## Special Elements
- **Special Character**: `#FF0000` - Red
- **Ghost Character**: `#4E5E46` - Dark green-gray
- **Highlight Junk**: `#3A0000` - Dark red
- **Highlight White**: `#003A3A` - Dark cyan
- **Paste**: `#DDEE00` - Yellow
- **Undo**: `#00DDEE` - Cyan

## Cycling Colors (for multi-selections)
- **Background Cycle**: 11 shades from `#020202` to `#700202` - Black to dark red gradient
- **Text Cycle**: `#A00000`, `#00A000`, `#0030B0`, `#A0A000` - Red/green/blue/yellow

## Line Numbers
- **Line Numbers Background**: `#101010` - Very dark gray
- **Line Numbers Text**: `#404040` - Dark gray

## Fleury-Specific Colors
- **Syntax Crap**: `#6e5d4a` - Dark brown (punctuation) - *Modified from original `#5c4d3c` for better contrast*
- **Operators**: `#bd2d2d` - Red
- **Inactive Pane Overlay**: `#44000000` - Transparent black
- **Inactive Pane Background**: `#000000` - Black
- **File Progress Bar**: `#60634323` - Transparent brown
- **Brace Highlight**: `#8ffff2` - Light cyan
- **Brace Line**: `#809ba290` - Transparent gray-green
- **Brace Annotation**: `#809ba290` - Transparent gray-green
- **Index Product Type**: `#edb211` - Gold
- **Index Sum Type**: `#a7eb13` - Yellow-green
- **Index Function**: `#de451f` - Orange-red
- **Index Macro**: `#2895c7` - Blue
- **Index Constant**: `#6eb535` - Green
- **Index Comment Tag**: `#ffae00` - Orange
- **Index Decl**: `#c9598a` - Pink
- **Cursor Macro**: `#de2368` - Pink-red
- **Cursor Power Mode**: `#efaf2f` - Gold
- **Cursor Inactive**: `#880000` - Dark red
- **Plot Cycle**: `#03d3fc`, `#22b80b`, `#f0bb0c`, `#f0500c` - Cyan/green/yellow/red
- **Token Highlight**: `#88f2d357` - Transparent yellow-green
- **Token Minor Highlight**: `#44d19045` - Transparent green
- **Error Annotation**: `#ff0000` - Red
- **Lego Grab**: `#efaf6f` - Light orange
- **Lego Splat**: `#efaaef` - Light purple
- **Comment User Name**: `#ffdd23` - Yellow

## Notes
- Color format is RGB hex (e.g., `#RRGGBB`)
- Theme implementation files:
  - `ship_files/themes/theme-fleury.4coder` - Fleury theme definition
  - `custom/4coder_default_colors.cpp` - Theme system implementation
  - `custom/4coder_default_colors.h` - Color slot ID declarations