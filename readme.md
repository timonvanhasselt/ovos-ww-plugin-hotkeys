## Description

plugin for Keyboard hotkeys, define a key combo to trigger listening

## Install

`pip install ovos_ww_plugin_hotkeys`

Then configure a wake_word with module set to `ovos_ww_hotkeys` in mycroft.conf

```json
 "listener": {
      "wake_word": "hotkey"
 },
 "hotwords": {
    "hotkey": {
        "module": "ovos_ww_hotkeys",
        "hotkey": "space"
    }
  }
 
```


Requirements:
python-evdev (https://python-evdev.readthedocs.io/en/latest/)

 - apt-get install python-dev-is-python3 gcc
 - apt-get install linux-headers-$(uname -r)
 - sudo pip install evdev 

user in ```input``` group

