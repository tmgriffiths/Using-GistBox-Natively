Using GistBox Natively on MacOSX
================================

## 1. Download and install [Fluid](http://fluidapp.com/)
Download [fluid](http://fluidapp.com/) to create a Site Specific Browser (SSB). This is a way to make any web-app you commonly use into a standalone app. You can install fluid via [Homebrew cask](https://caskroom.github.io/) with `brew cask install fluid`

Once you've installed fluid open the application and enter the following information to set up GistBox and click create.

  - **URL:** app.gistboxapp.com
  - **Name:** GistBox

![Fluid Setup GistBox. Setup window.](fluid-setup-GistBox_1.png)

This should create an SSB specifically for GistBox and place it in /Applications/.


To make GitBox work with Fluid you have to whitelist [github.com](https://github.com) links in `Preferences > Whitelist`, so that the initial signup can happen. After that it works fine. Make sure you use \*'s to whitelist *all* github links generally.

![Fluid Setup GistBox. Whitelist preference pane.](fluid-setup-GistBox_3.png)

## Gist away!