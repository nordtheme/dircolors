<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-dircolors/develop/src/assets/nord-dircolors-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/nord-dircolors/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-dircolors.svg?style=flat-square"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://www.gnu.org/software/coreutils/dircolors">dircolors</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-preview.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Getting started
### Installation
**NOTE**: Nord dircolors **MUST** be used with the associated terminal emulator theme in order to work properly!  
Make sure to install one of the currently supported terminal themes listed below before installing Nord dircolors.

[![Nord GNOME Terminal](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-gnome-terminal-banner.svg)](https://github.com/arcticicestudio/nord-gnome-terminal)  
[![Nord Guake](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-guake-banner.svg)](https://github.com/arcticicestudio/nord-guake)  
[![Nord iTerm2](https://cdn.rawgit.com/arcticicestudio/nord/0971858f496823fd916f3368961f16ef2c7aad1e/src/assets/nord-iterm2-banner.svg)](https://github.com/arcticicestudio/nord-iterm2)  
[![Nord Konsole](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-konsole-banner.svg)](https://github.com/arcticicestudio/nord-konsole)  
[![Nord Mintty](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-mintty-banner.svg)](https://github.com/arcticicestudio/nord-mintty)  
[![Nord PuTTY](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-putty-banner.svg)](https://github.com/arcticicestudio/nord-putty)  
[![Nord Terminal.app](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-terminal-app-banner.svg)](https://github.com/arcticicestudio/nord-terminal-app)  
[![Nord Terminator](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-terminator-banner.svg)](https://github.com/arcticicestudio/nord-terminator)  
[![Nord Tilix](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-tilix-banner.svg)](https://github.com/arcticicestudio/nord-tilix)  
[![Nord Termite](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-termite-banner.svg)](https://github.com/arcticicestudio/nord-termite)  
[![Nord XFCE Terminal](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-xfce-terminal-banner.svg)](https://github.com/arcticicestudio/nord-xfce-terminal)  
[![Nord Xresources](https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/nord-xresources-banner.svg)](https://github.com/arcticicestudio/nord-xresources)  

#### Manual
Copy the [`dir_colors`](https://github.com/arcticicestudio/nord-dircolors/blob/develop/src/dir_colors) file to `~/.dir_colors`.

#### Install Script
The included `install.sh` shell script can be used for an automated installation.  
If no option is specified, the default color theme file is `src/dir_colors`.

A list of available options can be shown with the `--help` option.
```shell
./install.sh --help
```
Syntax: `install.sh [OPTIONS]`

| Option | Description |
| --- | --- |
| `-h`, `--help` | Shows the help |
| `-v`, `--verbose` | Verbose output |
| `-c  <COLOR_THEME_FILE>`, `--colorthemefile <COLOR_THEME_FILE>` | Use the specified color theme file |

## Design Concept
### Global Defaults
#### Permissions
Directories are colored by `nord9` using a bold font.

Directories with the `t` permission flag have a `nord9` background, `nord4` foreground and the font is underlined while directories that addionally have the `o+w` permission flag are using a bold font style.

Directories with the `777` permission value are underlined.

![][scrot-global-defaults-permissions]

## Links
Symbolic links are colored by `nord8` while the font of hard links is addionally underlined.

The foreground of a invalid symbolic link is colored by `nord11` while nonexistent targets using a `nord11` background and a bold `nord4` foreground.

![][scrot-global-defaults-links]

#### Executables
Executables are colored by `nord7` using a bold font.

![][scrot-global-defaults-executables]

#### Blocks and Sockets
Character devices are colored by `nord13` while block devices are addionally using a bold font.

Sockets are also colored by `nord13` and addionally using a underlined font.

![][scrot-global-defaults-blocks-and-sockets]

#### Capabilities
The GID `g+s` and UID `u+s` capability flags are colored by the default `nord4` using a bold- and underlined font.

![][scrot-global-defaults-capabilities]

#### Named pipe (fifo)
Named pipes (fifo) are colored by `nord7` using a bold font.

![][scrot-global-defaults-fifo]

### Extension Pattern
#### Media
Extension for media based types like images, audio, videos and documents are colored by `nord14` while archive- and compression types are addionally using a bold font.

![][scrot-extension-pattern-media]

#### Ignores
This theme colorizes extensions that are produced during a application runtime, which should be ignored by version control systems, with the dimmed effect applied to `nord4`.

![][scrot-extension-pattern-ignores]

## Development
[![](https://img.shields.io/badge/Changelog-0.1.1-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-dircolors/blob/v0.1.1/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-dircolors/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg"/></p>

<p align="center">Copyright &copy; 2017-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-dircolors/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>

[scrot-extension-pattern-ignores]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-extension-pattern-ignores.png
[scrot-extension-pattern-media]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-extension-pattern-media.png
[scrot-global-defaults-blocks-and-sockets]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-blocks-and-sockets.png
[scrot-global-defaults-capabilities]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-capabilities.png
[scrot-global-defaults-executables]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-executables.png
[scrot-global-defaults-fifo]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-fifo.png
[scrot-global-defaults-links]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-links.png
[scrot-global-defaults-permissions]: https://raw.githubusercontent.com/arcticicestudio/nord-dircolors/develop/src/assets/scrot-global-defaults-permissions.png
