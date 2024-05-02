# Settings.json-vscode
Minhas configurações do vscode no arquivo Settings.json

```json
{
    "terminal.integrated.sendKeybindingsToShell": true,
    "explorer.confirmDelete": false,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "One Dark Pro",
    "[xml]": {
        "editor.defaultFormatter": "DotJoshJohnson.xml"
    },
    "redhat.telemetry.enabled": true,
    "editor.multiCursorLimit": 100000,
    "[sql]": {
        "editor.defaultFormatter": "mtxr.sqltools"
    },
    "[json]": {
        "editor.quickSuggestions": {
            "strings": true
        },
        "editor.suggest.insertMode": "replace",
        "editor.defaultFormatter": "vscode.json-language-features",
    },
    "[python]": {
        "editor.formatOnType": true
    },
    "security.workspace.trust.untrustedFiles": "open",
    "workbench.colorCustomizations": {
        "editorWarning.foreground": "#00000000",
    },
    "[oraclesql]": {
        "editor.suggest.showSnippets": true,
        "editor.quickSuggestions": {
            "comments": "on",
            "strings": "on",
            "other": "on"
        }
    },
    "files.associations": {
        "*.sql": "sql"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "git.openRepositoryInParentFolders": "always",
    "git.autofetch": true,
    "github.copilot.enable": {
        "*": true,
        "plaintext": false,
        "markdown": false,
        "scminput": false
    },
    "remote.SSH.defaultExtensions": [
        "gitpod.gitpod-remote-ssh"
    ],
    "terminal.integrated.fontSize": 12,
    "javascript.preferGoToSourceDefinition": true,
    "explorer.confirmDragAndDrop": false,
    "editor.dragAndDrop": false,
    "editor.dropIntoEditor.enabled": false,
    "editor.pasteAs.enabled": false,
    "markdown.editor.filePaste.enabled": false,
    "workbench.editor.splitOnDragAndDrop": false,
    "[vue]": {
        "editor.defaultFormatter": "Vue.volar"
    },
    "cmake.configureOnOpen": false,
    "cmake.options.statusBarVisibility": "visible",
    "git.confirmSync": false,
}
