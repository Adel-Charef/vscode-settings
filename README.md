# VS Code Settings

All of the themes / plugins / extensions / settings I use for VSCode. 


## Themes/Color

* Current theme:
  * [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)
* This is a cool theme also:
  * [Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)


## Icons

* Current Icons:
  * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)


## Extensions

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag.
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag.
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.


## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element.
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements.
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames.


## Style/Formatting/Linting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS.
* [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.

    ### For Python:
      * [black](https://github.com/psf/black)

      * [Pylint](https://pylint.org/) 


## Extensions for Frontend

* [JavaScript Code Snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  * Code snippets for JavaScript in ES6 syntax.
* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling.
* [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
  * Compile Sass or Scss to CSS at realtime with live browser reload.
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  * Compile Sass or Scss to CSS at realtime with live browser reload.
* [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
  * Simple extensions for React, Redux and Graphql in JS/TS with ES7 syntax.
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Code formatter using prettier.


## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package.
* [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
  * Automatically finds, parses and provides code actions and code completion for all available imports. Works with Typescript and TSX.
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Evaluate code/logs inline and show results in the editor.
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code.
* [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  * Makes it easy to create, manage, and debug containerized applications.
* [Dotenv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
  * Support for dotenv file syntax.
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * Language support for .gitignore files. Lets you pull .gitignore files from the https://github.com/github/gitignore repository.
* [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
  * All-language autocompleter — TabNine uses machine learning to help you write code faster.
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * Show TODO, FIXME, etc. comment tags in a tree view


## Python

* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  * Linting, Debugging (multi-threaded, remote), Intellisense, Jupyter Notebooks, code formatting, refactoring, unit tests, snippets, and more.
* [AREPL for python](https://marketplace.visualstudio.com/items?itemName=almenon.arepl)
  * AREPL automatically evaluates python code in real-time as you type.
* [Python Test Explorer](https://marketplace.visualstudio.com/items?itemName=LittleFoxTeam.vscode-python-test-adapter)
  * Run your Python tests in the Sidebar of Visual Studio Code
* [Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)
  * Automatically generates detailed docstrings for python functions.
* [Django](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)
  * Beautiful syntax and scoped snippets for perfectionists with deadlines.


# Settings

```json
{
  "explorer.openEditors.visible": 0,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "workbench.colorTheme": "Just Black",
  "window.zoomLevel": 0,
  "workbench.iconTheme": "vscode-icons",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 20,
  "files.autoSave": "afterDelay",
  "markdown.preview.fontSize": 36,
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.minimap.enabled": false,
  "liveshare.featureSet": "insiders",
  "liveshare.anonymousGuestApproval": "accept",
  "editor.lineHeight": 0,
  "editor.fontSize": 22,
  "python.formatting.provider": "black",
  "python.linting.mypyEnabled": true,
  "python.linting.pylintArgs": ["--load-plugins=pylint_django"],
  "python.analysis.logLevel": "Trace",
  "python.showStartPage": false,
  "editor.formatOnSave": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "terminal.integrated.inheritEnv": false,
  "vsicons.dontShowNewVersionMessage": true,
  "eslint.enable": true,
  "beautify.config": {
    "css": {
      "indent_size": 2
    },
    "indent_char": " ",
    "indent_size": 4,
    "js": {
      "indent_size": 2,
      "space_after_anon_function": true,
      "space_after_named_function": true,
      "space_before_conditional": true,
      "space_in_paren": false
    }
  },
  "beautify.language": {
    "css": ["sass", "scss"],
    "html": ["htm", "html", "django-html"]
  },
  "bracketPairColorizer.activeScopeCSS": [
    "backgroundColor : {color}",
    "borderStyle : solid",
    "borderWidth : 1px",
    "borderColor : {color}; opacity: 0.5"
  ],
  "bracketPairColorizer.forceIterationColorCycle": true,
  "bracketPairColorizer.forceUniqueOpeningColor": true,
  "bracketPairColorizer.highlightActiveScope": true,
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "[javascript]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[json]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[html]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[css]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorCustomizations": {},
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["comment", "comment.block"],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },
  "todo-tree.tree.showScanModeButton": false,
  "cSpell.enableFiletypes": [
    "asciidoc",
    "c",
    "cpp",
    "csharp",
    "css",
    "git-commit",
    "go",
    "handlebars",
    "haskell",
    "html",
    "jade",
    "java",
    "javascript",
    "javascriptreact",
    "json",
    "jsonc",
    "latex",
    "less",
    "markdown",
    "php",
    "plaintext",
    "pug",
    "python",
    "restructuredtext",
    "rust",
    "scala",
    "scss",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ],
  "cSpell.userWords": [
    "deno",
    "feathersjs",
    "middlewares",
    "socketio",
    "upsert",
    "upvote",
    "Beeblebrox",
    "CloudFormation",
    "Dalek",
    "FIPS",
    "Makefiles",
    "NIST",
    "Neopets",
    "OWASP",
    "POSIX",
    "Pipfile",
    "YAGNI",
    "anonymize",
    "anonymized",
    "asynchronicity",
    "autoremove",
    "boto",
    "botocore",
    "caffeination",
    "canonicalization",
    "changelogs",
    "commoditized",
    "cybersecurity",
    "distro",
    "dotfiles",
    "executables",
    "fooey",
    "gofakeit",
    "isort",
    "markdownlint",
    "multifactor",
    "pentesting",
    "performant",
    "pipenv",
    "postgres",
    "powerline",
    "prepend",
    "printf",
    "pylint",
    "pytest",
    "pytz",
    "readfile",
    "reassociated",
    "rebased",
    "repos",
    "shortcode",
    "shortcodes",
    "soteria",
    "stateful",
    "strcat",
    "strcpy",
    "struct",
    "stubber",
    "subproblems",
    "templating",
    "tinymce",
    "treehouse",
    "underuse",
    "unencrypted",
    "unintuitive",
    "vaporwave",
    "wirelessly"
  ],
}
```
