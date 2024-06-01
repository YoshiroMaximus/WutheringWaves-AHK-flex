# WutheringWaves AHK flex v1.3

AHK script for Wuthering Waves.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/poIhc7r3EX4/0.jpg)](https://www.youtube.com/watch?v=poIhc7r3EX4)

⬆️Click on the picture⬆️

👀 Below there is a detailed description!!!

🙏 Using scripts may lead to account blocking, use at your own risk.

__🚀Functional:🚀__

- Skip dialogues
- Fastlut
- Map
- Overlay
- Macros:
 +Za warudo
 + AutoAttack
 + Chixia rage
 + Shift Spam
 + Sanhua hold
 + Auto pistols
 +EncoreN1
 +RoverHavocN1
 +DanjinE1
 + High jump
- Tray menu:
 + Edit settings
 + Semi-automatic update
 + Manual import of settings
 + Create a shortcut

:musical_keyboard:__Hot keys:__:musical_keyboard:
```
End - Finish work
Yo - *Za warudo (Description*)
F1 - Overlay
F2 - Map
F - Fastlut
Z - Skip dialogue
V - Macro Key
Numpad 0 - Off
Numpad 1 - AutoAttack
Numpad 2 - Chixia rage
Numpad 3 - Shift Spam
Numpad 4 - Sanhua hold++
Numpad 5 - Auto pistols
Numpad 6 - *EncoreN1 (Description*)
Numpad 7 - *RoverHavocN1 (Description*)
Numpad 8 - *DanjinE1 (Description*)
Numpad 9 - High jump (Hook + Any swordsmen)
```

<details>
<summary> 🛠️ Settings 🛠️ </summary>

Or search for cfg "WWFlex\data\Config.ini"

Or through the menu "Tray menu => Edit Config"

```
;================Hot keys
; You can use regular key names.
; https://www.autohotkey.com/docs/v1/KeyList.htm
; But it is recommended to use virtual or scan codes
; Where can I get them? Google or run WWFlex\data\debug\VirtualCodeKeys.ahk
Key_ZaWarudo=vkC0
Key_RUltiDefault=vk51
Key_ESkillDefault=vk45
Key_RelicDefault=vk54
key_Overlay=F1
key_Map=F2
key_Macro=V
key_SkipNPC=Z
key_Fastlyt=F
key_EndExitapp=End
key_PauseSuspend=Del
key_Reload=Home
key_LabelNumpad0=Numpad0
key_LabelNumpad1=Numpad1
key_LabelNumpad2=Numpad2
key_LabelNumpad3=Numpad3
key_LabelNumpad4=Numpad4
key_LabelNumpad5=Numpad5
key_LabelNumpad6=Numpad6
key_LabelNumpad7=Numpad7
key_LabelNumpad8=Numpad8
key_LabelNumpad9=Numpad9
;================On-off
Checkbox_Overlay=1
Checkbox_Map=1
Checkbox_Macro=1
Checkbox_SkipNPC=1
Checkbox_Fastlyt=1
Checkbox_PauseSuspend=0
Checkbox_Reload=1
;================Other
RoverHavocTime1=60
EncoreTime1=43
SelectDefaultMacro=2
SkipNPCLockMode=1
BhopDelayIn=100
FastlytFastMode=1
FastlytDelayIn=130
MapRunUrl=https://genshin-impact-map.appsample.com/wuthering-waves-map
WindowFocus=ahk_class UnrealWindow
```

</details>

<details>
<summary>:memo:How to run?::memo:</summary>

1. Download and install [Autohotkey.com](https://www.autohotkey.com/download/ahk-install.exe)

 "Custom installation" => "Unicode 64" => All checkboxes => "Install"
![hippo](https://media.giphy.com/media/LerrohpjasApOHH9G1/giphy.gif)

2. Download the repository (Code > [Download Zip👌](https://github.com/Kramar1337/WutheringWaves-AHK-flex/archive/main.zip))

3. Launch "WWFlex.ahk"

</details>

<details>
<summary>📃 Detailed description 📃</summary>

# Tray menu (this is where the clock lives)

Edit Config - opens the settings file "data\Config.ini"

Import Settings - manual import of settings

Force Update - forcibly downloads files from Github, unpacks and imports settings. Before use, disable your antivirus or add it to an exception.

Create AHK shortcut - Create a shortcut on the desktop

# Macros

`(Ё) - Za warudo. Stops time. The first step is to configure the "data\Config.ini" parameter "Key_RUltiDefault" - the button on which your ultimate ability is activated.

Z - Skip dialogues.

There are 2 modes. Switching to "data\Config.ini" parameter "SkipNPCLockMode"

1 - Automatic mode, press “Z” and the script skips until the cursor disappears or you press “Z” again.

0 - Manual mode. The script skips while the key is pressed.

F1 - Overlay

Left - switch overlay

Right - switch overlay

F2 - Map

The first click opens the map; if there is no map, it launches the default browser and the map registered in the settings. Pressing it again will expand the game. "data\Config.ini" parameter "MapRunUrl" link to the map. The names of the windows on which the script will focus its attention are written in "data\GroupNameMap.txt"

F - Fastlut.

You hold down "F" and the script spams "F". There are 2 modes. Switching to the "data\Config.ini" parameter "FastlytFastMode", the delay before triggering "FastlytDelayIn" is also adjusted

1 - Fast mode. Adds wheel down spam. Also moves the camera away. But in this game, unlike GI, it is impossible to collect loot instantly. Game\server delay.

0 - Normal mode.

V - Macro Key.

Activates the macro. Selected below. In "data\Config.ini" the parameter "SelectDefaultMacro" selects the active default macro.

Numpad 0 - Off - disable.

Numpad 1 - AutoAttack - Spam auto attacks.

Numpad 2 - Chixia rage - Abuses the aiming animation, Chixia shoots very quickly.

Numpad 3 - Shift Spam - Spam Shift

Numpad 4 - Sanhua hold++ - Presses the hold of the poke in timing.

Numpad 5 - Auto pistols - Fast shooting with any pistols, not suitable for fights, only for puzzles.

Numpad 6 - *EncoreN1

Numpad 7 - *RoverHavocN1

Numpad 8 - *DanjinE1

*Get to Adventure Rank 25, complete the entire quest "Stygian Lacrimos"
Changes: 05/28/2024

 - Tweaking skip dialogues
 - Chisi twist for the brow
 - Overlay with information

Changes: 05/26/2024

 - Tweaking the fastloot
 - Numpad 5 - Auto pistols
 - Sanhua hold++
 - Esc - Interrupt the stuck thread
 - Settings opener in the tray menu
 - Transferring settings to config
 - Import settings to tray menu
 - Updater in the tray menu

Changes: 05/25/2024

 - Timing tweaks
 - Bind to card
 - Numpad 4 - Sanhua hold


Changes: 05/22/2024

 - A start
 - T - Web spam
 - F - Fastlut
 - Z - Skip dialogues
 - V - Macro Key
 - Numpad 0 - Off
 - Numpad 1 - AutoAttack
 - Numpad 2 - Chixia rage
 - Numpad 3 - Bhop

</details>
