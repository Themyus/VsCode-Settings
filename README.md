# VsCode Settings

```json
{
  // Editor
  "editor.formatOnSave": true,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.lineHeight": 2.2,
  "editor.rulers": [140],
  "editor.wordWrap": "bounded",
  "editor.wordWrapColumn": 150,
  "editor.renderLineHighlight": "gutter",
  "editor.minimap.renderCharacters": false,
  "editor.minimap.enabled": false,
  "editor.semanticHighlighting.enabled": false,
  "editor.parameterHints.enabled": false, ei vini
  "editor.scrollbar.vertical": "visible",
  "editor.scrollbar.horizontal": "hidden",
  "editor.stickyScroll.enabled": false,
  "editor.tabSize": 2,
  "editor.cursorHeight": 30,
  "editor.cursorWidth": 3,
  "editor.cursorBlinking": "blink",
  "editor.multiCursorLimit": 50000,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.suggestSelection": "first",
  "editor.tokenColorCustomizations": {
    "textMateRules": []
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },

  // ESlint
  "eslint.validate": ["javascript", "javascriptreact", "graphql"],

  // Workbench
  "workbench.tree.indent": 16,
  "workbench.tree.enableStickyScroll": false,
  "workbench.editor.labelFormat": "short",
  "workbench.editor.showTabs": "multiple",
  "workbench.editor.empty.hint": "hidden",
  "workbench.statusBar.visible": true,
  "workbench.navigationControl.enabled": false,
  "workbench.startupEditor": "none",
  "workbench.view.alwaysShowHeaderActions": false,
  "workbench.secondarySideBar.defaultVisibility": "visible",
  "workbench.activityBar.location": "bottom",
  "workbench.panel.showLabels": false,
  "workbench.colorTheme": "Vesper",
  "workbench.preferredDarkColorTheme": "Oscura Midnight",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.iconTheme": "symbols",
  "symbols.hidesExplorerArrows": true,
  "symbols.files.associations": {
    "*.module.ts": "nest",
    "*.guard.ts": "typescript",
    "*.spec.ts": "ts-test",
    "*.e2e-spec.ts": "ts-test",
    "*.mock.ts": "ts-test",
    "vitest.config.e2e.ts": "vite",
    ".env.development.local": "gear",
    ".env.test.local": "gear",
    ".env.local": "gear",
    ".env.sst": "gear",
    ".env.example": "gear",
    "*.ndjson": "brackets-orange"
  },
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "postcss",
    ".dev.vars": "dotenv",
    "*.ndjson": "jsonl"
  },

  // Explorer
  "explorer.compactFolders": false,
  "explorer.fileNesting.enabled": true,
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
    "package.json": ".eslint*, eslint.config.*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
    "tailwind.config.*": "tailwind.config*, postcss.config*",
    ".env.local": ".env*",
    ".env": ".env*"
  },

  // Window
  "window.menuBarVisibility": "compact",
  "window.commandCenter": false,
  "window.zoomLevel": 0,
  "window.autoDetectColorScheme": true,
  "window.titleBarStyle": "custom",

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
  "javascript.updateImportsOnFileMove.enabled": "always",

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
  "terminal.integrated.lineHeight": 1.8,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "terminal.integrated.showExitAlert": false,

  // Custom UI Style
  "custom-ui-style.font.sansSerif": "JetBrains Mono Regular, -apple-system",
  "custom-ui-style.stylesheet": {
    ".title-label > h2": "display: none",
    ".editor-actions": "display: none",
    ".nosidebar .inline-tabs-placeholder": "width: 75px",
    ".pane-header": "padding: 0 8px",
    ".pane-body": "padding: 8px",
    ".split-view-view:first-child .pane-header": "display: none !important;",
    ".monaco-list-row": "border-radius: 4px;",
    ".monaco-workbench .monaco-list:not(.element-focused):focus:before": "display: none;",

    ".explorer-viewlet .monaco-list-row .monaco-tl-row": {
      "box-sizing": "border-box"
    },
    ".explorer-viewlet .monaco-list-row:hover, .explorer-viewlet .monaco-list-row.selected": {
      "border-radius": "4px",
      "overflow": "hidden"
    }
  },
  "custom-ui-style.electron": {
    "frame": false,
    "titleBarStyle": "hiddenInset",
    "trafficLightPosition": {
      "x": 11,
      "y": 10
    }
  },

  // Tailwind CSS
  "tailwindCSS.experimental.classRegex": [
    ["tv\\(([^)]*)\\)", "cva\\(([^)]*)\\)", "[\"'`]([^\"'`]*).*?[\"'`]"],
    "class:\\s*?[\"'`]([^\"'`]*).*?,",
    "tw\\('([^']*)'\\)"
  ],

  // Others
  "chat.commandCenter.enabled": false,
  "redhat.telemetry.enabled": true,
  "laravel-pint.enable": true,
  "breadcrumbs.enabled": false,
  "notebook.defaultFormatter": "esbenp.prettier-vscode",
  "files.autoSave": "afterDelay",
  "update.mode": "start",
  "python.analysis.autoImportCompletions": true,
  "java.saveActions.organizeImports": true,

  // CSpell
  "cSpell.language": "en,pt",
  "cSpell.userWords": [
    "automations",
    "bootcamp",
    "chakra",
    "checkin",
    "checkins",
    "cloudflare",
    "clsx",
    "Codegen",
    "datadog",
    "Datetime",
    "dayjs",
    "Dotenv",
    "Elysia",
    "esbuild",
    "fastify",
    "Fastify",
    "feedbackwidget",
    "ffprobe",
    "gamificada",
    "Hasher",
    "hono",
    "Hono",
    "ilike",
    "IUGU",
    "jamjuree",
    "jupiter",
    "ksuid",
    "liveblocks",
    "LIVEBLOCKS",
    "Marguerita",
    "middlewares",
    "mixpanel",
    "monaco",
    "nestjs",
    "nivo",
    "omni",
    "Omni",
    "Onboarded",
    "pallas",
    "postgres",
    "postgresql",
    "prefetch",
    "reactflow",
    "retriable",
    "roboto",
    "rocketseat",
    "rotion",
    "rsxp",
    "Sandpack",
    "shiki",
    "skylab",
    "sqlite",
    "supergraph",
    "svgr",
    "sympla",
    "tailwindcss",
    "textblock",
    "tiptap",
    "trpc",
    "TRPC",
    "tsup",
    "unfollow",
    "Unfollow",
    "unform",
    "Unform",
    "unmark",
    "upsert",
    "Usuario",
    "webm",
    "WEBPUSH",
    "zrevrank",
    "zscore"
  ]
}
