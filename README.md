# Settings.json-vscode
Minhas configurações do vscode no arquivo Settings.json

```json
{
    "git.suggestSmartCommit": false,
    "git.autofetch": true,
    "git.confirmSync": false,
    "editor.fontSize": 15,
    "explorer.confirmDragAndDrop": false,
    "workbench.editorAssociations": {
        "*.pdf": "default",
        "*.jar": "default",
        "*.fxml": "default"
    },
    "editor.multiCursorModifier": "ctrlCmd",
    "window.autoDetectColorScheme": true,
    "workbench.preferredHighContrastColorTheme": "Visual Studio Dark",
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "editor.colorDecorators": true,
    "editor.accessibilitySupport": "off",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "One Dark Pro",
    "editor.linkedEditing": true,
    "workbench.editor.closeEmptyGroups": true,

    "python.defaultInterpreterPath": "C:\\Users\\jhool\\AppData\\Local\\Programs\\Python\\Python311\\python.exe",
    "redhat.telemetry.enabled": true,

    // Settings para html
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode",
        "editor.autoIndent": "full"
        // "editor.codeLens": true
        // Settings para css
    },
    "[css]": {
        "editor.suggest.insertMode": "replace",
        "editor.autoIndent": "full",
        "editor.defaultFormatter": "vscode.css-language-features"
        // Settings para markdown
    },
    "[markdown]": {
        "editor.unicodeHighlight.ambiguousCharacters": false,
        "editor.unicodeHighlight.invisibleCharacters": false,
        "editor.wordWrap": "off",
        "editor.quickSuggestions": {
            "comments": "on",
            "strings": "on",
            "other": "on"
        },
        "editor.codeLens": true
        // Settings para json
    },
    "[json]": {
        "editor.quickSuggestions": {
            "strings": true
        },
        "editor.suggest.insertMode": "replace",
        "editor.autoIndent": "full",
    },
    "material-icon-theme.folders.theme": "specific",
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "[python]": {
        "editor.formatOnType": true
    },
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[java]": {
        "editor.suggest.snippetsPreventQuickSuggestions": true,
        "editor.autoIndent": "full",
    },

    // configurando extenção sqltools
    "sqltools.connections": [],
    // configurando extensão markdownlint
    "markdownlint.config": {
        "default": true,
        "MD007": {
            "indent": 4
        },
        "no-hard-tabs": false,
        "MD033": false,
        "MD003": false,
        "MD025": false,
        "MD032": false,
        "MD022": false,
        "MD036": false
    },

    // configurando background do vscode
    "background.fullscreen": {
        // "image": "https://w.wallhaven.cc/full/lm/wallhaven-lmqxxl.jpg",
        "image": "https://wallpapercave.com/wp/wp6192910.jpg",
        // "image": "https://w.wallhaven.cc/full/kw/wallhaven-kwolrd.jpg",
        // "image": "https://i.gifer.com/KNiu.gif",
        // "image": ["https://pathtoimage.png"], // An array may be useful when set interval for carousel
        "opacity": 0.91, // 0.85 ~ 0.95 recommended
        "size": "cover", // also css, `cover` to self-adaption (recommended)，or `contain`、`200px 200px`
        "position": "center", // alias to `background-position`, default `center`
        "interval": 0 // seconds of interval for carousel, default `0` to disabled.
    },
    "workbench.statusBar.visible": false,
    "git.openRepositoryInParentFolders": "always",
    "aws.codeWhisperer.includeSuggestionsWithCodeReferences": true
}
