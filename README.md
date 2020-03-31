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
* [Doxygen Documentation Generator](https://marketplace.visualstudio.com/items?itemName=cschlosser.doxdocgen)

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
    "python.linting.pylintArgs": [
        "--disable=W,C,E"
    ],
    "workbench.sideBar.location": "left",
    "workbench.iconTheme": "material-icon-theme",

    // The prefix that is used for each comment line except for first and last.
    "doxdocgen.c.commentPrefix": " * ",
    // Smart text snippet for factory methods/functions.
    "doxdocgen.c.factoryMethodText": "Create a {name} object",
    // The first line of the comment that gets generated. If empty it won't get generated at all.
    "doxdocgen.c.firstLine": "/**************************************************",
    // Smart text snippet for getters.
    "doxdocgen.c.getterText": "Get the {name} object",
    // The last line of the comment that gets generated. If empty it won't get generated at all.
    "doxdocgen.c.lastLine": " **************************************************/",
    // Smart text snippet for setters.
    "doxdocgen.c.setterText": "Set the {name} object",
    // Doxygen comment trigger. This character sequence triggers generation of Doxygen comments.
    "doxdocgen.c.triggerSequence": "/**",
    // Smart text snippet for constructors.
    "doxdocgen.cpp.ctorText": "Construct a new {name} object",
    // Smart text snippet for destructors.
    "doxdocgen.cpp.dtorText": "Destroy the {name} object",
    // The template of the template parameter Doxygen line(s) that are generated. If empty it won't get generated at all.
    "doxdocgen.cpp.tparamTemplate": "@tparam {param} ",
    // File copyright documentation tag.  Array of strings will be converted to one line per element.  Can template {year}.
    "doxdocgen.file.copyrightTag": [
        "@copyright Copyright (c) {year}"
    ],
    // Additional file documentation.  Array of strings will be converted to one line per element.  Can template {year}, {date}, {author}, and {email}.
    "doxdocgen.file.customTag": [],
    // The order to use for the file comment. Values can be used multiple times. Valid values are shown in default setting.
    "doxdocgen.file.fileOrder": [
        "file",
        "author",
        "brief",
        "empty",
        "version",
        "date",
        // "empty",
        // "copyright",
        // "empty",
        // "custom"
    ],
    // The template for the file parameter in Doxygen.
    "doxdocgen.file.fileTemplate": "@file {name}",
    // Version number for the file.
    "doxdocgen.file.versionTag": "@version 0.1",
    // Set the e-mail address of the author.  Replaces {email}.
    "doxdocgen.generic.authorEmail": "Jiawei.Wang@harman.com",
    // Set the name of the author.  Replaces {author}.
    "doxdocgen.generic.authorName": "Wang Jiawei",
    // Set the style of the author tag and your name.  Can template {author} and {email}.
    "doxdocgen.generic.authorTag": "@author {author} ({email})",
    // If this is enabled a bool return value will be split into true and false return param.
    "doxdocgen.generic.boolReturnsTrueFalse": true,
    // The template of the brief Doxygen line that is generated. If empty it won't get generated at all.
    "doxdocgen.generic.briefTemplate": "@brief {text}",
    // The format to use for the date.
    "doxdocgen.generic.dateFormat": "YYYY-MM-DD",
    // The template for the date parameter in Doxygen.
    "doxdocgen.generic.dateTemplate": "@date {date}",
    // Decide if you want to get smart text for certain commands.
    "doxdocgen.generic.generateSmartText": true,
    // Whether include type information at return.
    "doxdocgen.generic.includeTypeAtReturn": true,
    // How many lines the plugin should look for to find the end of the declaration. Please be aware that setting this value too low could improve the speed of comment generation by a very slim margin but the plugin also may not correctly detect all declarations or definitions anymore.
    "doxdocgen.generic.linesToGet": 20,
    // The order to use for the comment generation. Values can be used multiple times. Valid values are shown in default setting.
    "doxdocgen.generic.order": [
        "brief",
        "empty",
        "tparam",
        "param",
        "return"
    ],
    // The template of the param Doxygen line(s) that are generated. If empty it won't get generated at all.
    "doxdocgen.generic.paramTemplate": "@param {param} ",
    // The template of the return Doxygen line that is generated. If empty it won't get generated at all.
    "doxdocgen.generic.returnTemplate": "@return {type} ",
    // Decide if the values put into {name} should be split according to their casing.
    "doxdocgen.generic.splitCasingSmartText": true
}
```

myCodeSegment.code-snippets
```json
{
	// Place your 全局 snippets here. Each snippet is defined under a snippet name and has a scope, prefix, body and 
	// description. Add comma separated ids of the languages where the snippet is applicable in the scope field. If scope 
	// is left empty or omitted, the snippet gets applied to all languages. The prefix is what is 
	// used to trigger the snippet and the body will be expanded and inserted. Possible variables are: 
	// $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. 
	// Placeholders with the same ids are connected.
	// Example:
	// "Print to console": {
	// 	"scope": "javascript,typescript",
	// 	"prefix": "log",
	// 	"body": [
	// 		"console.log('$1');",
	// 		"$2"
	// 	],
	// 	"description": "Log output to console"
	// }
	"doxygen": {
		"prefix": "dox",
		"body": [
			"/**"
		],
		"description": "doxygen"
	},
	"doxygenOneline": {
		"prefix": "dox1",
		"body": [
			"/*! $1 */"
		],
		"description": "doxygen one line"
	},
	"brief": {
		"prefix": "bri",
		"body": [
			"/*! @brief  $1  */"
		],
		"description": "brief"
	},
	"include area comment": {
		"prefix": "arinc",
		"body": [
			"/**************************************************",
			" *                 INCLUDES START                 *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *                 INCLUDES END                   *",
			" **************************************************/",
			""
		],
		"description": "include area comment"
	},
	"macros area": {
		"prefix": "armcr",
		"body": [
			"/**************************************************",
			" *                   MACROS START                 *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *                   MACROS END                   *",
			" **************************************************/",
			""
		],
		"description": "macros area"
	},
	"data types and structures area": {
		"prefix": "artyp",
		"body": [
			"/**************************************************",
			" *         DATA TYPES AND STRUCTURES START        *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *         DATA TYPES AND STRUCTURES END          *",
			" **************************************************/",
			""
		],
		"description": "data types and structures area"
	},
	"variables area": {
		"prefix": "arvar",
		"body": [
			"/**************************************************",
			" *                VARIABLES START                 *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *                VARIABLES END                   *",
			" **************************************************/",
			""
		],
		"description": "variables area"
	},
	"function definition area": {
		"prefix": "arfun",
		"body": [
			"/**************************************************",
			" *           FUNCTION DEFINITION START            *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *           FUNCTION DEFINITION END              *",
			" **************************************************/",
			""
		],
		"description": "function definition area"
	},
	"code area": {
		"prefix": "arcode",
		"body": [
			"/**************************************************",
			" *                CODE SEGMENT START              *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *                CODE SEGMENT END                *",
			" **************************************************/",
			""
		],
		"description": "code area"
	},
	"constant area": {
		"prefix": "arconst",
		"body": [
			"/**************************************************",
			" *                  CONSTANT START                *",
			" **************************************************/",
			"$1",
			"/**************************************************",
			" *                  CONSTANT END                  *",
			" **************************************************/",
			""
		],
		"description": "constant area"
	}
}
```
