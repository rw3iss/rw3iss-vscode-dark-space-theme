# Dark Space Theme

## Example:

### Window Sample:
![alt text](https://github.com/rw3iss/vscode_dark-space-theme/blob/master/screenshots/app.png?raw=true)

### Code Sample:
![alt text](https://github.com/rw3iss/vscode_dark-space-theme/blob/master/screenshots/code.png?raw=true)

### Full Window:
![alt text](https://github.com/rw3iss/vscode_dark-space-theme/blob/master/screenshots/window.png?raw=true)


## Install:

Download and copy this folder to:

~/.vscode/extensions/

Restart VSCode and choose 'Dark Space Theme' from Preferences: Color Theme

&nbsp;
## To apply the Custom UI for window/application styling:

Install CustomizeUI extension.

Add these entries to your User's settings.json:


```
"workbench.colorCustomizations": {
    //"sideBar.background": "#000000",
    "editor.background": "#111"
},

"customizeUI.stylesheet": {
    // Application title bar:
    ".monaco-workbench .part.titlebar": "background: rgb(18,26,32) !important;",

    // Main window background
    ".monaco-workbench": "background-color: #111 !important;",

    // Pane headers in file list:
    ".monaco-pane-view .split-view-view:first-of-type>.pane>.pane-header": "background: rgb(18,26,32) !important",
    ".monaco-pane-view .pane > .pane-header": "background: rgb(18,26,32) !important",

    // Open tabs background:
    ".monaco-workbench .part.editor>.content .editor-group-container>.title": "background: rgb(18,26,32) !important;",
    // Open tab items background:
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.sizing-fit": "background: rgb(28,35,42) !important; box-shadow: 1px 1px 4px rgba(0,0,0,.3) !important;",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.sizing-fit.active": "background: rgb(32,40,50) !important;",
    
    // View container backgrounds (ie. sidebar, open windows):
    ".monaco-split-view2>.split-view-container": "background: rgb(18,26,32); background: linear-gradient(180deg, rgba(18,26,32,1) 0%, rgba(8,18,28,1) 100%);",
    // Some other nice bakground fades:
    //".monaco-split-view2>.split-view-container": "background: rgb(32,34,36); background: linear-gradient(180deg, rgba(32,34,36,1) 0%, rgba(6,14,20,1) 100%);",
    //".monaco-split-view2>.split-view-container": "background: rgb(26,30,37); background: linear-gradient(180deg, rgba(26,30,37,1) 0%, rgba(12,17,24,1) 100%);",

    // sidebar / explorer file list background
    ".monaco-workbench .part.activitybar": "background: none !important;",
    ".monaco-workbench .part.sidebar": "background: none !important;",
    ".monaco-workbench .part>.composite.title": "background: none !important;",
    ".monaco-pane-view .split-view-view:first-of-type>.pane": "background: rgb(10,16,20) !important",
    ".monaco-list.list_id_1 .monaco-list-rows": "background: none !important;",

    // Change width/appearance of line-number, breakpoints, code-folding arrows:
    ".monaco-editor .margin": "background: #111; width: 44px !important;",
    ".monaco-editor .glyph-margin": "width: 0px !important;",
    ".monaco-editor .margin-view-overlays": "width: 44px !important;",
    ".monaco-editor .margin-view-overlays .cgmr": "width: 0px !important; display: none;", // hide breakpoints (I don't use them)
    ".monaco-editor .cldr.codicon.codicon-folding-expanded, .monaco-editor .cldr.codicon.codicon-folding-collapsed": "left: 23px !important; width: 20px !important;",
    ".monaco-scrollable-element.editor-scrollable": "left: 46px !important;",
    ".monaco-editor .margin-view-overlays .line-numbers": "left: 4px !important;",
},

"customizeUI.listRowHeight": 18
```

