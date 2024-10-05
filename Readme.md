## BT Shortcut for Windows

- This is an autohotkey shortcut for Windows to open windows BT menu directly with a shortcut.
- The script involves the following code

  ```
  ^k::
  Run, ms-settings:connecteddevices
  Return
  ```
> The above block of code is present in the "BTShortcut.ahk" file.

- The ^k refers to Ctrl + K as the shortcut to access the bluetooth menu. However this can be changed to whatever you like by editing the "BTShortcut.ahk" file.

### Steps to get the shortcut working 
1. Download & Install [AutoHotkey](https://www.autohotkey.com/) version 2.0
2. Save the "BTShortcut.ahk" file in Documents > Autohotkey directory.
3. Double click on or run the "BTShortcut.ahk" file.
4. You're good to use the shortcut to access the bluetooth menu.

- This can be extended to other menus and action as well, just need to change the app to be run in the second line of the code. 

