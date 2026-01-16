# `windows-desktop-switcher` fork
My fork of an AutoHotkey script for Windows that lets a user switch virtual desktops by pressing `win+num` key, among other keybindings. See the original repository for details on customizing configuration, FAQ and credits.

## Setup
[Install AutoHotkey v1.1](https://autohotkey.com/download/1.1/AutoHotkey_1.1.37.02_setup.exe)

You can clone this repo inside your WSL home directory and run it from windows.
```bash
# or ssh if you prefer
git clone https://github.com/tlovell-sxt/windows-desktop-switcher
```

To configure the script to run on startup..
1. navigate to the repository in File Explorer
2. create a shortcut to `desktop_switcher.ahk`
  - right click on file > show more options > Create shortcut
  - you may need to show hidden files in File Explorer to see the shortcut
3. open startup directory: press `win+r` and input `shell:startup`
4. move shortcut to startup directory

## Keybindings cheat sheet

| Key | Action |
| --- | --- |
| `win+num` | go to desktop `num` |
| `win+shift+d` | create new desktop |
| `win+shift+q` | delete current desktop |
| `win+shift+num` | move window to desktop `num` |
| `win+tab` | desktop overview |

*that last one is not part of the script but is worth mentioning*
