# A Collection of Useful Mac Tools / Scripts / Links
Currently, highly personalised for my setup.

## 1. Only Active Items in the Dock.
[Source](https://www.idownloadblog.com/2022/05/24/how-to-show-only-running-apps-on-mac-dock/)

Show only active.
```bash
defaults write com.apple.dock static-only -bool true; killall Dock
```

Back to Normal.
```bash
defaults write com.apple.dock static-only -bool false; killall Dock
```

## 2. Battery Manager: Passthrough charging, extend life etc.
[AlDente](https://apphousekitchen.com)

## 3. Window Manager: Shortcuts for window sizes etc.
[Rectangle](https://rectangleapp.com)

## 4. Clipboard Manager: Multiple Items, History etc.
[Pelican](https://apps.apple.com/us/app/pelican-clipboard-manager/id1524721688?mt=12)

## 5. Free Up Storage: Remove Application caches etc.
1. Cache Folders
     1. `~/Library/Caches`
     2. `/Library/Caches`
     3. `~/Library/Application Support`
     4. `/Library/Application Support`
2. Free Apps
     1. Disk Inventory X
     2. Grand Perspective
3. Paid Apps
     1. DaisyDisk

## 6. Terminal: Cross platform, themes, built in Electron.
[Hyper](https://hyper.is)
