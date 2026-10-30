# AviUtl Plugin - Object Explorer

## DISCLAMER: This plugin is not mine!!!, i simply translated it to English and applied some modifications

**This plugin has been translated in favour of the **A.U.T.P. (AviUtl Translation Project)** 

Displays an Explorer window to make aliases, objects, and material files easier to work with.
[Download the latest version](../../releases/latest/)

## Installation

Put the following files and folders into AviUtl's Plugins folder.
* ObjectExplorer.auf
* ObjectExplorer (folder)
* セカンドエクスプローラ.auf (Second Explorer; if you need multiple windows)
* セカンドエクスプローラ (folder) (Second Explorer; if you need multiple windows)

## Changing ExEdit filter name
If you're using a custom **ExEdit** with a different filter name, you can change it's name after running it for the first time in the file called: **ObjectExplorerConfig.ini**.

The file will be located beside the **AviUtl** executable and not the pluugin.

## Usage

### Show the Object Explorer

1. Select "View" → "Show Object Explorer".
2. The Object Explorer is displayed.
3. The Object Explorer can be used almost the same way as a normal Explorer.

### Toggle the tree view on/off

1. Right-click the buttons at the top and select "Show/Hide tree view".

### Enable voice

1. Install [WavPlayer](../../../WavPlayer/).
2. Right-click the buttons at the top and select "Notify by voice" to check it.

### Disable voice

1. Right-click the buttons at the top and select "Notify by voice" to uncheck it.

### Don't use the common dialog

1. Right-click the buttons at the top and select "Use common dialog" to uncheck it.

### Increase the number of windows

1. Make a copy of ObjectExplorer.auf and the ObjectExplorer folder.
2. Rename them to any easily recognizable name (for example, "Third Explorer").

### Register a favorite folder

1. Navigate to the folder you want to register.
2. Right-click the buttons at the top and select "Add to favorites".

### Move to a favorite folder

1. Press the dropdown button of the combo box.
2. Select the folder you want to go to from the dropdown list.

### Move to the folder related to an item

1. Select an item such as a video file on the timeline.
2. Press the "Get" button in the Object Explorer.

### Search (filter)

1. Enter the text you want to search for in the edit box at the upper right.
2. Press the Enter key.

*Note: Folders are not filtered.

### Create an alias file in the Extended Editing window

1. Right-click an item on the timeline and select "Create alias".
2. A normal file selection dialog is displayed instead of Extended Editing's own dialog.
   The folder shown first is the folder currently displayed in the Object Explorer.
3. Save the alias file like a normal file.

### Load an alias file in the Extended Editing window

1. Drag and drop the alias file from the Object Explorer onto the timeline.
2. The file is loaded and an item is generated on the timeline. (This is Extended Editing's normal behavior.)

### Create an alias file in the settings dialog

1. Right-click in the settings dialog and select "Save settings" → "Create alias with current settings".
2. Save the alias file using the same procedure as in the Extended Editing window.

### Load an alias file in the settings dialog

1. Drag and drop the alias file from the Object Explorer onto the settings dialog.
2. The multiple filters contained in the alias file are applied to the selected item.

## Configuration

Edit ObjectExplorerSettings.xml with a text editor.

## Changelog

* 3.6.2 - 2026/10/30 Added **ExEdit** filter name change with a config file and changed AviUtlInternals.h with a custom one to make it work.
* 3.6.1 - 2023/02/21 Fixed an issue where an error message appeared when WavPlayer was not present
* 3.6.0 - 2023/02/16 Adjusted shutdown processing to match SplitWindow
* 3.5.0 - 2023/01/10 Added search (filtering) feature
* 3.4.0 - 2023/01/07 Changed sounds to play in an external process
* 3.3.0 - 2022/08/31 Added an option to choose whether to use the common dialog
* 3.2.1 - 2022/08/02 Fixed errors in the documentation
* 3.2.0 - 2022/07/28 Made it possible to display multiple Explorers
* 3.1.0 - 2022/07/26 Made it possible to toggle the tree view on/off
* 3.0.1 - 2022/07/10 Fixed display settings so they persist
* 3.0.0 - 2022/06/26 Changed external process dialogs to child windows
* 2.2.0 - 2022/05/30 Adapted to specification changes in DarkenWindow
* 2.1.0 - 2022/05/13 Fixed to load DarkenWindow.aul if it exists
* 2.0.2 - 2022/05/12 Fixed an issue where aliases could not be saved for certain object names
* 2.0.1 - 2022/05/05 Fixed an issue where default processing was not executed on drag and drop in the settings dialog
* 2.0.0 - 2022/05/05 Refactoring
* 1.0.0 - 2022/04/05 Initial release

## Tested Environment

* (Required) AviUtl 1.10 & Extended Editing 0.92 http://spring-fragrance.mints.ne.jp/aviutl/
* (Coexistence confirmed) patch.aul r42 https://scrapbox.io/ePi5131/patch.aul

## Credits

* Microsoft Research Detours Package https://github.com/microsoft/Detours
* aviutl_exedit_sdk https://github.com/ePi5131/aviutl_exedit_sdk
* Common Library https://github.com/hebiiro/Common-Library
* VOICEVOX https://voicevox.hiroshiba.jp/
* VOICEVOX: Aoyama Ryusei

## Author Information

* Author - Hebiiro (蛇色)
* GitHub - https://github.com/hebiiro
* Twitter - https://twitter.com/io_hebiiro

## Disclaimer

Neither I, my associates, nor any group or organization I belong to accepts any responsibility for any failure, damage, or malfunction resulting from the use of this work or its bundled files. Please use it at your own risk.
