# Expanded Gridmenu for BAR
Expand your Grid menu from 3x4 panel to 3x6 grid menu panel for BAR (Beyond All Reason)! 

This widget is to help alleviate the 2nd page unit syndrome, where units get forgotten for just being on the 2nd page of factory/build menus.

> [!NOTE]
> Still a WIP to make a toggable option to switch between Grid menu & Expanded Grid menu in Custom settings.

![armt2botlab3x6menu](https://github.com/user-attachments/assets/81194621-93ee-483b-8268-36435c8f8421)

# Features
Expands the Grid menu panel from 3x4 to 3x6 panel to allow an extra 6 slot visibility in grid menu.

# Known Issue
- You will have to delete/move `gui_gridmenu.lua` out of the `Widgets` folder,
- Also delete/move `gridmenu_layout.lua` & `gridmenu_config.lua` out of the `Configs` folder, to go back to `3x4 Grid menu panel.`

# Installation Guide
1. Download [Gridmenu_config.lua](https://github.com/DMikey86/BAR-Widgets/blob/main/Expanded_Gridmenu/Configs/gridmenu_config.lua), [Gridmenu_layout.lua](https://github.com/DMikey86/BAR-Widgets/blob/main/Expanded_Gridmenu/Configs/gridmenu_layouts.lua), [Gui_gridmenu.lua](https://github.com/DMikey86/BAR-Widgets/blob/main/Expanded_Gridmenu/Widgets/gui_gridmenu.lua) and [uikeys.txt](https://github.com/DMikey86/BAR-Widgets/blob/main/Expended_Girdmenu/uikeys.txt) files.
2. Create another folder inside <ins>**LuaUI**</ins> folder call `Configs` image below for context.
3. Paste `gridmenu_config.lua` & `gridmenu_layout.lua` into your `/Beyond-All-Reason/data/LuaUI/Configs/` folder
4. Paste `gui_gridmenu.lua` inside your `/Beyond-All-Reason/data/LuaUI/Widgets/` folder
5. Paste `uikeys.txt` into your `/Beyond-All-Reason/data/` folder
6. Launch Beyond-All-Reason

# LuaUI Folder setup
 ![LuaUI_folder](https://github.com/user-attachments/assets/f538837c-9f8b-4222-bb3d-76fa086cf97a)

# In-game Settings Setup
1. Start a Skirmish game
2. Open <ins>**Settings**</ins> make sure `Advanced` is selected.
3. Under `Custom` tab enable `Grid menu` widget
4. Under `Control` tab and **<ins>Hotkeys</ins>** heading,
5. Enable `Custom` in Keybind Preset
6. Toggle `Use Gridmenu`
7. Toggle `Factory build mode hotkeys`
8. You can now play with the new Expanded Gridmenu.

> [!NOTE] 
> You can adjust size via the in-game setting under `Interface tab` by adjusting the `Interface Scale`

# Hotkey Setup image
![Control_Hotkeys](https://github.com/user-attachments/assets/94ecac7c-6479-41e0-8f0c-f1de8f30c59a)

# In-game Setting Advanced Window image
![settings](https://github.com/user-attachments/assets/d45cc7f8-5a14-4aeb-9c54-cec43124992b)
