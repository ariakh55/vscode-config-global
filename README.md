# Visual Studio Code - Config

This is a global config for vscode in both linux and windows.

In this settings I have maintained the things that programmers need to have in their editors right away!!
(and **ofc** for lazy ones 👀)

So this settings are the ones that you need to have your vsc configed.

let us begin...

## Global configuration

### workbench icon theme

Set a beautiful icon set for your files.
Remeber to install ```pkief.material-icon-theme```

```json
"workbench.iconTheme": "material-icon-theme"
```

### editor font size

Just in case.

```json
"editor.fontSize": 17
```

### Windows terminal configurations

If you have windows you can set this for your code to make it recognize your terminals.

```json
"terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        },
    },
"terminal.integrated.defaultProfile.windows": "PowerShell"
```

### Windows terminal configurations

If you have windows you can set this for your code to make it recognize your terminals.

```json
"terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        },
    },
"terminal.integrated.defaultProfile.windows": "PowerShell"
```

### Just some typical settings...part 1

```json
"terminal.integrated.tabs.enabled": true,
"workbench.startupEditor": "welcomePageInEmptyWorkbench",
"markdown.preview.typographer": true,
```

### Beautiful product icons (recommendation)

Before you set this one install ```miguelsolorio.fluent-icons```

```json
"workbench.productIconTheme": "fluent-icons"
```

### Auto save setting

**This is crucial!!** for your own sanity and your code sake set this one.

```json
"files.autoSave": "afterDelay"
```

### Emmet profile

If you are a **React** dev or a web dev you can try these settings for faster codings!

also install these extentions... for react dev.
```
1. dsznajder.es7-react-js-snippets
2. dbaeumer.vscode-eslint
3. graphql.vscode-graphql
4. xabikos.javascriptsnippets
5. ms-vscode.vscode-typescript-next
6. ritwickdey.live-sass
7. christian-kohler.npm-intellisense
8. jpoissonnier.vscode-styled-components
9. mrmlnc.vscode-scss
```

```json
"emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "php": "html"
},
"emmet.syntaxProfiles": {
    "php": "html"
}
```

### Just some typical settings...part 2

```json
"workbench.editor.decorations.badges": false,
"terminal.integrated.fontFamily": "Delugia Mono Nerd Font"
```

### Linux Settings

A good setting to hide the gnome title bar

```json
"window.titleBarStyle": "custom"
```

### A good color scheme

Install this before proceeding ```arcticicestudio.nord-visual-studio-code```

```json
"workbench.colorTheme": "Nord"
```