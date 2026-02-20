# Installation Guide

## Quick Install (VSIX)

1. **Download**: `sourcemod-professional-2.0.0.vsix` (8.77KB)
2. **Open Cursor**
3. **Press**: `Ctrl+Shift+P`
4. **Type**: `install from vsix`
5. **Select**: The downloaded VSIX file
6. **Restart** Cursor

## Manual Install

1. **Download**: `sourcemod-professional-2.0.0.zip`
2. **Extract** to temporary folder
3. **Navigate**: `%USERPROFILE%\.cursor\extensions\`
4. **Create**: `sourcemod-professional-2.0.0` folder
5. **Copy**: All extracted files
6. **Restart** Cursor

## Verification

After installation:
- Open a `.sp` file
- Type `plugin` and press Tab
- Right-click → "Compile SourceMod Plugin"

## Troubleshooting

**VSIX not working?**
- Use manual installation method
- Check Cursor version (requires 1.82+)
- Restart Cursor after installation

**Syntax highlighting not working?**
- Make sure file extension is `.sp` or `.inc`
- Check if extension is enabled in Extensions tab
- Try reopening the file

**Compiler not found?**
- Configure path in Settings → SourceMod
- Set `sourcemod.compiler.path` to your spcomp location
