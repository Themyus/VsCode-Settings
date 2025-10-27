# VSCode Settings

```json
{
  // Editor
  "editor.formatOnSave": true,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.lineHeight": 2.2,
  "editor.rulers": [150],
  "editor.wordWrap": "bounded",
  "editor.wordWrapColumn": 150,
  "editor.renderLineHighlight": "gutter",
  "editor.minimap.renderCharacters": false,
  "editor.minimap.enabled": false,
  "editor.semanticHighlighting.enabled": false,
  "editor.scrollbar.vertical": "hidden",
  "editor.tabSize": 2,
  "editor.cursorHeight": 30,
  "editor.cursorWidth": 3,
  "editor.cursorBlinking": "smooth",
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // Workbench
  "workbench.tree.indent": 8,
  "workbench.editor.labelFormat": "short",
  "workbench.editor.showTabs": "multiple",
  "workbench.editor.empty.hint": "hidden",
  "workbench.iconTheme": "catppuccin-perfect-mocha",
  "workbench.colorTheme": "Vesper",
  "workbench.statusBar.visible": true,
  "workbench.navigationControl.enabled": false,
  "workbench.startupEditor": "none",
  "workbench.view.alwaysShowHeaderActions": false,
  "workbench.secondarySideBar.defaultVisibility": "visible",
  "workbench.activityBar.location": "hidden",
  "workbench.panel.showLabels": false,

  // Explorer
  "explorer.compactFolders": false,
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.patterns": {},

  // Window
  "window.menuBarVisibility": "compact",
  "window.commandCenter": false,
  "window.zoomLevel": 0,

  // Git
  "git.decorations.enabled": false,
  "git.ignoreLimitWarning": true,
  "git.openRepositoryInParentFolders": "never",
  "gitlens.ai.model": "vscode",
  "gitlens.ai.vscode.model": "copilot:gpt-4.1",
  "github.copilot.enable": {
    "*": false,
    "plaintext": false,
    "markdown": false,
    "scminput": false
  },

  // Terminal
  "terminal.integrated.profiles.windows": {
    "PowerShell": {
      "source": "PowerShell",
      "icon": "terminal-powershell",
      "args": ["-NoExit", "-Command", "chcp 65001"]
    }
  },
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",

  // Custom UI Style
  "custom-ui-style.font.sansSerif": "JetBrains Mono Regular, -apple-system",
  "custom-ui-style.stylesheet": {
    ".explorer-viewlet .monaco-list-row .monaco-tl-row": {
      "padding-left": "10px",
      "box-sizing": "border-box"
    },
    ".explorer-viewlet .monaco-list-row:hover, .explorer-viewlet .monaco-list-row.selected": {
      "border-radius": "4px",
      "overflow": "hidden"
    }
  },

  // Others
  "chat.commandCenter.enabled": false,
  "redhat.telemetry.enabled": true,
  "laravel-pint.enable": true,
  "breadcrumbs.enabled": false,
  "notebook.defaultFormatter": "esbenp.prettier-vscode",
  "files.autoSave": "afterDelay"
}
