# mac-setup
Basic setup steps for a new Mac to get it ticking along just hgow I like it. 

## System preferences
 - [ ] Trackpad gestures: Mission control swipe up with four fingers, App Exposé swipe down with four fingers
 - [ ] `Accessibility`>`Pointer Control`>`Trackpad Options...`: Enable three-finger drag

## Homebrew, terminal, command line tools
This includes the Xcode command line tools. 
 - [ ] Install Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 - [ ] iTerm2. `brew install iterm2`
 - [ ] Set iTerm2 navigation shortcuts: follow instructions [here](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x)
 - [ ] wget: `brew install wget`
 - [ ] tree, for displaying directory hierarchies: `brew install tree`
 
## Productivity
 - [ ] Maccy - clipboard manager `brew install maccy`
 - [ ] Magnet - window manager. Install in the App store

## Python: Anaconda
 - [ ] Download the command line installer: `wget https://repo.anaconda.com/archive/Anaconda3-2023.03-MacOSX-arm64.sh`
 - [ ] Run the script with `bash`: `bash Anaconda3-2023.03-MacOSX-arm64.sh`

## Git setup
 - [ ] Generate SSH keys and add them to github projects as required: `ssh-keygen`
 - [ ] Setup multiple `.gitconfig` files and specify the `core.sshCommand`: see [here](https://superuser.com/a/1664624/258941)
