# destroyer-ui
 cross-platform, customizable science fiction terminal emulator with advanced monitoring &amp; touchscreen support.
<p align="center">
  <br>
  <img alt="Logo" src="media/logo.png">
  <br><br>
  <a href="https://lgtm.com/projects/g/GitSquared/destroyer-ui/context:javascript"><img alt="undefined" src="https://img.shields.io/lgtm/grade/javascript/g/GitSquared/destroyer-ui.svg?logo=lgtm&logoWidth=18"/></a>
  <br>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/latest"><img alt="undefined" src="https://img.shields.io/github/release/GitSquared/destroyer-ui.svg?style=popout"></a>
  <a href="#featured-in"><img alt="undefined" src="https://img.shields.io/github/downloads/GitSquared/destroyer-ui/total.svg?style=popout"></a>
  <a href="https://github.com/GitSquared/destroyer-ui/blob/master/LICENSE"><img alt="undefined" src="https://img.shields.io/github/license/GitSquared/destroyer-ui.svg?style=popout"></a>
  <br>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/download/v2.2.8/destroyer-UI-Windows.exe" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/Windows/?color=blue&icon=windows&label"></a>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/download/v2.2.8/destroyer-UI-macOS.dmg" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/macOS/?color=grey&icon=apple&label"></a>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/download/v2.2.8/destroyer-UI-Linux-x86_64.AppImage" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/Linux64/?color=orange&icon=terminal&label"></a>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/download/v2.2.8/destroyer-UI-Linux-arm64-AppImage" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/LinuxArm64/?color=orange&icon=terminal&label"></a>
  <a href="https://aur.archlinux.org/packages/destroyer-ui" target="_blank"><img alt="undefined" src="https://badgen.net/badge/AUR/Package/cyan"></a>
  <br>
  <a href="https://github.com/GitSquared/destroyer-ui/releases/tag/v2.2.8"><strong><i>(Project archived oct. 18th 2021)</i></strong></a>
  <br><br><br>
</p>

destroyer-UI is a fullscreen, cross-platform terminal emulator and system monitor that looks and feels like a sci-fi computer interface.

---

<a href="https://youtu.be/BGeY1rK19zA">
  <img align="right" width="400" alt="Demo on YouTube" src="media/youtube-demo-teaser.gif">
</a>


<p align="center">
  <em>Jump to: <br><a href="#features">Features</a> — <a href="#screenshots">Screenshots</a> — <a href="#qa">Questions & Answers</a> — <strong><a href="#how-do-i-get-it">Download</a></strong> — <a href="#featured-in">Featured In</a> — <a href="#useful-commands-for-the-nerds">Contributor Instructions</a> — <a href="#credits">Credits</a></em>
</p>

## Sponsor

**Want to help support my open-source experiments and learn some cool JavaScript tricks at the same time?**

Click the banner below and sign up to **Bytes**, the only newsletter cool enough to be recommended by destroyer-UI.

[![Bytes by UI.dev](media/sponsor-uidev-bytes.jpg)](https://ui.dev/bytes/?r=gabriel)

## Features
- Fully featured terminal emulator with tabs, colors, mouse events, and support for `curses` and `curses`-like applications.
- Real-time system (CPU, RAM, swap, processes) and network (GeoIP, active connections, transfer rates) monitoring.
- Full support for touch-enabled displays, including an on-screen keyboard.
- Directory viewer that follows the CWD (current working directory) of the terminal.
- Advanced customization using themes, on-screen keyboard layouts, CSS injections. See the [wiki](https://github.com/GitSquared/destroyer-ui/wiki) for more info.
- Optional sound effects made by a talented sound designer for maximum hollywood hacking vibe.

## Screenshots
![Default screenshot](media/screenshot_default.png)

_[neofetch](https://github.com/dylanaraps/neofetch) on destroyer-UI 2.2 with the default "tron" theme & QWERTY keyboard_

![Blade screenshot](media/screenshot_blade.png)

_Checking out available themes in [destroyer's config dir](https://github.com/GitSquared/destroyer-ui/wiki/userData) with [`ranger`](https://github.com/ranger/ranger) on destroyer-UI 2.2 with the "blade" theme_

![Disrupted screenshot](media/screenshot_disrupted.png)

_[cmatrix](https://github.com/abishekvashok/cmatrix) on destroyer-UI 2.2 with the experimental "tron-disrupted" theme, and the user-contributed DVORAK keyboard_

![Horizon screenshot](media/screenshot_horizon.png)

_Editing destroyer-UI source code with `nvim` on destroyer-UI 2.2 with the custom [`horizon-full`](https://github.com/GitSquared/horizon-destroyer-theme) theme_


Thanks! If you feel like it, you can [follow me on Twitter](https://gaby.dev/twitter) to hear about new stuff I'm making.

<img width="220" src="https://78.media.tumblr.com/35d4ef4447e0112f776b629bffd99188/tumblr_mk4gf8zvyC1s567uwo1_500.gif" />





## Useful commands for the nerds

**IMPORTANT NOTE:** the following instructions are meant for running destroyer from the latest unoptimized, unreleased, development version. If you'd like to get stable software instead, refer to [these](#how-do-i-get-it) instructions.

#### Starting from source:
on *nix systems (You'll need the Xcode command line tools on macOS):
- clone the repository
- `npm run install-linux`
- `npm run start`

on Windows:
- start cmd or powershell **as administrator**
- clone the repository
- `npm run install-windows`
- `npm run start`

#### Building
Note: Due to native modules, you can only build targets for the host OS you are using.

- `npm install` (NOT `install-linux` or `install-windows`)
- `npm run build-linux` or `build-windows` or `build-darwin`

The script will minify the source code, recompile native dependencies and create distributable assets in the `dist` folder.



## Licensing

Licensed under the [GPLv3.0](https://github.com/GitSquared/destroyer-ui/blob/master/LICENSE).
