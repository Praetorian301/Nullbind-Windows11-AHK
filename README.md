# Nullbind-Windows11-AutoHotKey

A universal null-bind script for Windows 11 using AutoHotKey (AHK).

## What this does
This script creates a "null bind" hotkey that intercepts keystrokes or mouse inputs and discards them, so they don’t trigger default Windows actions or in-game binds.  
It’s useful for:
- Creating safe placeholder hotkeys.
- Preventing accidental key presses from doing anything.
- Gaming setups that need a universal “do nothing” bind.

## Features
- Written in AutoHotKey (lightweight, no dependencies).  
- Compatible with Windows 11.  
- Easy to edit: you can change which keys are null-bound.  
- Minimal resource usage.

## Quick Start
1. [Install AutoHotKey](https://www.autohotkey.com/).  
2. Download this repository and open the `.ahk` file.  
3. Double-click the script to run.  
4. To stop the script, right-click the green “H” tray icon and choose **Exit**.

## Example
```ahk
; Example null bind for CapsLock
CapsLock::Return

; Null bind for Mouse Button 5
XButton2::Return
