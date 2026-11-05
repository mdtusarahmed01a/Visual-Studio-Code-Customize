# Visual Studio Code Customization

## 📝 Why?
I've been a loyal user of Visual Studio Code since 2018, and it has become my preferred code editor. Its speed and flexibility make it a reliable choice for me, regardless of the operating system I'm using. Over the years, I've created numerous projects using this code editor, and I've made various customizations to tailor it to my preferences.

I've tweaked its appearance, added and modified features, installed extensions, and even created a personalized theme because I haven't found a theme that's absolutely perfect for me. Each time I set up a new work environment, I find myself manually configuring these settings. To streamline this process, I've uploaded all my settings here, so I can quickly apply them. Feel free to use any of them for your convenience.

## 🛠 VS Code Settings
```bash
 
{
  // ==========================================
  // EDITOR - MAIN SETTINGS
  // ==========================================

  "editor.fontSize": 20,
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.wordWrap": "on",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 2,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  "editor.smoothScrolling": true,
  "editor.mouseWheelZoom": true,
  "editor.renderWhitespace": "selection",
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": true,
  "editor.minimap.showSlider": "always",
  "editor.scrollBeyondLastLine": false,
  "editor.linkedEditing": true,
  "editor.hover.enabled": true,

  // ==========================================
  // INTELLISENSE - AUTO CODE SUGGESTIONS
  // ==========================================

  "editor.quickSuggestions": {
    "other": "on",
    "comments": "off",
    "strings": "on"
  },
  "editor.suggestOnTriggerCharacters": true,
  "editor.acceptSuggestionOnEnter": "on",
  "editor.acceptSuggestionOnCommitCharacter": true,
  "editor.suggestSelection": "first",
  "editor.tabCompletion": "on",
  "editor.inlineSuggest.enabled": true,
  "editor.parameterHints.enabled": true,
  "editor.suggest.preview": true,
  "editor.suggest.showWords": true,
  "editor.suggest.showSnippets": true,
  "editor.snippetSuggestions": "top",
  "editor.wordBasedSuggestions": "matchingDocuments",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "editor.autoClosingBrackets": "languageDefined",
  "editor.autoClosingQuotes": "languageDefined",
  "editor.autoSurround": "languageDefined",

  // ==========================================
  // AUTO SAVE & FORMATTING
  // ==========================================

  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 1000,
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,
  "files.encoding": "utf8",

  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // ==========================================
  // JAVASCRIPT & TYPESCRIPT
  // ==========================================

  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.suggest.completeFunctionCalls": true,
  "typescript.suggest.completeFunctionCalls": true,
  "typescript.preferences.includePackageJsonAutoImports": "auto",

  // ==========================================
  // LANGUAGE FORMATTERS
  // ==========================================

  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // ==========================================
  // EMMET - HTML & REACT
  // ==========================================

  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },
  "emmet.triggerExpansionOnTab": true,
  "emmet.showAbbreviationSuggestions": true,
  "emmet.showExpandedAbbreviation": "always",

  // ==========================================
  // PRETTIER
  // ==========================================

  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.trailingComma": "es5",
  "prettier.semi": true,
  "prettier.tabWidth": 2,

  // ==========================================
  // WORKBENCH
  // ==========================================

  "workbench.colorTheme": "Andromeda",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.enablePreview": false,
  "workbench.startupEditor": "none",
  "workbench.sideBar.location": "left",
  "workbench.activityBar.location": "default",
  "workbench.statusBar.visible": true,
  "window.zoomLevel": 1,

  // ==========================================
  // ANDROMEDA DARK - PURPLE WORKSPACE
  // ==========================================

  "workbench.colorCustomizations": {
    "[Andromeda]": {
      "focusBorder": "#A29BFE",
      "foreground": "#DCDDE1",
      "descriptionForeground": "#9292A8",

      // Sidebar
      "sideBar.background": "#141422",
      "sideBar.foreground": "#C8C8D8",
      "sideBar.border": "#292946",
      "sideBarTitle.foreground": "#FFFFFF",
      "sideBarSectionHeader.background": "#19192E",
      "sideBarSectionHeader.foreground": "#A29BFE",

      // Activity Bar
      "activityBar.background": "#19192E",
      "activityBar.foreground": "#A29BFE",
      "activityBar.inactiveForeground": "#77778F",
      "activityBar.activeBorder": "#A29BFE",
      "activityBar.border": "#292946",

      // Tabs
      "editorGroupHeader.tabsBackground": "#19192E",
      "editorGroupHeader.tabsBorder": "#292946",
      "tab.activeBackground": "#302E59",
      "tab.activeForeground": "#FFFFFF",
      "tab.inactiveBackground": "#19192E",
      "tab.inactiveForeground": "#9292A8",
      "tab.activeBorderTop": "#A29BFE",
      "tab.border": "#292946",

      // Editor
      "editorGroup.border": "#292946",
      "editorLineNumber.foreground": "#62627C",
      "editorLineNumber.activeForeground": "#A29BFE",
      "editorCursor.foreground": "#A29BFE",
      "editor.selectionBackground": "#706FD355",
      "editor.inactiveSelectionBackground": "#706FD322",
      "editor.lineHighlightBackground": "#FFFFFF08",
      "editorIndentGuide.background1": "#383852",
      "editorIndentGuide.activeBackground1": "#706FD3",

      // Minimap
      "minimap.background": "#141422",
      "minimapSlider.background": "#706FD344",
      "minimapSlider.hoverBackground": "#706FD388",
      "minimapSlider.activeBackground": "#A29BFE88",

      // Terminal
      "terminal.background": "#19192E",
      "terminal.border": "#383852",
      "terminal.foreground": "#DCDDE1",
      "terminalCursor.foreground": "#A29BFE",

      // Panel
      "panel.background": "#141422",
      "panel.border": "#383852",
      "panelTitle.activeBorder": "#A29BFE",
      "panelTitle.activeForeground": "#FFFFFF",
      "panelTitle.inactiveForeground": "#9292A8",

      // Status Bar
      "statusBar.background": "#302E59",
      "statusBar.foreground": "#FFFFFF",
      "statusBar.border": "#383852",
      "statusBar.debuggingBackground": "#8E44AD",
      "statusBar.debuggingForeground": "#FFFFFF",

      // Title Bar
      "titleBar.activeBackground": "#19192E",
      "titleBar.activeForeground": "#FFFFFF",
      "titleBar.inactiveBackground": "#141422",
      "titleBar.inactiveForeground": "#9292A8",

      // Scrollbar
      "scrollbarSlider.background": "#706FD344",
      "scrollbarSlider.hoverBackground": "#706FD388",
      "scrollbarSlider.activeBackground": "#A29BFE88"
    }
  },

  // ==========================================
  // CODE COLOR CUSTOMIZATION
  // ==========================================

  "editor.tokenColorCustomizations": {
    "comments": "#95AFC0"
  },

  // ==========================================
  // LIVE SERVER
  // ==========================================

  "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,

  // ==========================================
  // LIVE SASS COMPILER
  // ==========================================

  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.generateMap": false,

  // ==========================================
  // TERMINAL - GIT BASH
  // ==========================================

  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontSize": 20,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.smoothScrolling": true,

  // ==========================================
  // SCREencast MODE
  // ==========================================

  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#A29BFE",
  "screencastMode.verticalOffset": 0,

  // ==========================================
  // DIFF EDITOR & OTHER
  // ==========================================

  "diffEditor.wordWrap": "on",
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "security.workspace.trust.untrustedFiles": "prompt"
}


```

## ⚙️ VS Code Extension
- Prettier - Code formatter
- ESLint
- ES7 + React/Redux/React-Native snippets
- Auto Rename Tag
- Path Intellisense
- Material Icon Theme
- GitLens
- Live Server
- Live Sass Compiler
- Auto Close Tag
- Code Spell Chacker
- DotENV
- Thunder Client
- Auto Import - ES6, TS, JSX, TSK


## 🎨 VS Code Themes
- Andromeda 

## 🔑 VS Code Keyboard Shortcuts 

| Keyboard Shortcuts | Windows / Linux     | Mac   |
| :-------- | :------- | :-------------------------------- |
|  HTML boilerplate  |  ! + TAB | ! + TAB |
|  Open the palette to search for a file  | Ctrl + P | cmd + P |
|  Add cursors to all matching selections  | Ctrl + Shift + L  | cmd + Shift + L |
|  Undo  |  Ctrl + U | cmd + U |
|  Select Current Line  | Ctrl + L | cmd + L |
|  Zen Mode  | Ctrl + K Z | cmd + K Z |
|  Toggle Sidebar  | Ctrl + B | cmd + B |
|  Search Global Files  | Ctrl + Shift + F | Ctrl + Shift + F |
|  Search on file  | Ctrl + F | cmd + F |
|  Find and Replace  | Ctrl + H | cmd + H |
|  Delete the previous Word  | Ctrl + Backspace | cmd + Backspace |
|  Move line up/Down  | Alt + up/down arrow | option + up/down arrow |
|  Add multiple cursors  | Ctrl + Alt +up/down arrow | cmd + option + up/down arrow |
|  Comment Line  | Ctrl + / | cmd + / |
|  Comment Line  | Ctrl + K + Ctrl + C | cmd + K + cmd + C |
|  Split View  | Ctrl + \  | cmd + \ |
|  Switch Between views |  Ctrl +1, Ctrl + 2 .. | cmd + 1, cmd + 2 |
|  Duplicate Line  | Alt + Shift + up/down | option + Shift + up/down |
|  Navigate to a specific line  | Ctrl + g | cmd + G |
|  Open Terminal | Ctrl + ` | cmd + ` |
|  To Show suggestion | Ctrl + Space | cmd + space |
|  To Close a TAB | Ctrl + W | cmd + W |
|  To Close all TAB | Ctrl + Shift + W | cmd + Shift + W |