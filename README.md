# my-windhawk-mods
My mods for Windhawk

## Non Immersive Taskbar Context Menu
This mod restores the non-immersive taskbar context menus.

You can also disable icons in the context menu in the settings of this mod.

**Only works on the Windows 10 taskbar.**

The code is based on [Taskbar-Context-Menu-Tweaker](https://github.com/rikka0w0/Taskbar-Context-Menu-Tweaker).

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/classic-taskbar-context-menu.png)

## Disable Feedback Hub Hotkey
This mod disables the feedback hub (Win+F) hotkey in Windows.

## Disable Immersive Context Menus
This mod disables immersive context menus in file explorer.

This mod applies to explorer folders as well as save/open dialogs in all programs.

Note: This mod disables immersive context menus for *file explorer*, *desktop*, etc.  
For disabling immersive context menus on the *taskbar*, use my [Non Immersive Taskbar Context Menu](https://windhawk.net/mods/classic-taskbar-context-menu) mod.

**Without** this mod:
![Screenshot](https://i.imgur.com/0iRYrCJ.png)

**With** this mod:
![Screenshot](https://i.imgur.com/1bkNHyT.png)

## Disable Navigation Bar
This mod disables the navigation bar in file explorer.

Note: This mod applies to explorer folders as well as save/open dialogs in all programs.

The code is based on the implementation in [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher).

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/disable-navigation-bar.png)

## Disable Office Hotkeys
This mod disables the office hotkeys (Ctrl+Shift+Alt+Win combinations) in Windows.

## Hide Search Bar
This mod removes the search bar in File Explorer.

Note: It expands itself to the right to take place of the search bar that was removed.

The code is based on the implementation in [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher).

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/hide-search-bar.png)

## No Focus Rectangle
Removes the dotted focus rectangle, that it sometimes shown when deselecting files, especially on the desktop. This is appearently an intended feature, but it is pretty annoying.

The code is based on [NoDrawFocusRectW11](https://github.com/NoDrawFocusRectW11/NoDrawFocusRectW11).

This is how the focus rectangle looks like (without this mod):

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/no-focus-rectangle/with_focus_rectangle.png)

This is the focus rectangle removed, with the mod installed:

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/no-focus-rectangle/no_focus_rectangle.png)

## No Hidden Cursor
Some video games will hide your cursor in-game.
This mod will prevent games from hiding your cursor.

### How to enable the mod for a program
In Windhawk, go to the "Advanced" tab and scroll down to
"Custom process inclusion list". In that box, put the filename of the `.exe`.
The mod will immediately apply to those programs after you click "Save".

### Known Issues / Caveats
- This mod makes **no guarantees** of anti-cheat compatibility,
  and has not been tested with any games that use anti-cheat software.

## Shrink Address Bar Height
This mod shrinks the address bar height in file explorer.

Note: This mod applies to explorer folders as well as save/open dialogs in all programs.

The code is based on the implementation in [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher).

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/shrink-address-bar-height.png)

## Windows 7 Command Bar
This mod restores the Windows 7 file command bar in the file explorer.

The code is based on the implementation in [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher).

![Screenshot](https://raw.githubusercontent.com/ItsProfessional/Screenshots/main/Windhawk/win7-command-bar.png)
