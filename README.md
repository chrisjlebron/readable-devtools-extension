Readable DevTools Theme extension
=================================

Chrome extension for dev tools "Readable" theme.

Built using [Yeoman Generator for Chrome DevTools Theme](https://github.com/zenorocha/generator-devtools-theme)
with CSS forked from [Readable Chrome Dev Theme](https://github.com/Augus/Readable-ChromeDevThemes) and [SunnyVale Theme](https://github.com/mateusortiz/sunnyvale-theme).

Utilizes the new experimental devtools API (see [Chromium issue](https://code.google.com/p/chromium/issues/detail?id=318566) for more details), available in Chrome 33+.

### To use ###

(_Note: first two ripped straight from Yeoman theme generator docs_)

1. Copy whichever CSS file you'd like into the styles.css file (currently including the readable forked theme css & sunnyvale theme css; choose one and paste)
2. Enable DevTools experiments in `chrome://flags/#enable-devtools-experiments`.
3. Open DevTools > _Settings_ > _Experiments_ > _Allow UI themes_.
4. Go to `chrome://extensions/` and load unpacked extension (only available in Developer mode—just a toggle away!)
5. Enable the extension
6. Open the inspector and let out a sigh of relief

### Even more info ###
See Paul Irish's [original example extension](https://github.com/paulirish/sample-devtools-theme-extension).

CHANGELOG
---------
See [Releases](https://github.com/chrisjlebron/readable-devtools-extension/releases) for full version history.