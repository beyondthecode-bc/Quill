<p align="center">
  <img src="images/banner.png" alt="Quill — rich-text snippets, pasted anywhere with a keystroke" width="100%">
</p>

<p align="center">
  <strong>Rich-text snippets, pasted anywhere with a keystroke</strong><br>
  Type a short abbreviation or press a hotkey — Quill pastes back the whole thing, fully formatted: bold, colors, lists, fonts, sizes, even images.
</p>

<p align="center">
  <a href="https://github.com/beyondthecode-bc/Quill/releases/latest"><img src="https://img.shields.io/github/v/release/beyondthecode-bc/Quill?style=flat-square&label=Download&color=blue" alt="Latest Release"></a>
  <a href="https://github.com/beyondthecode-bc/Quill/releases/latest"><img src="https://img.shields.io/github/downloads/beyondthecode-bc/Quill/total?style=flat-square&label=Downloads&color=brightgreen" alt="Downloads"></a>
  <a href="https://github.com/beyondthecode-bc/Quill/stargazers"><img src="https://img.shields.io/github/stars/beyondthecode-bc/Quill?style=flat-square" alt="Stars"></a>
  <img src="https://img.shields.io/github/license/beyondthecode-bc/Quill?style=flat-square&cacheSeconds=300" alt="License">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%2014%2B-lightgrey?style=flat-square&logo=apple" alt="Platform">
  <img src="https://img.shields.io/badge/chip-Apple%20Silicon%20%2B%20Intel-orange?style=flat-square&logo=apple" alt="Apple Silicon + Intel">
  <img src="https://img.shields.io/badge/swift-6.0-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
  <img src="https://img.shields.io/badge/SwiftUI-native-007AFF?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI">
</p>

<p align="center">
  <a href="https://www.virustotal.com/gui/file/475caf21a175e534a3246d542ec7b6f91fe8c0ef7a25f1645d64fb6873555fec"><img src="https://img.shields.io/badge/VirusTotal-0%2F66%20Clean-brightgreen?style=flat-square&logo=virustotal&logoColor=white" alt="VirusTotal"></a>
  <a href="https://github.com/sponsors/beyondthecode-bc"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?style=flat-square&logo=github" alt="GitHub Sponsors"></a>
  <a href="https://www.buymeacoffee.com/BEYONDTHECODE"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=flat-square&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"></a>
</p>

<p align="center">
  Built with Swift and SwiftUI. No Electron, no web views, no bloat.
</p>

---

> [!NOTE]
> This is a **community hub**, not a source repository. It hosts Quill's
> signed release downloads, translations, and issue tracker. The app's source
> code is closed and is never published here.

Quill is a native macOS snippet expander for **rich, formatted** content —
bold/italic/underline, color, fonts, lists, and embedded images (email
signatures) — triggered by a typed abbreviation or a global hotkey and pasted
into any app. It's TextExpander-category power at a **one-time price**, with no
subscription.

## Features

- **Rich formatting** — bold, italic, underline, text color, **font family &
  size**, bullet & numbered lists, and embedded images (like an email
  signature), pasted straight into any app.
- **Two triggers per snippet** — a typed abbreviation (e.g. `;sig`) and/or a
  global hotkey.
- **Quick-Search palette** — a Spotlight-style palette to find and paste any
  snippet back into the app you were just in.
- **Developer-ID signed + notarized** — no Gatekeeper "unidentified developer"
  wall.

Free to download and fully functional — **rich snippets, both triggers, and the
Quick-Search palette, with no snippet cap.** **Quill Pro ($12 one-time)**
unlocks:

- **Dynamic tokens** — `%date%` math, `%time%`, `%clipboard%`, `%cursor%`
  placement, and nested snippets.
- **App-specific expansion** — allow a snippet to expand only in the apps you
  choose.
- **iCloud sync** — your snippet library across all your Macs.

## Screenshots

![Library and rich editor](images/library-editor.png)

<p align="center"><em>Groups, a searchable snippet list, and a rich editor with a formatting toolbar and embedded images — organize snippets into groups, duplicate and move them, and paste anywhere.</em></p>

<p align="center">
  <img src="images/hotkeys.png" alt="Hotkeys settings" width="540">
</p>

<p align="center"><em>Triggers — a global Quick-Search hotkey, a toggle-expansion shortcut, and per-snippet hotkeys.</em></p>

## Download

Grab the latest signed `.zip` from the [Releases](https://github.com/beyondthecode-bc/Quill/releases)
page. Each release ships a SHA-256 checksum and is notarized by Apple. Unzip,
move `Quill.app` to Applications, and launch.

## Requirements

- macOS 14 (Sonoma) or later — Apple Silicon or Intel
- **Accessibility** + **Input Monitoring** permissions (Quill guides you through
  granting them on first launch). Hotkey-only triggers need just Accessibility.

## Get Quill Pro

[Unlock Quill Pro — $12 one-time](https://beyondthecode.gumroad.com/l/quill-pro).
Enter your license key in **Settings → License**. One purchase activates up to
**3 Macs**; deactivate any Mac to free a slot.

## Translations

Quill is localized via XML files in [`languages/`](languages/). To contribute a
translation, copy `English.xml`, translate the values (keep the `key` attributes
unchanged), and open a pull request or a [Translation issue](https://github.com/beyondthecode-bc/Quill/issues/new?template=translation.md).

## Support

- [Report a bug](https://github.com/beyondthecode-bc/Quill/issues/new?template=bug_report.md)
- [Request a feature](https://github.com/beyondthecode-bc/Quill/issues/new?template=feature_request.md)
- Homepage: https://beyondthecode.app

---

Made by [Beyond the Code](https://beyondthecode.app).
