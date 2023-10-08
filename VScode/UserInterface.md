- [Layout](#layout)
- [Command Palette](#command-palette)
- [Editor](#editor)
  - [Side by side editing](#side-by-side-editing)
  - [Minimap](#minimap)
  - [Indent Guides](#indent-guides)
  - [Breadcrumbs](#breadcrumbs)
  - [Tabs](#tabs)
- [Side Bar](#side-bar)
  - [Explorer](#explorer)
      - [the tree Find control](#the-tree-find-control)
      - [Open Editors](#open-editors)
      - [Outline](#outline)
- [Status Bar](#status-bar)
  - [Language identifier](#language-identifier)
- [Settings](#settings)
  - [Filters](#filters)
  - [settings.json](#settingsjson)
  - [Workspace settings](#workspace-settings)
  - [Language specific editor settings](#language-specific-editor-settings)
  - [Default settings](#default-settings)

---

- [docs](https://code.visualstudio.com/docs)

# Layout

- Editor
- Side Bar
- Status Bar
- Activity Bar
- Panel

> A Secondary Side Bar is also available to display views opposite the Primary Side Bar  
> `Ctrl+Alt+B`

# Command Palette

- `Ctrl+Shift+P` show and run command
- `Ctrl+P` navigate to any file
- `Ctrl+Shift+O` navigate to a specific symbol in a file
- `Ctrl+G` navigate to a specific line in a file

Type `?` get help

# Editor

## Side by side editing

*   `Alt` click on a file in the Explorer
*   Click the **Split Editor** (`Ctrl+\`) button in the upper right of an editor
*   **Open to the Side** (`Ctrl+Enter`) from the Explorer context menu on a file 
*   Drag and drop a file to any side of the editor region
*   `Ctrl+Enter` in the Quick Open (Ctrl+P) file list

you can switch between them quickly by holding the Ctrl key and pressing 1, 2, or 3

and `Ctrl+W` close the active editor

By default, closing the last editor of an editor group will also close the group itself, change this

- `workbench.editor.closeEmptyGroups: false`


## Minimap

settings

- `"editor.minimap.side": "left"`
- `"editor.minimap.enabled": false`

## Indent Guides

- `"editor.guides.indentation":false`
- color
  ```
  "workbench.colorCustomizations": {
      "editorIndentGuide.background": "#0000ff"
  }
  ```

## Breadcrumbs

It shows the current location and allows you to quickly navigate between folders, files, and symbols

settings

- `View > Show Breadcrumbs`

## Tabs

- preview mode

# Side Bar

## Explorer

#### the tree Find control

With the focus on the File Explorer, press `Ctrl+F` to open the tree Find control

Pressing `DownArrow` will let you jump between matching elements

#### Open Editors

manage [Side by side editing](#Side-by-side-editing) quickly 

#### Outline

it will show the symbol tree of the currently active editor


# Status Bar

## Language identifier

Located on the right hand of the Status Bar, bring up the **Select Language Mode**

You can select another language for the current file ( `Ctrl+K M` )

Note that casing matters for exact identifier matching ('Markdown' != 'markdown')

You can add new file extensions to an existing language with the `files.associations` setting


# Settings

- User Settings
- Workspace Settings

`Ctrl+,`

## Filters

- `@ext` - Settings specific to an extension
  - You provide the extension ID such as `@ext:ms-python.python`
- `@id` - Find a setting based on the setting ID.
  - For example, `@id:workbench.activityBar.visible`

## settings.json

opening it with `Preferences: Open User Settings (JSON)` command

you can set `"workbench.settings.editor": "json"`, the keybinding `Ctrl+,` always opens the `settings.json` file and not the Setting editor UI

Depending on your platform, the user settings file is located here:

- Windows `%APPDATA%\Code\User\settings.json`

## Workspace settings

Workspace settings override user settings

`Preferences: Open Workspace Settings (JSON)`

The workspace settings file is located under the `.vscode` folder in your root folder

> A VS Code "workspace" is usually just your project root folder
> 
> Workspace settings are stored at the root in a `.vscode` folder
> 
> You can also have more than one root folder in a VS Code workspace through a feature called [Multi-root workspaces](https://code.visualstudio.com/docs/editor/multi-root-workspaces)

## Language specific editor settings

## Default settings

see a read-only version of the `defaultSettings.json` via `Preferences: Open Default Settings (JSON)`