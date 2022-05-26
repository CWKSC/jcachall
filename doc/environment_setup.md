# Environment Setup

Suggest to use Visual Studio Code as editor

### Windows

Reference: https://jekyllrb.com/docs/installation/windows/

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