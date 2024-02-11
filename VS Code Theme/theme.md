# VS Code Theme For me

```JSON
//Theme By Kiran Ghorpade

    "editor.fontFamily": "MonoLisa, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 12,

    "workbench.colorCustomizations": {

        // "editor.background": "#22272e",
        //sidebar 
        "sideBar.border": "#0000",
        "sideBar.background": "#191d1f",
        "sideBarSectionHeader.background": "#2a3134",

        //editor widget
        "editorWidget.border": "#0003",

        //activity bar
        "activityBar.background": "#191d1f",
        "activityBar.border": "#0001",
        "activityBar.activeBorder": "#0055ff",

        //titlebar
        "titleBar.border": "#0001",
        "titleBar.activeBackground": "#191d1f",


        //path or breadcrumb
        "breadcrumb.background": "#121517",

        //statusbar
        "statusBar.background": "#191d1f",
        "statusBar.border": "#0003",

        //tab
        "tab.activeBorder": "#0f1617",
        "tab.hoverBorder": "#0f1617",
        "tab.inactiveBackground": "#191d1f00",
        "tab.unfocusedActiveBorder": "#0f1617",
        "tab.activeBackground": "#0f1617",
        "tab.hoverBackground": "#0f1617",
        "tab.border": "#191d1f",
        
        //editor
        "editor.background": "#0f1617",
        "editorGroupHeader.tabsBackground":"#191d1f",
        "editorGroupHeader.border": "#0003",
        "editorGroupHeader.tabsBorder": "#0003",

        //focusBorder
        "focusBorder":"#3b474a",

        //terminal
        "panel.background": "#0b0d0e",
        "panel.border": "#0004",
        "panelTitle.activeBorder": "#0055ff",
    },

    "workbench.iconTheme": "material-icon-theme",
    "terminal.integrated.fontSize": 12,
```


# VSCode Setting Configuration For me

**settings.json**
```json
{
    "debug.terminal.clearBeforeReusing": true,
    "code-runner.runInTerminal": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "explorer.confirmDragAndDrop": false,
    // "security.workspace.trust.untrustedFiles": "open",
    "redhat.telemetry.enabled": false,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
    },
    "liveServer.settings.donotVerifyTags": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "powermode.presets": "fireworks",
    "window.zoomLevel": 1,
    "java.configuration.runtimes": [


    ],
    "code-runner.executorMap": {

        "javascript": "node",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "zig": "zig run",
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "php": "php",
        "python": "python -u",
        "perl": "perl",
        "perl6": "perl6",
        "ruby": "ruby",
        "go": "go run",
        "lua": "lua",
        "groovy": "groovy",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "bat": "cmd /c",
        "shellscript": "bash",
        "fsharp": "fsi",
        "csharp": "scriptcs",
        "vbscript": "cscript //Nologo",
        "typescript": "ts-node",
        "coffeescript": "coffee",
        "scala": "scala",
        "swift": "swift",
        "julia": "julia",
        "crystal": "crystal",
        "ocaml": "ocaml",
        "r": "Rscript",
        "applescript": "osascript",
        "clojure": "lein exec",
        "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
        "rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
        "racket": "racket",
        "scheme": "csi -script",
        "ahk": "autohotkey",
        "autoit": "autoit3",
        "dart": "dart",
        "pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
        "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
        "haskell": "runghc",
        "nim": "nim compile --verbosity:0 --hints:off --run",
        "lisp": "sbcl --script",
        "kit": "kitc --run",
        "v": "v run",
        "sass": "sass --style expanded",
        "scss": "scss --style expanded",
        "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
        "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "sml": "cd $dir && sml $fileName"
    },
    "[java]": {

        "editor.suggest.snippetsPreventQuickSuggestions": false
    },
    "files.associations": {
        "*.java": "java",
        "*.cpp": "cpp"
    },
    "boot-java.common.properties-metadata": "",
    "rapidapi.terminalLink.enabled": false,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "[cpp]": {

        "editor.wordBasedSuggestions": "off",
        "editor.suggest.insertMode": "replace",
        "editor.semanticHighlighting.enabled": true
    },
    "files.autoSave": "afterDelay",
    "workbench.editorAssociations": {
        "*.pdf": "default"
    },
    "editor.fontFamily": "MonoLisa, Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 12,

    //Theme By Kiran Ghorpade
    "workbench.colorCustomizations": {

        // "editor.background": "#22272e",
        //sidebar 
        "sideBar.border": "#0000",
        "sideBar.background": "#191d1f",
        "sideBarSectionHeader.background": "#2a3134",

        //editor widget
        "editorWidget.border": "#0003",

        //activity bar
        "activityBar.background": "#191d1f",
        "activityBar.border": "#0001",
        "activityBar.activeBorder": "#0055ff",

        //titlebar
        "titleBar.border": "#0001",
        "titleBar.activeBackground": "#191d1f",


        //path or breadcrumb
        "breadcrumb.background": "#121517",

        //statusbar
        "statusBar.background": "#191d1f",
        "statusBar.border": "#0003",

        //tab
        "tab.activeBorder": "#0f1617",
        "tab.hoverBorder": "#0f1617",
        "tab.inactiveBackground": "#191d1f00",
        "tab.unfocusedActiveBorder": "#0f1617",
        "tab.activeBackground": "#0f1617",
        "tab.hoverBackground": "#0f1617",
        "tab.border": "#191d1f",
        
        //editor
        "editor.background": "#0f1617",
        "editorGroupHeader.tabsBackground":"#191d1f",
        "editorGroupHeader.border": "#0003",
        "editorGroupHeader.tabsBorder": "#0003",

        //focusBorder
        "focusBorder":"#3b474a",

        //terminal
        "panel.background": "#0b0d0e",
        "panel.border": "#0004",
        "panelTitle.activeBorder": "#0055ff",
    },

    "workbench.iconTheme": "material-icon-theme",
    "terminal.integrated.fontSize": 12,
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
        "hello": {
            "path": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe"
        }
    },
    "terminal.integrated.defaultProfile.windows": "Command Prompt",
}
```