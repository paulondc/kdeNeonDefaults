### What is this project about ?
This project is used to share initial [KDE neon](https://neon.kde.org/) settings, since it can be very demanding to configure KDE from scratch. The overall goal of these settings is to provide an easy & intuitive workflow without giving up usability enhancements that takes advantage of modern hardware.
![screenshot](./data/screenshot.png)

### How does it work ?
Everything is done on top of [KDE neon](https://neon.kde.org/), it does not use any special theme or extension.

![KDE neon](./data/neon-logo.png)

It works by providing pre-defined config files that were isolate from a fresh [KDE neon](https://neon.kde.org/) installation. It contains modifications all over KDE from little things aka not showing the icon at window's title bar to changing some of the global shortcuts (described below).

### How do I get it ?
It requires [KDE neon](https://neon.kde.org/) 5.9 (or greater).

[Download the zip](https://github.com/paulondc/kdeNeonDefaults/archive/master.zip) (or git clone the project):
unzip the contents and run the setup:
```bash
wget https://github.com/paulondc/kdeNeonDefaults/archive/master.zip -O kdeNeonDefaults.zip
unzip kdeNeonDefaults.zip
cd kdeNeonDefaults-master
./setup
```

> Be aware by running the setup it will override your current settings (you may want to create a backup of your current configuration for the directories  `~/.config, ~/.kde and ~/.local` beforehand).

---

#### Customized shortcuts:
- open dolphin:  `super + e`
- open konsole: `super + r`
- minimize/restore all windows: `super + d`
- close current window: `ctrl + w`
- change to next virtual desktop: `alt + left`
- change to previous virtual desktop: `alt + right`

For the next set of shortcuts I recommend you to put a [sticker on F8 key](./data/f8-sticker.png):
![key](./data/kde-expose-key.jpg)

- present all windows (expose): `F8`
- show desktop grid (spaces): `ctrl + F8`
- show desktop: `shift + F8`

#### Customized applications:
- kwrite
- dolphin
- konsole
- kdiff3
- konversation
