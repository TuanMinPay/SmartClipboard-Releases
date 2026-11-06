# SmartClipboard

A fast clipboard history for macOS. Everything you copy is kept in a searchable board that opens with
**Control+V**; pick a card and press **Return** to paste it straight into the app you are using.

- Text, rich text, links (with page titles), images (with text recognition), colours and files
- Search by app, type, date or text, with filter chips
- Pin clips into tags, preview and edit them, paste several in a row (Paste Stack)
- Password managers and concealed content are never recorded; everything stays on your Mac
- Updates install themselves automatically

## Install

1. Download **SmartClipboard-x.y.z.zip** from the [latest release](https://github.com/TuanMinPay/SmartClipboard-Releases/releases/latest).
2. Unzip it and move **SmartClipboard.app** to your **Applications** folder.
3. Open it. SmartClipboard lives in the menu bar (no Dock icon).
4. When asked, allow **Accessibility** in System Settings → Privacy & Security → Accessibility. It is needed to
   paste into other apps.

Requires macOS 14 Sonoma or later. The app is signed with a Developer ID and notarized by Apple.

## Updates

SmartClipboard checks for updates once a day, downloads them in the background and restarts itself for a
moment while you are not using it. You can also choose **Check for Updates…** from the menu bar icon, or turn
automatic installs off in Settings → Updates.

This repository only hosts releases and the update feed (`appcast.xml`).
