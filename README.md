# vscode_json

{
    //! editor settings
    "editor.hover.enabled": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.lineHeight": 2.3,
    "editor.cursorBlinking": "expand",
    "editor.cursorWidth": 2,
    "editor.fontSize": 18,
    "editor.formatOnSave": true,
    "diffEditor.wordWrap": "on",
    "editor.wordWrap": "on",
    "files.autoSave": "afterDelay",
    "editor.suggestSelection": "first",
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
    "editor.find.addExtraSpaceOnTop": true,
    "editor.fontLigatures": true,
    "editor.fontWeight": "100",
    "editor.find.cursorMoveOnType": true,
    "editor.formatOnType": true,
    "editor.quickSuggestions": {
        "comments": true,
        "strings": true
    },
    //! Git Project Manager
    "gitProjectManager.storeRepositoriesBetweenSessions": true,
    "gitProjectManager.codePath": "C:\\Program Files (x86)\\Microsoft VS Code\\bin\\code.cmd",
    "gitProjectManager.ignoredFolders": ["node_modules"],
    "gitProjectManager.maxDepthRecursion": 4,
    "gitProjectManager.checkRemoteOrigin": true,
    "gitProjectManager.openInNewWindow": true,
    "gitProjectManager.baseProjectsFolders": ["/home/user/nodeProjects", "/home/user/personal/pocs"],
    //! cursor style
    "editor.cursorSmoothCaretAnimation": true,
    "editor.renderLineHighlight": "gutter",
    "editor.hideCursorInOverviewRuler": true,
    //! font
    "editor.fontFamily": "'JetBrains Mono', 'Fira Code', 'Cascadia Code', 'Operator Mono Lig'",
    //! powermode
    "powermode.enabled": false,
    "powermode.presets": "flames",
    //! better comments
    "better-comments.highlightPlainText": true,
    "better-comments.tags": [
        {
            "tag": "*",
            "color": "#000000",
            "bold": true,
            "strikethrough": false,
            "backgroundColor": "#198754"
        },
        {
            "tag": "?",
            "color": "#000000",
            "bold": true,
            "strikethrough": false,
            "backgroundColor": "#DC3545"
        },
        {
            "tag": "/",
            "color": "#FFFFFF",
            "bold": true,
            "strikethrough": false,
            "backgroundColor": "#6610F2"
        },
        {
            "tag": "!",
            "color": "#000000",
            "bold": true,
            "strikethrough": false,
            "backgroundColor": "#FFC107"
        },
        {
            "tag": "$",
            "color": "#000000",
            "bold": true,
            "strikethrough": false,
            "backgroundColor": "#0D6EFD"
        }
    ],
    "editor.tokenColorCustomizations": {
        "comments": "#ff0000b7"
    },
    //! bracket pair
    "bracket-pair-colorizer-2.scopeLineCSS": ["borderStyle : solid", "borderWidth : 0px", "borderColor : {#51ff00}", "opacity: 0.5"],
    //! emojisense
    "emojisense.languages": {
        "plaintext": {
            "markupCompletionsEnabled": true,
            "emojiDecoratorsEnabled": true
        },
        "javascript.validate.enable": false,
        "abap": true,
        "bat": true,
        "bibtex": true,
        "clojure": true,
        "coffeescript": true,
        "c": true,
        "cpp": true,
        "csharp": true,
        "css": true,
        "diff": true,
        "dockerfile": true,
        "fsharp": true,
        "git-commit": true,
        "git-rebase": true,
        "go": true,
        "groovy": true,
        "handlebars": true,
        "html": true,
        "ini": true,
        "java": true,
        "javascript": true,
        "javascriptreact": true,
        "json": true,
        "jsonc": true,
        "latex": true,
        "less": true,
        "lua": true,
        "makefile": true,
        "markdown": true,
        "objective-c": true,
        "objective-cpp": true,
        "perl6": true,
        "php": true,
        "powershell": true,
        "jade": true,
        "python": true,
        "r": true,
        "razor": true,
        "ruby": true,
        "rust": true,
        "scss": true,
        "sass": true,
        "shaderlab": true,
        "shellscript": true,
        "sql": true,
        "swift": true,
        "typescript": true,
        "typescriptreact": true,
        "tex": true,
        "vb": true,
        "xml": true,
        "xsl": true,
        "yaml": true
    },
    //! theme customaizations
    "workbench.colorCustomizations": {
        "titleBar.activeBackground": "#111",
        "minimap.background": "#47478700",
        "editor.background": "#000",
        "sideBar.background": "#000",
        "tab.inactiveForeground": "#ff009d",
        "tab.activeForeground": "#fffb00",
        "tab.activeBorder": "#51ff",
        "tab.activeBorderTop": "#51ff",
        "activityBar.background": "#111",
        "activityBar.dropBorder": "#ff0000",
        "activityBar.inactiveForeground": "#00fff2",
        "activityBar.activeBorder": "#00ff2f",
        "activityBar.foreground": "#00ff2f",
        "activityBarBadge.background": "#00000000",
        "editorGutter.background": "#111",
        "statusBar.background": "#111",
        "editor.selectionBackground": "#333",
        "editor.lineHighlightBackground": "#222",
        "statusBarItem.hoverBackground": "#6363633a",
        "list.activeSelectionBackground": "#0004ffad",
        "editorGroupHeader.tabsBackground": "#000",
        "tab.activeBackground": "#58434300",
        "button.background": "#2b2b2b",
        "tab.inactiveBackground": "#111",
        "terminal.background": "#000",
        "terminal.border": "#2c2c54",
        "scrollbarSlider.background": "#47478773",
        "scrollbarSlider.hoverBackground": "#716fd35b",
        "editorCursor.background": "#ffff4d",
        "editorCursor.foreground": "#ffff4d",
        "bookmarks.lineBorder": "#2f2f2f"
    },
    //! quokka
    "quokka.colors": {
        "covered": "#62b455",
        "errorPath": "#ffa0a0",
        "errorSource": "#fe536a",
        "notCovered": "#cccccc",
        "partiallyCovered": "#d2a032"
    },
    //! prettier
    "prettier.enableDebugLogs": true,
    "prettier.insertPragma": true,
    "prettier.withNodeModules": true,
    "prettier.vueIndentScriptAndStyle": true,
    "prettier.useTabs": true,
    "prettier.singleQuote": true,
    "prettier.jsxSingleQuote": true,
    "prettier.jsxBracketSameLine": true,
    "prettier.trailingComma": "all",
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    //! git
    "git.suggestSmartCommit": true,
    "gitlens.advanced.messages": {
        "suppressGitMissingWarning": true
    },
    //! terminal
    "editor.linkedEditing": true,
    "terminal.integrated.cursorWidth": 2,
    "terminal.integrated.fontFamily": "'Cascadia Code'",
    "terminal.integrated.cursorStyle": "underline",
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.lineHeight": 1.2,
    "terminal.integrated.letterSpacing": 1,
    "terminal.integrated.fontSize": 16,
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    //! output
    // "output.smartScroll.enabled": true,
    //! bookmarks
    "bookmarks.navigateThroughAllFiles": true,
    "bookmarks.showCommandsInContextMenu": true,
    "bookmarks.wrapNavigation": true,
    "bookmarks.saveBookmarksInProject": true,
    "bookmarks.label.suggestion": "useWhenSelected",
    "bookmarks.multicursor.toggleMode": "eachLineIndependently",
    "bookmarks.sideBar.expanded": true,
    "bookmarks.useWorkaroundForFormatters": true,
    "bookmarks.experimental.enableNewStickyEngine": true,
    //! spell words
    "cSpell.userWords": ["arif", "azmarif", "????????????", "null"],
    //! others
    "workbench.colorTheme": "Learn with Sumit - Shades of Grey",
    "workbench.iconTheme": "vscode-icons",
    "projectManager.git.baseFolders": ["Main"],
    "cSpell.language": "en,en-GB,en-US,en-BN",
    "search.seedWithNearestWord": true,
    "liveServer.settings.CustomBrowser": "firefox",
    "bracket-pair-colorizer-2.scopeLineRelativePosition": false,
    "bracket-pair-colorizer-2.showHorizontalScopeLine": false,
    "bracket-pair-colorizer-2.showVerticalScopeLine": false,
    "json.format.enable": true,
    "json.schemaDownload.enable": true,
    "js/ts.implicitProjectConfig.strictFunctionTypes": true,
    "typescript.format.placeOpenBraceOnNewLineForFunctions": true,
    "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
    "javascript.format.placeOpenBraceOnNewLineForFunctions": true,
    "javascript.format.placeOpenBraceOnNewLineForControlBlocks": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": true,
    "javascript.referencesCodeLens.showOnAllFunctions": true,
    "js/ts.implicitProjectConfig.checkJs": true,
    "js/ts.implicitProjectConfig.experimentalDecorators": true,
    "js/ts.implicitProjectConfig.strictNullChecks": true,
    "notebook.outline.showCodeCells": true,
    "liveshare.notebooks.allowGuestExecuteCells": true,
    "notebook.consolidatedRunButton": true,
    "terminal.integrated.enableBell": true,
    "terminal.integrated.fastScrollSensitivity": 4,
    "code-runner.runInTerminal": true,
    "terminal.integrated.allowMnemonics": true,
    "terminal.integrated.copyOnSelection": false,
    "explorer.confirmDelete": true,
    "editor.foldingImportsByDefault": true,
    "window.zoomLevel": 1,
    //! debug
    "debug.console.acceptSuggestionOnEnter": "on",
    "debug.console.fontFamily": "'Cascadia Code'",
    "debug.console.fontSize": 16,
    "debug.showBreakpointsInOverviewRuler": true,
    "debug.showSubSessionsInToolBar": true,
    "bracket-pair-colorizer-2.forceUniqueOpeningColor": true,
    "editor.parameterHints.cycle": true,
    "javascript.inlayHints.parameterTypes.enabled": true,
    "javascript.suggest.completeFunctionCalls": true,
    "typescript.inlayHints.parameterNames.enabled": "all",
    "typescript.inlayHints.parameterTypes.enabled": true,
    "typescript.suggest.completeFunctionCalls": true,
    "javascript.inlayHints.parameterNames.enabled": "all",
    "editor.scrollbar.verticalScrollbarSize": 8,
    "editor.scrollbar.horizontalScrollbarSize": 8,
    "workbench.editor.wrapTabs": true
}
