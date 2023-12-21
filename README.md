# A Collection of Useful Mac Scripts
Currently, highly personalised for my setup.

# 1. Show only Active Items in the Dock.
[Source](https://www.idownloadblog.com/2022/05/24/how-to-show-only-running-apps-on-mac-dock/)

Show only active.
```bash
defaults write com.apple.dock static-only -bool true; killall Dock
```

Back to Normal.
```bash
defaults write com.apple.dock static-only -bool false; killall Dock
```

