---

# **Nullbind-Windows11-AutoHotKey**

A **universal null-bind script** for **Windows 11** built with **AutoHotKey (AHK)**.
Designed for gamers, power users, and productivity setups that need a safe “do-nothing” hotkey or a way to intercept inputs without triggering default Windows or in-game actions.

---

## 🧩 **What This Does**

This script creates a **null bind** hotkey that intercepts keystrokes or mouse inputs and discards them — meaning the key press performs no action at all.
Perfect for:

* Creating **safe placeholder hotkeys**.
* Preventing accidental input from performing system actions.
* Configuring **universal dummy binds** in games or automation setups.

---

## ⚙️ **Features**

* Written entirely in **AutoHotKey** — lightweight, no dependencies.
* Compatible with **Windows 11**.
* Easy to edit — customize which keys or buttons are null-bound.
* Minimal resource usage; runs silently in the tray.

---

## 🚀 **Quick Start**

1. Install [AutoHotKey](https://www.autohotkey.com/).
2. Download this repository and open `nullbind.ahk`.
3. Double-click the script to run it.
4. To stop the script, right-click the green **H** tray icon → **Exit**.

---

## 💡 **Example Usage**

```ahk
; Example null bind for Caps Lock
CapsLock::Return

; Example null bind for Mouse Button 5
XButton2::Return
```

You can add or remove lines as needed to match your device layout or preferences.

---

## 🧠 **Customization**

Open `nullbind.ahk` in any text editor (Notepad, VS Code, etc.) and edit the key mappings.
Each hotkey line follows the pattern:

```
<Key>::Return
```

For example:

* `CapsLock::Return` → disables Caps Lock.
* `XButton2::Return` → disables your mouse side button.

You can map any key combination supported by AutoHotKey (e.g., `Ctrl + Q`, `Alt + 1`, `F13`, etc.).

---

## ⚙️ **Notes**

* Works globally across all Windows apps.
* Uses negligible CPU and memory.
* Start minimized or add to your Windows Startup folder for persistent use.

---

## 📂 **Folder Layout**

```
Nullbind-Windows11-AHK/
│
├── nullbind.ahk
└── README.md
```

---

👤 **Created by [@Praetorian301](https://github.com/Praetorian301)**

---
