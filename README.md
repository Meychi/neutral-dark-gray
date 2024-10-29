# Introduction

Repository contains:

- `manifest.json`: theme file to package for https://addons.firefox.com
- `chrome` folder containing CSS files for Firefox

Tested on Mac and Windows 11 in dark mode with Firefox v132.

## Using these CSS files in Firefox

1. Download or clone repository
2. Open `about:config` page in Firefox
    - A dialog will warn you, ignore it, press the `I accept the risk!` button
    - Enable: `toolkit.legacyUserProfileCustomizations.stylesheets` property
3. Go to your Firefox profile:
    - `Menu` > `Help` > `More troubleshoot information` > `Profile Folder` > `Open Folder`
4. Copy `chrome` directory to you profile folder
5. Restart Firefox

## Screenshots

![Startpage](/images/startpage.jpg "Startpage")

![Settings](/images/settings.jpg "Settings")
