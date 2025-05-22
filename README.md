# Gopher Night Theme

A clean and minimalistic VS Code theme inspired by Go's mascot 🥏

![Theme Preview](/images/theme-preview.png)

## Features

- Soft, eye-friendly color palette
- Optimized for readability
- Special attention to Go syntax highlighting

## Installation

1. Open VS Code Marketplace
2. Search for "gopher-night-theme"
3. Press install

## Customization

If you want a minimalistic view of VS Code like in the above image, add these to `settings.json`:

```json
    "workbench.colorTheme": "Gopher Theme",
    "workbench.editor.wrapTabs": true,
    "window.density.editorTabHeight": "compact",
    "editor.minimap.enabled": false,
    "editor.lineHeight": 1.4,
    "workbench.statusBar.visible": false,
    "workbench.tree.enableStickyScroll": false,
    "workbench.activityBar.location": "bottom",
    "breadcrumbs.enabled": false,
    "editor.wordWrap": "on",
    "editor.stickyScroll.scrollWithEditor": false,
    "editor.stickyScroll.enabled": false,
    "editor.lightbulb.enabled": "off",

    // vim settings
    "vim.smartRelativeLine": true,
    "vim.leader": "<space>",
    "vim.highlightedyank.enable": true,
    "vim.useSystemClipboard": true,
    "vim.highlightedyank.color": "#4dabf7af",
    "vim.highlightedyank.duration": 150,

```

You can customize this theme in your `settings.json`:

### **Change Key Repeat Settings**

To set a **faster** key repeat rate beyond the limit follow these instructions.

**Note** After setting these settings, restart your device (Configs are for mac users).

```
defaults write -g KeyRepeat -int 1
defaults write -g InitialKeyRepeat -int 10
```

If you want to restore the **default** settings, use:

```
defaults delete -g KeyRepeat
defaults delete -g InitialKeyRepeat
```

## Feedback

- [Report Issues](https://github.com/yourusername/gopher-minimal/issues)
- [Request Features](https://github.com/yourusername/gopher-minimal/issues)

**Happy Coding with Gopher Minimal! 🥏**
