# Chrome Secure Shell Themes

## Overview

A collection of themes for Chrome Secure Shell, generated using
[xrdb2hterm](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/tools/xrdb2hterm)
script to convert
[`xrdb/*`](https://github.com/mbadolato/iTerm2-Color-Schemes/tree/master/xrdb)
themes to hterm themes.

## Install

To install the theme on Chrome Secure Shell:

1. Copy the theme's JavaScript code: `cat theme/foo.js | pbcopy`
1. Open Chrome Secure Shell in your browser (i.e. `ssh://`)
1. Open the **JavaScript Console**: hit <kbd>F12</kbd>
1. Paste & execute the javascript code.

To reset Chrome Secure Shell's appearance:

1. Follow the steps above, but copy and execute the javascript code below:

   ```js
   term_.prefs_.reset("color-palette-overrides");
   term_.prefs_.reset("foreground-color");
   term_.prefs_.reset("background-color");
   term_.prefs_.reset("cursor-color");
   ```

## Thanks

This project would not be possible without [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)
and all the great contributions from the community.

## License

MIT
