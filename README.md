# Mecromec VS Code Extension Pack

Mecromec VS Code Extension pack is an extension pack for Visual Studio Code made by Kaaris_Moi_Le_Crane.

## Installation (Windows)

1- Download the extension pack [here](https://github.com/KaarisMoiLeCrane/Mecromec-VS-Code-Extension-Pack/raw/main/Mecromec.vsix).

2- Do ``CTRL + SHIFT + X`` (Or click on ``Extensions`` category).

3- Click on ``...``

4- And click on ``Install From VSIX...``

5- Select ``Mecromec.vsix`` extension pack (or annother pack).

6- Do ``CTRL + SHIFT + P`` (Or click on ``View`` then ``Command Palette...``)

7- Search for ``>Preferences: Open Settings (JSON)`` (Or go to File Explorer and open ``settings.json`` file from ``%appdata%\Code\User`` folder)

8- Fill the file with this json code :

```json
{
    "editor.fontLigatures": false,
    "editor.fontSize": 14,
    "editor.minimap.enabled": false,
    "editor.suggestSelection": "first",
    "editor.tabSize": 2,
    "editor.wordWrap": "on",

    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.compactFolders": false,

    "extensions.ignoreRecommendations": true,

    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },

    "git.enableSmartCommit": true,
    "git.autofetch": true,

    "liveServer.settings.donotShowInfoMsg": true,

    "prettier.arrowParens": "avoid",
    "prettier.endOfLine": "auto",
    "prettier.proseWrap": "never",
    "prettier.singleQuote": true,
    "prettier.trailingComma": "all",
    "prettier.useTabs": true,

    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",

    "window.zoomLevel": 1,

    "workbench.activityBar.visible": true,
    "workbench.iconTheme": "moxer-icons",
    "workbench.sideBar.location": "left",
    "workbench.statusBar.visible": true,
    "workbench.tree.indent": 10,

    "zenMode.centerLayout": false,
    "zenMode.hideLineNumbers": false,
}
```

9- Restart VS Code

## License

[MIT](https://choosealicense.com/licenses/mit/)