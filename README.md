# remap-fr

Fix the <> keys on a QWERTY keyboard with a French layout

## The Problem

When Windows is set to a **French (FR) keyboard layout**, the key positions are remapped for AZERTY. But if you're physically typing on a **QWERTY keyboard**, certain symbols become hard or impossible to type, because the keys don't match what Windows expects.

This script fixes that with simple shortcuts.

## What it does

| Shortcut | Output |
|----------|--------|
| `Ctrl + ,` | `<` |
| `Ctrl + ;` | `>` |

## Requirements

- **Windows** (tested on Windows 10/11)
- **[AutoHotkey v1.x](https://www.autohotkey.com/)** installed

## Getting Started

1. Install [AutoHotkey](https://www.autohotkey.com/)
2. Download or clone this repo
3. Double-click the `.ahk` script to run it
4. The script runs silently in the background (check your system tray)

To run it **automatically on startup**:
- Press `Win + R`, type `shell:startup`, press Enter
- Drop a shortcut to the `.ahk` file in that folder


## Why Not Just Switch Layouts?

Switching back and forth between FR and EN layouts constantly is annoying, This script lets you stay on FR while still being able to type symbols that are awkward on a QWERTY-as-AZERTY setup.

I personally use it to do <> in C++ because before I couldn't.

Another useless repo I made <3 sorry.
