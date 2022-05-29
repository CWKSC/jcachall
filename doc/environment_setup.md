# Environment Setup

[GitHub Desktop](#GitHub Desktop)

[Visual Studio Code](#Visual Studio Code)

[Jekyll](#jekyll)

[Typora](#Typora)

## GitHub Desktop

https://desktop.github.com/

GitHub Desktop use for git repository management

## Visual Studio Code

https://code.visualstudio.com/

Visual Studio Code as Editor

## Jekyll

Reference: https://jekyllrb.com/docs/installation/windows/

Jekyll is core to build and run website

Download RubyInstallers: https://rubyinstaller.org/downloads/

![](image/RubyInstallers_download_page.png)

Download link on left side (WITH DEVKIT), the first one

After run it, following will show on screen:

```
 _____       _           _____           _        _ _         ___
|  __ \     | |         |_   _|         | |      | | |       |__ \
| |__) |   _| |__  _   _  | |  _ __  ___| |_ __ _| | | ___ _ __ ) |
|  _  / | | | '_ \| | | | | | | '_ \/ __| __/ _` | | |/ _ \ '__/ /
| | \ \ |_| | |_) | |_| |_| |_| | | \__ \ || (_| | | |  __/ | / /_
|_|  \_\__,_|_.__/ \__, |_____|_| |_|___/\__\__,_|_|_|\___|_||____|
                    __/ |           _
                   |___/          _|_ _  __   | | o __  _| _     _
                                   | (_) |    |^| | | |(_|(_)\^/_>

   1 - MSYS2 base installation
   2 - MSYS2 system update (optional)
   3 - MSYS2 and MINGW development toolchain

Which components shall be installed? If unsure press ENTER [1,2,3]
```

Press Enter to install by default

After it, close terminal and open a new one, run:

```
gem install jekyll bundler
```

To check is it installed, run:

```
jekyll -v
```

Go under root of repository, run:

```
bundle install
```

To start server, run:

```
bundle exec jekyll serve
```

It is same as what `run.ps1` do

## Typora

https://typora.io/releases/all

Typora use for editing markdown file (.md)

Typora start to charge after version 1.0.0

You can download 0.11.18 version in <u>History Releases</u> > <u>Dev / Beta Releases</u> > <u>More Beta</u> > <u>old Windows / Linux beta</u>