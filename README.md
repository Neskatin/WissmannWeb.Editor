# WissmannWeb Editor Essentials - Extension Pack for VS Code

[![Badge for version for Visual Studio Code extension Wissmann-Web.wissmannweb-editor](https://vsmarketplacebadge.apphb.com/version/Wissmann-Web.wissmannweb-editor.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/Wissmann-Web.wissmannweb-editor.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) [![Rating](https://vsmarketplacebadge.apphb.com/rating-star/Wissmann-Web.wissmannweb-editor.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Wissmann-Web.wissmannweb-editor) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)

This extension pack for Visual Studio Code adds extensions that are amazingly useful for development with VS Code.

See the [CHANGELOG](CHANGELOG.md) for the latest changes

> As tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

## Recommended Settings

Here are some of my recommended settings. These are optional, but I get asked a lot for them, so here they are.

### Editor settings

```json
  "workbench.colorTheme": "Default Light+",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.renderIndentGuides": false,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.minimap.enabled": false,
  "editor.renderWhitespace": "none",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "off",

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
```

### Prettier settings

```json
  "prettier.singleQuote": true,
  "prettier.printWidth": 140,
```

### Todo Tree settings

```json
  "todo-tree.filtering.excludeGlobs": [
    "**/node_modules/**",
    "**/dist*/**"
  ],
  "todo-tree.tree.flat": true,
```

## Included

Here is the list of extensions the pack includes:

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - VS Code plugin for prettier/prettier
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - AI-assisted development
- [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) - A extension for Visual Studio Code that assists you in working with .gitignore files.
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Visual Studio Code plugin that autocompletes npm modules in import statements
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) - Show TODO, FIXME, etc. comment tags in a tree view
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) - Material Design Icons for Visual Studio Code
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - EditorConfig Support for Visual Studio Code
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) - Debug your JavaScript code in the Chrome browser.
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) - Highlight web colors in your editor
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) - A customizable extension for colorizing matching brackets
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Auto rename paired HTML/XML tag
