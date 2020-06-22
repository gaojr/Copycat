# Copycat

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/jdjbiojkklnaeoanimopafmnmhldejbg.svg?maxAge=86400)](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg) [![Mozilla Add-on](https://img.shields.io/amo/v/extension-copycat.svg?maxAge=864000)](https://addons.mozilla.org/firefox/addon/extension-copycat/) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackGlory/copycat/master/LICENSE)

![Copycat](https://github.com/BlackGlory/copycat/blob/master/src/assets/images/icon-128.png?raw=true)

Copy content from web powerful than ever before.

## Support browsers

- [x] [Chrome](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)
- [x] [Firefox](https://addons.mozilla.org/firefox/addon/extension-copycat/)
- [x] Opera: Code review too slow, never publish again, please manually install.
- [x] [Vivaldi](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)
- [x] [Edge](https://chrome.google.com/webstore/detail/copycat/jdjbiojkklnaeoanimopafmnmhldejbg)

## Features

- [x] Copy tab link as
  - [x] Plaintext
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
- [x] Copy frame link as
  - [x] Plaintext
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
- [x] Copy link as
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
- [x] Copy selection as
  - [x] Plaintext
  - [x] Raw strings
  - [x] Markdown
  - [x] BBCode
  - [x] HTML
  - [x] HTML(only `<a>` tag)
  - [x] HTML(no attributes)
- [x] Copy image as
  - [x] Markdown
  - [x] Markdown(DataURI jpeg, png, webp[^1])
  - [x] HTML
  - [x] HTML(DataURI jpeg, png, webp[^1])
  - [x] DataURI(original format)
  - [x] DataURI(jpeg, png, webp[^1])
  - [x] BBCode
- [x] Copy browser native audio/video as HTML

[^1]: WebP format is Chromium(Chrome, Opera, Vivaldi) only

## Support Markdown flavors

- [x] [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [x] [CommonMark](http://commonmark.org/)
- [x] [Ghost's Markdown](https://help.ghost.org/article/4-markdown-guide)

## Keyboard shortcuts

Copy tab link and selection can be set as keyboard shortcuts.

Chrome shortcuts page: `chrome://extensions/shortcuts`
Edge shortcuts page: `edge://extensions/shortcuts`

Unfortunately, I couldn't find the official shortcut key customization page in Firefox. Maybe users can use other extensions to implement shortcut key binding. Copycat will not provide related UI for the time being.
