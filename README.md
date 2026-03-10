![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)
# Kobo Clara BW Screensavers (Wallpapers)

This repository contains a set of images optimized for Kobo Clara e-ink readers and prepared for use as sleep screen (screensaver) wallpapers.

Resolution: **1072×1448** (native Kobo Clara BW screen resolution).

When redistributing or reusing these images, please include attribution similar to the example below:

```
Image by: ge-roy
Source: https://github.com/ge-roy/kobo-clara-screensavers
Licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)
```

## Repository structure

./images/clara-bw/ - screensaver images  
./preview/ - preview thumbnails for the README

## Preview

|                                                                     |                                                         |
| ------------------------------------------------------------------- | ------------------------------------------------------- |
| ![Reading on the hill](images/preview/kobo_reading_on_the_hill.jpg) | ![Forest night](images/preview/kobo_forest_night.jpg)   |
| ![Voyager](images/preview/kobo_probe_voyager.jpg)                   | ![KOreader time](images/preview/kobo_koreader_calm.jpg) |

## How to install

### Using KOreader

- connect your device to a computer using USB cable or via [SSH](https://github.com/koreader/koreader/wiki/SSH) protocol with any SFTP client (or just use `scp` command);
- create a new folder and copy files you like from `./images/clara-bw/` to it. 
  (I do recommend to create new folder under the `home` folder you chose in KOreader's settings since it helps keep your personal files organized, but really any folder will work as long as you can access it from the app);
- open KOreader and use top menu:
  
  ⚙ -> Screen -> Sleep Screen -> Wallpaper
  
  and select
  
   `Show random image from folder on sleep screen`
  
  then go and check
  
  `Border fill, rotation and fit`
  
  and make sure those are disabled:
  
  `Stretch cover to fit screen`, `Rotate cover for best fit`
  
  and filling option is set to:
  
  `No fill`
  
- (Optional) Adjust sleep screen message container:
  
  ⚙ -> Screen -> Sleep Screen -> Sleep screen message -> Container and position
  
  and set:

```
Box
Vertical position: 5%
Message opacity: 60%
```
  
- now press the power button and enjoy 🎉.

### Using Kobo's native app (Nickel)

It is rumored that you can connect the device and access the `KOBOereader` mass-storage drive to locate the hidden `.kobo` folder and create a `screensaver` subfolder.

## Download

You can download all images using the green **Code → Download ZIP** button on GitHub.

## Other

Find more about setting up KOreader [here](https://koreader.rocks/user_guide/).

>"Kobo" is a trademark of [Rakuten Kobo Inc](https://en.wikipedia.org/wiki/Kobo_Inc.).
>This repository is not affiliated with or endorsed by Rakuten Kobo.

>"KOReader" is an independent open-source [project](https://github.com/koreader/koreader) for e-readers.
>This repository is not affiliated with the KOReader project.