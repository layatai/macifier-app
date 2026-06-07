# Macifier

Bring your Mac keyboard muscle memory to Windows. Macifier remaps the keyboard so
`⌘C` / `⌘V`, app switching, word navigation, a clipboard manager and Mac-style
screenshots work the way they do on macOS — one lightweight tray app, no scripts.

## Download

Grab the latest installer from the **[Releases page](https://github.com/layatai/macifier-app/releases/latest)**
or from **[macifier.com](https://macifier.com)**. Requires Windows 10 or 11.

| Edition | What you get |
|---|---|
| **Free** | Fully featured: Alt↔Ctrl swap, copy/paste, clipboard manager, window switcher, Mac screenshots, word navigation, terminal-aware Ctrl, tray + light/dark themes. |
| **Pro** | Everything in Free, plus a signed installer, automatic in-app updates, priority support, and an upcoming Monosnap-style markup editor. Activate with the license key from your purchase via the tray menu. |

## Features

- **Alt ↔ Ctrl swap** — Alt acts like Command (⌘), Ctrl like Option (⌥), matching macOS.
- **macOS copy/paste** — `Alt + C` / `Alt + V` map to Copy / Paste.
- **Clipboard manager** — `Alt + Shift + V` opens clipboard history (text and images).
- **Window switcher** — `Alt + \`` cycles windows of the same application.
- **Mac screenshots** — `Alt + Shift + 3/4/5` capture the screen / a region / the Snipping Tool, saved to the Desktop.
- **Word navigation** — `Alt + Arrow` maps to Ctrl+Arrow.
- **Terminal-aware Ctrl** — Ctrl+C / Ctrl+Z keep working natively in consoles.
- **Auto-start & tray** — runs quietly in the system tray, optional launch at sign-in.

One native app using low-level keyboard hooks — no SharpKeys registry edits and no
AutoHotkey scripts to maintain.

## Installation

1. Download `Macifier_Setup_vX.Y.exe` from the [Releases page](https://github.com/layatai/macifier-app/releases/latest).
2. Run the installer.
3. Macifier launches into the system tray. Right-click the tray icon to configure.

## Usage

1. **Settings** — right-click the tray icon.
2. **Enable/Disable** — toggle key mapping on or off.
3. **Clipboard manager** — press `Alt + Shift + V` for history.
4. **Auto-start** — enable "Start with Windows" to launch on boot.
5. **Activate Pro** — tray menu → "Enter license key…".
6. **Exit** — right-click the tray icon → Exit.

## Key Mappings

| macOS | Windows (Macifier) | Result |
|---|---|---|
| ⌘ (Command) | Alt | Swapped with Ctrl |
| ⌥ (Option) | Ctrl | Swapped with Alt |
| ⌘ + C / V | Alt + C / V | Copy / Paste |
| ⌘ + Tab | Alt + Tab | Switch applications |
| ⌘ + Arrow | Alt + Arrow | Word navigation |
| ⌘ + ` | Alt + ` | Switch windows of the same app |
| ⌘ + Shift + V | Alt + Shift + V | Clipboard manager |
| ⌘ + Shift + 3/4/5 | Alt + Shift + 3/4/5 | Screenshot → Desktop |

## Troubleshooting

- **Keys not remapping** — check that Macifier is enabled (right-click the tray icon).
- **Permissions** — keyboard hooks may need elevation; run as administrator if mapping doesn't take effect.
- **Updates** — Pro checks automatically; on Free use the tray "Check for updates".

## License

Macifier is proprietary software. © Macifier. All rights reserved.
