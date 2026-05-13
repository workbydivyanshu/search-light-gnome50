# Search Light

A GNOME Shell extension that provides Spotlight-like search functionality outside of the Overview.

### Credits

- **Original**: [icedman/search-light](https://github.com/icedman/search-light)
- **GNOME 50 support**: [ondrovic/search-light](https://github.com/ondrovic/search-light)
- **Fixes applied**: Import path correction (`resource:///org/gnome/shell/extensions/extension.js`) to resolve GNOME Shell crash on enable.

### Compatibility

- **GNOME Shell 50** and later

### Features

- Popup search box outside Overview
- Colors, background, and border customization
- Multi-monitor support
- Configurable keyboard shortcuts

### Installation

```bash
git clone https://github.com/workbydivyanshu/search-light-gnome50
cd search-light-gnome50
glib-compile-schemas schemas/
```

Then load as unpacked extension in GNOME Extensions app, or copy to `~/.local/share/gnome-shell/extensions/search-light@icedman.github.com/`.

### Keybindings

- Default: **Ctrl+Super+Space**
- Configure in extension preferences

### License

Same as original project (GPL-3.0).