# destroyer-ui
 cross-platform, customizable terminal emulator with advanced monitoring &amp; touchscreen support.
<p align="center">
  <br>
  <img alt="Logo" src="https://github.com/Meghal-kc/destroyer-ui/blob/main/logo.png">
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


## Features
- Fully featured terminal emulator with tabs, colors, mouse events, and support for `curses` and `curses`-like applications.
- Real-time system (CPU, RAM, swap, processes) and network (GeoIP, active connections, transfer rates) monitoring.
- Full support for touch-enabled displays, including an on-screen keyboard.
- Directory viewer that follows the CWD (current working directory) of the terminal.







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
