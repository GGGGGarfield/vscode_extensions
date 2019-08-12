# vscode_extensions

* [Align by RegEx](https://marketplace.visualstudio.com/items?itemName=janjoerke.align-by-regex)
* [background](https://marketplace.visualstudio.com/items?itemName=shalldie.background)
* [Bracket Pair Colorizer2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
* [Chinese (Simplified) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hans)
* [GitHub Plus Theme](https://marketplace.visualstudio.com/items?itemName=thenikso.github-plus-theme)
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
* [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
* [markdown-index](https://marketplace.visualstudio.com/items?itemName=legendmohe.markdown-index)
* [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
* [TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut)
* [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

settings.json
```json
{
    "C_Cpp.errorSquiggles": "Disabled",
    "bracket-pair-colorizer-2.colors": [
        // "#66ccff",
        // "#ff66cc",
        // "#007788",
        "#0066cc",
        "#cc0066",
        "#66cc00",
        "#6600cc",
        "#cc6600",
        "#00cc66",
    ],
    "workbench.colorCustomizations": {
        "editor.selectionBackground": "#66ccffcc",
        "editor.selectionForeground":"#ffffff",
        "editor.selectionHighlightBackground":"#66ccff66",
        "editor.selectionHighlightBorder":"#ee000000",
        "editor.findMatchBorder":"#ee000000",
        "editor.findMatchBackground":"#66cc00cc",
        "editor.findMatchHighlightBorder":"#ee000000",
        "editor.findMatchHighlightBackground":"#66cc0066",
        "editor.findRangeHighlightBackground":"#ee0000",
        "editorBracketMatch.border": "#ee0000",
        "editorBracketMatch.background": "#00000000",
    },
    "search.useIgnoreFiles": false,
    "git.autorefresh": false,
    "git.autoRepositoryDetection": false,
    "git.confirmEmptyCommits": false,
    "git.confirmForcePush": false,
    "git.confirmSync": false,
    "git.decorations.enabled": false,
    "git.enabled": false,
    "search.followSymlinks": false,
    "editor.renderControlCharacters": false,
    "editor.fontSize": 12,
    "outline.problems.badges": false,
    "outline.problems.colors": false,
    "outline.problems.enabled": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "files.autoSave": "off",
    "C_Cpp.updateChannel": "Insiders",
    "workbench.colorTheme": "GitHub Plus",
    "workbench.statusBar.visible": true,
    "window.zoomLevel": 0,
    "workbench.activityBar.visible": true,
    "breadcrumbs.enabled": true,
    "editor.minimap.enabled": true,
    "window.menuBarVisibility": "default",
    "editor.renderWhitespace": "all",
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    "workbench.startupEditor": "welcomePage",
    "window.restoreWindows": "none",
    "python.jediEnabled": false,
    "terminal.integrated.rendererType": "dom",
    "markdown-preview-enhanced.enableCriticMarkupSyntax": true,
    "markdown-preview-enhanced.enableExtendedTableSyntax": true,
    "markdown-preview-enhanced.codeBlockTheme": "vs.css"
}
```