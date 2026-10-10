# Gboard+ 

A Gboard toolbar with a **clipboard vault (text + images)**, **shortcuts**, **cursor/trackpad
tools**, **select mode** and **screenshot capture** â€” delivered as a standalone LSPosed module.

Gboard+ was **extracted from [Auto Expand]** so the Gboard feature lives in its own module with an
isolated scope, preferences and storage. Both modules can be installed at the same time without
fighting over Gboard.

> Not affiliated with Google. "Gboard" is a trademark of Google LLC.

---

## Features

- **Toolbar row** above the keyboard, sized to your layout.
- **Buttons:** Clipboard, Paste, Select-all (tap = word آ· long-press = field), Cursor nav,
  Trackpad stick, Select-mode toggle, Text shortcut (tap/long-press).
- **Clipboard vault:** history, pin, favourite, search, capacity limit, full-text/one-line rows.
- **Image vault:** save copied images, dedup by hash, entry + byte budgets.
- **Screenshots:** auto-capture into the vault; optionally push to the clipboard.
- **Undo:** shake-to-undo and/or an Undo button, with sensitivity.
- **Haptics:** vibration strength, trackpad haptics and sensitivity.
- **Liveness card:** tells you whether the module is actually loaded in Gboard, with a one-tap
  restart.
- **Auto Expand handoff:** if AE's Gboard tweak is still on, Gboard+ removes AE's toolbar row and
  offers a one-tap (root) takeover.

## Toolbar buttons

The strip above the keyboard. Every demo below loops on its own â€” no need to press play.

### ًں“‹ Clipboard

Opens the clipboard vault â€” a history of everything you copied (text and images) with pin,
favourite, search and delete.

<p align="center"><img src="https://raw.githubusercontent.com/kvmy666/Gboard/main/docs/media/clipboard.gif" width="340" alt="Clipboard vault"></p>

### âœ‚ï¸ڈ Select

A single tap selects the last word; a long-press selects everything. Opens the
Cut / Copy / Paste / Share bar.

<p align="center"><img src="https://raw.githubusercontent.com/kvmy666/Gboard/main/docs/media/select.gif" width="340" alt="Select"></p>

### ًں•¹ï¸ڈ Trackpad (+ ًں–چï¸ڈ select mode)

Drag to move the cursor letter-by-letter. Turn on the pen (ًں–چï¸ڈ select mode) and the same drag
highlights a selection instead.

<p align="center"><img src="https://raw.githubusercontent.com/kvmy666/Gboard/main/docs/media/trackpad.gif" width="340" alt="Trackpad + select mode"></p>

### â­گ Text shortcut

Inserts text you predefined in the app â€” tap inserts shortcut 1, long-press inserts shortcut 2.

<p align="center"><img src="https://raw.githubusercontent.com/kvmy666/Gboard/main/docs/media/star.gif" width="340" alt="Text shortcut"></p>

### ًں“¥ Paste

Pastes the last thing you copied. If the newest vault entry is an image or screenshot, it pastes
that image instead.

<p align="center"><img src="https://raw.githubusercontent.com/kvmy666/Gboard/main/docs/media/paste.gif" width="340" alt="Paste"></p>

## Requirements

- Rooted device with **LSPosed** (Zygisk/Riru).
- **Android 15+** (verified on Android 16 / OxygenOS), **arm64-v8a**.
- **Gboard** installed (verified against 18.4.1).
- **Root is optional**: the core toolbar, vault, images and screenshots work without it. Root only
  unlocks automatic force-stop reload and the one-tap AE takeover.

## Install

1. Install the APK.
2. Open **LSPosed Manager â†’ Modules**, enable **Gboard+**.
3. In **Scope**, select **Gboard** (`com.google.android.inputmethod.latin`) only, then reboot.
4. Open the **Gboard+** app. If the card says *not loaded*, tap **Force stop Gboard** (root) or
   **Open Gboard app info â†’ Force stop**, then open the keyboard once.

## Support & feedback

- **Report a bug / ask a question:** Telegram **[@kvmy1](https://t.me/kvmy1)**
- **Issues:** [open an issue](https://github.com/kvmy666/Gboard/issues) â€” include your device, Android
  version, Gboard version, and `adb logcat -s GboardPlus`.

## License

Personal project. See repository for terms.
