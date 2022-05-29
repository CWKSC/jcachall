# Environment Setup

[GitHub Desktop](#GitHub Desktop)

[Visual Studio Code](#Visual Studio Code)

[Jekyll](#jekyll)

[Typora](#Typora)

## GitHub Desktop

https://desktop.github.com/

GitHub Desktop use for git repository management

![github_git_clone](image\github_git_clone.png)

git clone repository into your local computer

![github_desktop](image\github_desktop.png)

Change will display, and to apply the change, write down the commit message (on left bottom) and click Commit to main

![github_desktop_update](image\github_desktop_update.png)

Then click push origin (on  top middle black bar)

![push](image\push.png)

## Visual Studio Code

https://code.visualstudio.com/

Visual Studio Code as Editor

![vscode](image\vscode.png)

## Jekyll

Reference: https://jekyllrb.com/docs/installation/windows/

Jekyll is core to build and run website

Following is the installation guideline for **Windows**, please check the official documentation for other operating systems

Download RubyInstallers: https://rubyinstaller.org/downloads/

![](image/RubyInstallers_download_page.png)

Download link on left side (WITH DEVKIT), the first one

After run it, following will show on screen:

![install_ruby](image\install_ruby.png)

Click Finish, 

![install_ruby2](image\install_ruby2.png)

Press Enter to install by default

![install_ruby3](image\install_ruby3.png)

Press Enter again to close

After it, close terminal and open a new one, run:

```
gem install jekyll bundler
```

![install_jekyll](image\install_jekyll.png)

To check is it installed, run:

```
jekyll -v
```

Go under root of repository, run:

```
bundle install
```

![bundle_install](image\bundle_install.png)

To start server, run:

```
bundle exec jekyll serve
```

It is same as what `run.ps1` do

![run_server](image\run_server.png)

It will running on 127.0.0.1:4000, you can check out it for development preview

## Typora

https://typora.io/releases/all

Typora use for editing markdown file (.md)

Typora start to charge after version 1.0.0

You can download 0.11.18 version in <u>History Releases</u> > <u>Dev / Beta Releases</u> > <u>More Beta</u> > <u>old Windows / Linux beta</u>