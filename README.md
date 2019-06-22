<p align="center"><a href="https://www.nordtheme.com/ports/dircolors" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/repository-hero.svg?sanitize=true"/></a></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-dircolors/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-dircolors.svg?style=flat-square&label=Release&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a> <a href="https://www.nordtheme.com/docs/ports/dircolors"><img src="https://img.shields.io/github/release/arcticicestudio/nord-dircolors.svg?style=flat-square&label=Docs&colorA=4c566a&colorB=88c0d0&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI%2BCiAgICA8cGF0aCBmaWxsPSIjZDhkZWU5IiBkPSJNMTMuNzQ2IDIuODEzYS42Ny42NyAwIDAgMC0uNTU5LS4xMzNMOCAzLjg0OGwtNS4xODgtMS4xOGEuNjY5LjY2OSAwIDAgMC0uNTcuMTMzLjY3Ny42NzcgMCAwIDAtLjI0Mi41MzF2OC4xMzNjLS4wMDguMzIuMjEuNTk4LjUyLjY2OGw1LjMzMiAxLjE5OWguMjk2bDUuMzMyLTEuMmEuNjY4LjY2OCAwIDAgMCAuNTItLjY2N1YzLjMzMmEuNjU5LjY1OSAwIDAgMC0uMjU0LS41MnpNMy4zMzIgNC4xNjhsNCAuODk4djYuNzY2bC00LS44OTh6bTkuMzM2IDYuNzY2bC00IC44OThWNS4wNjZsNC0uODk4em0wIDAiLz4KPC9zdmc%2BCg%3D%3D"/></a> <a href="https://github.com/arcticicestudio/nord-dircolors/blob/develop/CHANGELOG.md#050"><img src="https://img.shields.io/github/release/arcticicestudio/nord-dircolors.svg?style=flat-square&label=Changelog&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a></p>

<p align="center"><a href="https://github.com/arcticicestudio/styleguide-markdown/releases/latest" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/styleguide-markdown.svg?style=flat-square&label=Markdown%20Style%20Guide&colorA=4c566a&colorB=88c0d0&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzOSIgaGVpZ2h0PSIzOSIgdmlld0JveD0iMCAwIDM5IDM5Ij48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNEOERFRTkiIHN0cm9rZS13aWR0aD0iMyIgc3Ryb2tlLW1pdGVybGltaXQ9IjEwIiBkPSJNMS41IDEuNWgzNnYzNmgtMzZ6Ii8%2BPHBhdGggZmlsbD0iI0Q4REVFOSIgZD0iTTIwLjY4MyAyNS42NTVsNS44NzItMTMuNDhoLjU2Nmw1Ljg3MyAxMy40OGgtMS45OTZsLTQuMTU5LTEwLjA1Ni00LjE2MSAxMC4wNTZoLTEuOTk1em0tMi42OTYgMGwtMTMuNDgtNS44NzJ2LS41NjZsMTMuNDgtNS44NzJ2MS45OTVMNy45MzEgMTkuNWwxMC4wNTYgNC4xNnoiLz48L3N2Zz4%3D"/></a> <a href="https://github.com/arcticicestudio/styleguide-git/releases/latest" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/styleguide-git.svg?style=flat-square&label=Git%20Style%20Guide&logoColor=eceff4&colorA=4c566a&colorB=88c0d0&logo=git"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://www.gnu.org/software/coreutils/dircolors" target="_blank">dircolors</a> theme.</p>

<p align="center">Designed for a fluent and clear workflow based on the <a href="https://www.nordtheme.com" target="_blank">Nord</a> color palette.</p>

<p align="center"><a href="https://www.nordtheme.com/ports/dircolors" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/overview.png"/></a></p>

## Getting started

Visit the [official website][nord-home] to learn all about the [features][nord-home#intro], how to [install and activate][nord-docs-home-install] the theme, supported [data and node types][nord-docs-home-types] and more from the [official documentations][nord-docs-home].

### Quick Start

Nord dircolors can be installed for all application that respect the `LS_COLORS` environment variable like GNU core utils [`ls`][wiki-ls], [`tree`][wiki-tree] or modern projects like [`fd`][gh-sharkdp/fd].

Download the [`dir_colors`][gh-tree-dir_colors] file and place it as `~/.dir_colors` in your [home directory][wiki-home_dir].

For more details see the [official installation & activation guide][nord-docs-home-install] as well as the [GNU `dircolors` documentations][gnu-docs-dircolors].

#### Latest Development State

To always use the latest development state of Nord dircolors, [clone the repository][repo] and create a [symbolic link][wiki-symlink] of the `src/dir_colors` file to `~/.dir_colors` in your [home directory][wiki-home_dir] afterwards:

```sh
ln -sr "$PWD/src/dir_colors" "~/.dir_colors"
```

#### Activation

To activate and use Nord dircolors as your default color theme for all sessions, load the theme with `dircolors` by adding the following snippet to the configuration file of your shell (`~/.bashrc`, `~/.zshrc`, …):

```sh
test -r "~/.dir_colors" && eval $(dircolors ~/.dir_colors)
```

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/installation-shell-rc.png"/></p>

## Features

<p align="center"><strong>Beautiful highlighting for all your bits and bytes.</strong></p>
<p align="center">Support for a wide range of data and node types — From <a href="https://en.wikipedia.org/wiki/Symbolic_link" target="_blank">symbolic links</a>, <a href="https://en.wikipedia.org/wiki/Executable" target="_blank">executables</a> up to <a href="https://en.wikipedia.org/wiki/File_system_permissions" target="_blank">file system permissions</a>.</p>
<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/links.png"/></p>

<p align="center">Directories with different <a href="https://en.wikipedia.org/wiki/File_system_permissions" target="_blank">file system permissions</a>.</p>
<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/directories.png"/></p>

<p align="center">Various <a href="https://en.wikipedia.org/wiki/Unix_file_types" target="_blank">Unix file types</a> like <a href="https://en.wikipedia.org/wiki/Device_file" target="_blank">device files</a> and <a href="https://en.wikipedia.org/wiki/Unix_domain_socket" target="_blank">domain sockets</a>.</p>
<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/dircolors/blocks-and-sockets.png"/></p>

## Contributing

Nord is an open source project and we love to receive contributions from the [community][nord-comm]!

There are many ways to contribute, from [writing- and improving documentation and tutorials][nord-contrib-guide-docs], [reporting bugs][nord-contrib-guide-bugs], [submitting enhancement suggestions][nord-contrib-guide-enhance] that can be added to Nord by [submitting pull requests][nord-contrib-guide-pr].

Please take a moment to read Nord's full [contributing guide][nord-contrib-guide] to learn about the development process, the project's used [styleguides][nord-contrib-guide-styles], [branch organization][nord-contrib-guide-branching] and [versioning][nord-contrib-guide-versioning] model.

The guide also includes information about [minimal, complete, and verifiable examples][nord-contrib-guide-mcve] and other ways to contribute to the project like [improving existing issues][nord-contrib-guide-impr-issues] and [giving feedback on issues and pull requests][nord-contrib-guide-feedback].

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/nord/repository-footer-separator.svg?sanitize=true" /></p>

<p align="center">Copyright &copy; 2017-present <a href="https://www.arcticicestudio.com" target="_blank">Arctic Ice Studio</a> and <a href="https://www.svengreb.de" target="_blank">Sven Greb</a></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-dircolors/blob/develop/LICENSE.md"><img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=MIT&logoColor=eceff4&logo=github&colorA=4c566a&colorB=88c0d0"/></a></p>

[gh-sharkdp/fd]: https://github.com/sharkdp/fd
[gh-tree-dir_colors]: https://github.com/arcticicestudio/nord-dircolors/blob/develop/src/dir_colors
[gnu-docs-dircolors]: https://www.gnu.org/software/coreutils/manual/html_node/dircolors-invocation.html
[nord-comm]: https://www.nordtheme.com/community
[nord-contrib-guide-branching]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#branch-organization
[nord-contrib-guide-bugs]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#bug-reports
[nord-contrib-guide-docs]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#documentations
[nord-contrib-guide-enhance]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#enhancement-suggestions
[nord-contrib-guide-feedback]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#give-feedback-on-issues-and-pull-requests
[nord-contrib-guide-impr-issues]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#improve-issues
[nord-contrib-guide-mcve]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#mcve
[nord-contrib-guide-pr]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#pull-requests
[nord-contrib-guide-styles]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#styleguides
[nord-contrib-guide-versioning]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md#versioning
[nord-contrib-guide]: https://github.com/arcticicestudio/nord/blob/develop/CONTRIBUTING.md
[nord-docs-home-install]: https://www.nordtheme.com/docs/ports/dircolors/installation
[nord-docs-home-types]: https://www.nordtheme.com/docs/ports/dircolors/type-support
[nord-docs-home]: https://www.nordtheme.com/docs/ports/dircolors
[nord-home]: https://www.nordtheme.com/ports/dircolors
[nord-home#intro]: https://www.nordtheme.com/ports/dircolors#introduction
[repo]: https://github.com/arcticicestudio/nord-dircolors
[wiki-home_dir]: https://en.wikipedia.org/wiki/Home_directory
[wiki-ls]: https://en.wikipedia.org/wiki/Ls
[wiki-symlink]: https://en.wikipedia.org/wiki/Symbolic_link
[wiki-tree]: https://en.wikipedia.org/wiki/Tree_(command)
