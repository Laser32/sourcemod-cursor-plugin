# SourceMod Professional - Cursor Extension

## 🚀 Installation

### Method 1: VSIX Installation (Recommended)
1. Download `sourcemod-professional-2.0.0.vsix`
2. Open Cursor
3. Press `Ctrl+Shift+P`
4. Type: `install from vsix`
5. Select the downloaded VSIX file
6. Restart Cursor

### Method 2: Manual Installation
1. Download and extract `sourcemod-professional-2.0.0.zip`
2. Navigate to: `%USERPROFILE%\.cursor\extensions\`
3. Create folder: `sourcemod-professional-2.0.0`
4. Copy all extracted files to this folder
5. Restart Cursor

## ✨ Features

- **Syntax Highlighting** for .sp and .inc files
- **Code Snippets** for common SourceMod patterns
- **Compiler Integration** with spcomp
- **Project Creator** for new plugins
- **Auto-completion** and bracket matching

## 📝 Available Snippets

- `plugin` - Complete plugin template
- `cmd` - Command handler
- `event` - Event hook
- `timer` - Timer function
- `menu` - Menu system

## ⚙️ Configuration

```json
{
  "sourcemod.compiler.path": "spcomp",
  "sourcemod.compiler.includePath": [],
  "sourcemod.autoCompile": false
}
```

## 🎯 Commands

- `SourceMod: Compile Plugin` - Compile current .sp file
- `SourceMod: Create New Project` - Generate new plugin structure

## 📁 Supported Files

- `.sp` - SourcePawn plugin files
- `.inc` - SourcePawn include files
- `.smx` - Compiled plugin files

## 🔧 Requirements

- Cursor/VSCode 1.82+
- SourceMod compiler (spcomp) for compilation

## 📄 License

MIT License - see LICENSE file for details

## 🤝 Support

For issues and feature requests, please visit our GitHub repository.

---

**Made with ❤️ for SourceMod developers**
