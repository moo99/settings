# trevordmiller

_Personal setup for new machines_

---

# Home directory

- **Clone this repo:** inside `~/projects/`
- **Run script to symlink dotfiles to home directory:** `. ~/projects/settings/bootstrap.sh`
- **Install Vim plugins:** clone [Vundle](https://github.com/VundleVim/Vundle.vim), then `:BundleInstall`

---

# Automator

- Restore iCloud automator apps

---

# OS Config

- Time Machine backups
- Show hidden files: `defaults write com.apple.finder AppleShowAllFiles YES`, then `option + right click` finder icon and relaunch
- Set screenshot folder: `defaults write com.apple.screencapture location ~/Pictures/Screenshots/`, then `killall SystemUIServer`
- Turn on "Find My Mac"
- Turn on "Do Not Disturb" schedule
- Notification center match iPhone + Notification center keyboard shortcut
- Automatically hide Dock
- Internet accounts like Facebook, Twitter etc.
- Reminders + iCloud
- Calendar + iCloud
- Mail + iCloud
- Messages + iCloud

---

# Downloads

- [Karabiner](https://pqrs.org/osx/karabiner/index.html.en), then:
    - Update `private.xml` with `~/projects/trevordmiller-settings/karabiner/private.xml
    - "Key Repeat" settings:
        - Delay until repeat: 30ms
        - Key Repeat: 20ms
    - "Change f1...f12"
- [Seil](https://pqrs.org/osx/karabiner/seil.html.en), then:
    - caps lock -> fn
- Git latest
- Node + npm, then:
    - `n` + `n latest`)
    - Install latest (since Node doesn't ship with latest npm)
    - Install `parallelshell` and `browsersync` as global npm packages
- iTerm2, then:
    - link settings folder to `~/projects/trevordmiller-settings/iterm`
- Chrome
- Slate
- Anki
- Sketch (Mac app store)
- Skitch (Mac app store)
- Slack (Mac app store)
- Tweetbot (Mac app store)
- Spotify (Mac app store)
- All [Egghead gear setup apps and settings](https://trello.com/c/Emwk89vh/158-gear-setup), including Screenflow (Mac app store)

---

# Hardware

## Pok3r Keyboard

- DIP switch 3: On (caps lock to fn)
- Programming layer (Fn+R_Ctrl to start/stop recording)
  - VIM like HJKL
    - Left: FN + H then: FN + J then: PN
    - Down: FN + J then: FN + K then: PN
    - Up: FN + K then: FN + I then: PN
    - Right: already works ;)
    - Home: FN + I then: FN + H then: PN
