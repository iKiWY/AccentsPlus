<div align="center">

<img src="https://accentsplus.klemen.nl/icon.png" width="120" alt="">

# Accents+

**Type accented characters on macOS without memorising numbers.**

Hold a letter, pick the accent you want, keep typing.

[Download](https://github.com/iKiWY/AccentsPlus/releases/latest) · [accentsplus.klemen.nl](https://accentsplus.klemen.nl) · [Ko-fi](https://ko-fi.com/klemmen)

</div>

---

## What it does

macOS already has a press and hold accent popup, but it shows every accent that
exists for a letter, in a fixed order, with no idea which ones you actually
write. Hold `e` and you get `è é ê ë ē ė ę` every time, so you end up reading a
row instead of typing.

Accents+ replaces that popup with one you control. You decide which accents live
on which key, which one is the default, and how you commit them.

## How it works

1. Press and hold a mapped key. The plain letter appears instantly, so normal
   typing is never delayed.
2. After a short delay, 300 ms by default, a picker appears above the letter.
3. Choose an accent with the arrow keys or the number keys, then commit with
   Space, Enter, or by releasing the key. Esc dismisses and keeps the plain
   letter.

A quick tap types the plain letter as usual, so fast typing is unaffected.

## Features

- **Any key, any accent.** Letters, punctuation and symbol keys. The first
  accent in a row is the default.
- **Language presets.** French, Spanish, German, Nordic, Croatian and Slovenian
  sets you can import and then edit freely.
- **Four ways to commit.** Space, Enter, the number keys and key release, each
  toggleable on its own.
- **Instant replace.** Skip the picker entirely and have a long press type the
  default accent straight away.
- **Themes and sizing.** Match the macOS accent popup in light, dark or system
  appearance, or use the app's own look, at whatever size suits you.
- **Stays out of the way.** Password fields, keyboard shortcuts and the Settings
  window are all left alone.

## Requirements

macOS 14 (Sonoma) or later, and Accessibility permission. The app reads key
presses and types characters system wide, which is what that permission is for.
Nothing you type is recorded, stored or sent anywhere.

## Install

1. Download the latest `.zip` from the
   [releases page](https://github.com/iKiWY/AccentsPlus/releases/latest) and
   unzip it.
2. Drag `Accents+.app` to your Applications folder and open it. It lives in the
   menu bar, not the Dock.
3. Grant Accessibility permission when macOS asks, or later in System Settings
   under Privacy & Security, then Accessibility.

If the first launch says the app cannot be verified, right click it, choose
Open, and confirm once. macOS remembers from then on.

## Privacy

Accents+ collects nothing. It reads the keyboard only to notice a held key and
to type the accent you choose, and all of that happens on your Mac. Nothing you
type is recorded, stored or sent anywhere, and the app never connects to the
internet. Your key mappings and settings are kept in your user account on your
Mac and go away with the app if you delete it.

## License

Accents+ is free to use on as many Macs as you like. Redistributing, selling,
modifying or reverse engineering it is not permitted. The full terms are in
[LICENSE.txt](LICENSE.txt), which is also included in the download.

## Support

Accents+ is free. If it saves you time, you can
[buy me a coffee on Ko-fi](https://ko-fi.com/klemmen).

## Troubleshooting

**The picker does nothing.** Check that Accents+ is switched on in System
Settings, Privacy & Security, Accessibility.

**The picker appears at the top of the window.** Some apps draw their own text
and never tell the system where the cursor is. Accents+ works around this where
it can, and where it cannot it puts the picker at the top of the window you are
typing in.

**Something else.** Open an issue and include your macOS version, the app
version from the About tab, and which app you were typing in.

---

© 2026 Klemen
