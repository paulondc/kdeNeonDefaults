### What is this project about ?
I use this project to store my personal [KDE neon](https://neon.kde.org/) settings, since it can be very demanding to configure KDE from scratch. The overall goal of these settings is to provide an easy & intuitive workflow without giving up the modern usability enhancements found in other systems.
![screenshot](./data/screenshot.png)

### How does it work ?
Everything is done on top of [KDE neon](https://neon.kde.org/), it does not use any special theme or extension.

![KDE neon](./data/neon-logo.png)

It works by providing config files that contain pre-defined settings. Therefore, I managed to isolate the settings that were related with the changes I made in my initial KDE neon installation and created a bundle for them. By using it you should get the same look & feel.

### How do I get it ?
It requires [KDE neon](https://neon.kde.org/) 5.9 (or greater).

[Download](https://github.com/paulondc/kdeNeonDefaults/archive/master.zip) the zip (or git clone the project):
unzip the contents and run the setup:
```
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

The next set of shortcuts I recommend you to put a sticker in the F8 key of your keyboard:
![key](./data/kde-expose-key.jpg)

- present all windows (expose): `F8`
- show desktop grid (spaces): `ctrl + F8`
- show desktop: `shift + F8`

#### Customized applications:
- kwrite
- dolphin
- konsole
- konversation
