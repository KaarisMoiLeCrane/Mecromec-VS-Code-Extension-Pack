# Mecromec VS Code Extension Pack

Mecromec VS Code Extension pack is an extension pack for Visual Studio Code made and used by Kaaris_Moi_Le_Crane.

## Extensions included

- [📦 .gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)
  - Generate .gitignore file using gitignore.io API.
- [📦 Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  - Human-friendly comments in your code.
- [📦 Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.bookmarks)
  - Mark lines and jump to them.
- [📦 Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  - A customizable extension for colorizing matching brackets.
- [📦 C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
  - C/C++ IntelliSense, debugging, and code browsing.
- [📦 carbon-now-sh](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)
  - A Code package to open the current editor content in carbon.now.sh.
- [📦 Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  - Run C, C++, Java, JS, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, CMD, BASH, F#, C#, VBScript, TypeScript, CoffeeScript, Scala, Swift, Julia, Crystal, OCaml, R, AppleScript, Elixir...
- [📦 Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
  - Highlight web colors in your editor.
- [📦 CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  - Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.
- [📦 DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
  - Support for dotenv file syntax.
- [📦 Error lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
  - Improve highlighting of errors, warnings and other language diagnostics.
- [📦 ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - Integrates ESLint JavaScript into VS Code.
- [📦 Formatting Toggle](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle)
  - A VS Code extension that allows you to toggle the formatter (Prettier, Beautify, …) ON and OFF with a simple click.
- [📦 Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)
  - An extension for more guide lines.
- [📦 HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
  - CSS Intellisense for HTML
- [📦 Icon Fonts](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts)
  - Snippets for popular icon fonts such as Font Awesome, Ionicons, Glyphicons, Octicons, Material Design Icons and many more!
- [📦 Intellisense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=zignd.html-css-class-completion)
  - CSS class name completion for the HTML class attribute based on the definitions found in your workspace.
- [📦 JavaScript (ES6) Code snippets](https://marketplace.visualstudio.com/items?itemName=alefragnani.bookmarks)
  - Code snippets for JavaScript in ES6 syntax.
- [📦 Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
  - Java Linting, Intellisense, formatting, refactoring, Maven/Gradle support and more...
- [📦 Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.liveserver)
  - Launch a development local Server with live reload feature for static & dynamic pages.
- [📦 Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
  - All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).
- [📦 Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
  - Convert Markdown to PDF.
- [📦 Material Icon Theme](https://marketplace.visualstudio.com/items?pkief.material-icon-theme)
  - Material Design Icons for Visual Studio Code.
- [📦 Moxer Icons](https://marketplace.visualstudio.com/items?itemName=equinusocio.moxer-icons)
  - Moxer Icons, the epic icons companion for Moxer Theme.
- [📦 npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense).
  - Visual Studio Code plugin that autocompletes npm modules in import statements
- [📦 Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  - Visual Studio Code plugin that autocompletes filenames.
- [📦 PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.powershell)
  - Develop PowerShell scripts in Visual Studio Code!
- [📦 Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - Code formatter using prettier.
- [📦 Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)
  - Regex matches previewer for JavaScript, TypeScript, PHP and Haxe in Visual Studio Code.
- [📦 Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  - Open any folder or repository inside a Docker container and take advantage of Visual Studio Code's full feature set.
- [📦 Shell launcher](https://marketplace.visualstudio.com/items?itemName=tyriar.shell-launcher)
  - Easily launch multiple shell configurations in the terminal.
- [📦 Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=visualstudioexptteam.vscodeintellicode)
  - AI-assisted development.

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
