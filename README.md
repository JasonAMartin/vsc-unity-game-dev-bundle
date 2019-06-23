# UNITY GAME DEV BUNDLE

#### Setting up a great VSC environment to get coding now.

If you're an Unity game dev who likes Visual Studio Code, this bundle is for you. I've bundled up the extensions (with settings) that I use when developing in Unity.

Yes, normal Visual Studio is awesome, but I really love **[Visual Studio Code](https://code.visualstudio.com/)** and am always telling people about it.

This bundle removes the pain point of getting started. Just click, copy settings and go!

### SOME COOL THINGS YOU CAN DO RIGHT AWAY

- Use the project manager to organize your projects (shift+cmd and start typing "project" for more)
- Get quick GIT info on each line thanks to Git Lens.
- Nice highlighting for DEPRECATED, FIXME, REVIEW, STUB and TODO notes.
- Great Todo Tree that shows all of the spots in your code with DEPRECATED, FIXME, REVIEW, STUB, and TODO. And they have custom colors/icons already setup.
- Enjoy a nice UI from the start.
- and more!

## RECOMMENDED USER SETTINGS

Here's the user settings I'm currently using. Just open user settings in VSC and paste this JSON into there.

These settings are off a Windows machine, so if you're on Linux or Windows, change the editor.fontFamily to something appropriate and you can remove the git.path setting.

And dont' forget to peek at the overall settings because there's a ton you can tweak.

**These settings will get you running right away.**

```
{
    "auto-close-tag.enableAutoCloseSelfClosingTag": true,
    "auto-close-tag.SublimeText3Mode": true,
    "bracket-pair-colorizer-2.colors": [
        "crimson",
        "darkorange",
        "mediumseagreen",
        "LightSkyBlue"
    ],
    "csharp.format.enable": false,
    "color-highlight.markerType": "dot-before",
    "editor.cursorStyle": "block",
    "editor.fontSize": 14,
    "editor.formatOnPaste": false,
    "editor.formatOnSave": false,
    "editor.formatOnType": false,
    "editor.rulers": [150],
    "editor.tabSize": 2,
    "files.trimTrailingWhitespace": true,
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "git.path": "C:\\Program Files\\Git\\cmd\\git.exe",
    "indentRainbow.colors": [
        "rgba(16,16,16,0.1)",
        "rgba(16,16,16,0.3)",
        "rgba(16,16,16,0.6)",
        "rgba(16,16,16,0.4)",
        "rgba(16,16,16,0.2)"
    ],
    "npm.enableScriptExplorer": true,
    "todohighlight.isCaseSensitive": true,
    "telemetry.enableTelemetry": false,
    "todohighlight.keywords": [
        {
            "text": "DEPRECATED",
            "color": "black",
            "backgroundColor": "yellow",
        },
        {
            "text": "FIXME",
            "color": "white",
            "backgroundColor": "red",
        },
        {
            "text": "REVIEW",
            "color": "blue",
            "backgroundColor": "white",
        },
        {
            "text": "STUB",
            "color": "white",
            "backgroundColor": "grey",
        },
        {
            "text": "TODO",
            "color": "white",
            "backgroundColor": "green",
        },
    ],
    "todo-tree.tags": [
        "DEPRECATED",
        "FIXME",
        "REVIEW",
        "STUB",
        "TODO"
    ],
    "todo-tree.customHighlight": {
        "DEPRECATED": {
            "icon": "stop",
            "iconColour": "yellow"
        },
        "FIXME": {
            "icon": "alert",
            "iconColour": "red"
        },
        "REVIEW": {
            "icon": "search",
            "iconColour": "white"
        },
        "STUB": {
            "icon": "beaker",
            "iconColour": "grey"
        },
        "TODO": {
            "icon": "pin",
            "type": "line"
        }
    },
    "workbench.colorCustomizations": {
        "editorIndentGuide.activeBackground": "#20b0f3"
    },
    "workbench.colorTheme": "eppz!",
    "workbench.iconTheme": "vscode-icons"
}
```

# EXTENSIONS BREAKDOWN

Here's a list of extensions in this pack along with any relevant notes.

### GENERAL IMPROVEMENTS

> [TODO Hightlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) :: Adds highlighting when you put a TODO or FIXME in your code. You can add more words and styles too. If you're using the recommended settings, you already have those plus STUB, REVIEW and DEPRECATED.

> [TODO Tree](https://marketplace.visualstudio.com/items?itemName=gruntfuggly.todo-tree) :: Nice plugin to see all your TODOs in one place. My settings also grab FIXME, DEPRECATED, STUB and REVIEW. And they have custom icons/colors setup.

> [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) :: Colorizes brackets so it's easier to see what section you're in.

> [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) :: Makes it even easier to see what nest you're in.

> [Sort Lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines) :: Easy way to sort lines in the editor.

> [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

> [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) :: Easy way to create/manage projects.

> [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) :: Creates a way to bookmark a line of code.

> [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) :: Creates closing tags, which VSC doesn't do out the box.

> [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) :: When you rename a tag, this will rename the closing tag as well.

> [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) :: Adds more code formatting functionality.

> [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) :: Shows colors for hex colors it finds in code.

> [Formatting Toggle](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle) :: Quick way to toggle formatting. It puts a one-click toggle in the bottom bar.

> [Copy Relative Path](https://marketplace.visualstudio.com/items?itemName=alexdima.copy-relative-path) :: Drop menu off file will now have 'Copy Path' that copies over the relative path of the file.

> [Partial Diff](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) :: Ability to diff text sections in file or in multiple files.

> [DotJoshJohnson.xml](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) :: XML formatting/tooling.


### VSC THEME

> [Eppz](https://marketplace.visualstudio.com/items?itemName=eppz.eppz-code) :: C# Unity Theme.

> [VS Code Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) :: Provides awesome icons for VSC.

Material Theme.

### C# / UNITY3D

> [ShaderLab](https://marketplace.visualstudio.com/items?itemName=amlovey.shaderlabvscodefree) :: Unity shaderlab.

> [Shader Languages Support](https://marketplace.visualstudio.com/items?itemName=slevesque.shader) :: Shader languages support.

> [C# XML Doc Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment) :: Generates XML doc comments.

> [Unity Tools](https://marketplace.visualstudio.com/items?itemName=Tobiah.unity-tools)

> [C# Fix Format](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat)

> [Unity Debug](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) :: Debugger extension for Unity.

> [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)

> [C# Support](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)

> [Unity Code Snippets](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets)

> [Unity Snippets](https://marketplace.visualstudio.com/items?itemName=YclepticStudios.unity-snippets)


### GIT

> [GIT Project Manager](https://marketplace.visualstudio.com/items?itemName=felipecaputo.git-project-manager)

> [GIT Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) :: Provides a good way to visualize GIT activity, such as providing GIT data at the ends of lines showing when it was last modified, commit message, etc.

> [GIT History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) :: GIT history, search, log and more.

## **Go forth & code...**