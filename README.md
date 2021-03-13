# Chrome Secure Shell Themes

A fork of [Blink Shell themes](https://github.com/blinksh/themes) for Chrome
Secure Shell.

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
