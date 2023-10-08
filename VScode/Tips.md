- [Tips and Tricks](#tips-and-tricks)
  - [Quick Open](#quick-open)
  - [Customization](#customization)
      - [theme](#theme)
      - [keyboard shortcuts](#keyboard-shortcuts)
  - [Editing hacks](#editing-hacks)
      - [Multi cursor selection](#multi-cursor-selection)
      - [Box selection](#box-selection)
      - [Fast scrolling](#fast-scrolling)
      - [Select/Move/Copy line](#selectmovecopy-line)
      - [Undo cursor position](#undo-cursor-position)
      - [Trim trailing whitespace](#trim-trailing-whitespace)
      - [Code formatting](#code-formatting)
      - [Code folding](#code-folding)
  - [IntelliSense](#intellisense)
  - [Snippets](#snippets)

---

# Tips and Tricks

`Help > Welcome`

## Quick Open

Keyboard Shortcut: `Ctrl+P`

- quickly open files
- `the Right arrow` key open the currently selected file in the background

Keyboard Shortcut: `Ctrl+R`

- navigate between recently opened folders

## Customization

- Change your theme
- Change your keyboard shortcuts
- Tune your settings
- Install extensions
- Add JSON validation
- Create snippets

#### theme

Keyboard Shortcut: `Ctrl+K Ctrl+T`

Additionally, you can install and change your File Icon themes

#### keyboard shortcuts

Keyboard Shortcut: `Ctrl+K Ctrl+S`

You can search for shortcuts and add your own keybindings to the `keybindings.json` file

## Editing hacks

#### Multi cursor selection

`Alt+Click`

- add additional cursors to all occurrences of the current selection with `Ctrl+Shift+L`
- use `Ctrl+D` selects the next occurrence after the one you selected

#### Box selection

You can select blocks of text by holding `Shift+Alt` while you drag your mouse

A separate cursor will be added to the end of each selected line

#### Fast scrolling

Pressing the `Alt` key enables fast scrolling in the editor

By default, fast scrolling uses a 5X speed multiplier but you can control the multiplier with `editor.fastScrollSensitivity`

#### Select/Move/Copy line

Keyboard Shortcut: `Ctrl+L`

Keyboard Shortcut: `Alt+Up/down`

Keyboard Shortcut: `Shift+Alt+Up/down`

#### Undo cursor position

Keyboard Shortcut: `Ctrl+U`

#### Trim trailing whitespace

Keyboard Shortcut: `Ctrl+K Ctrl+X`

#### Code formatting

Currently selected source code: `Ctrl+K Ctrl+F`

Whole document: `Shift+Alt+F`

#### Code folding

Keyboard Shortcut: `Ctrl+Shift+[/]` 

You can also fold/unfold all regions in the editor with `Fold All` and `Unfold All`

## IntelliSense

`right click` to open a context menu

- Peek
- Go to Definition
  - press `Ctrl` when you are hovering over the symbol
  - You can go back to your previous location with the `Go > Back` command or `Alt+Left`
- Go to References ??
- Find All References view
- Rename Symbol

## Snippets

Create custom snippets `File > Preferences > Configure User Snippets`

See more details in [Creating your own Snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets)