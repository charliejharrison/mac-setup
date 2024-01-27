# mac-setup
Basic setup steps for a new Mac to get it ticking along just how I like it. 

## System Settings
 - [ ] Trackpad gestures: Mission control swipe up with four fingers, App Exposé swipe down with four fingers
 - [ ] `Accessibility`>`Pointer Control`>`Trackpad Options...`: Enable three-finger drag

## Homebrew, terminal, command line tools
 - [ ] Install Homebrew:
   - [ ] `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`. This also installs the Xcode command line tools.
   - [ ] (On Apple Silicon) Add Homebrew install locations to the `$PATH`: `(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> ~/.zprofile`
   - [ ] `eval "$(/opt/homebrew/bin/brew shellenv)"`
   - [ ] Verify installation: `brew doctor`
 - [ ] iTerm2. `brew install iterm2`
 - [ ] Set iTerm2 navigation shortcuts: follow instructions [here](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x)
 - [ ] wget: `brew install wget`
 - [ ] tree, for displaying directory hierarchies: `brew install tree`
 
## Productivity
 - [ ] Maccy (clipboard manager): `brew install maccy`
   - [ ] Maccy preferences: tick "Paste automatically"
   - [ ] System Settings: add Maccy in `Privacy & Security`>`Accessibility`
 - [ ] Rectangle (window manager): [download](https://rectangleapp.com/) and install
       
## Python: Anaconda
 - [ ] Download the command line installer: `wget https://repo.anaconda.com/archive/Anaconda3-2023.03-MacOSX-arm64.sh`
 - [ ] Run the script with `bash`: `bash Anaconda3-2023.03-MacOSX-arm64.sh`

## Git setup
 - [ ] Generate SSH keys and add them to projects as required: `ssh-keygen`
 - [ ] Setup multiple `.gitconfig` files and specify the `core.sshCommand`: see [here](https://superuser.com/a/1664624/258941)

## Other software
 - [ ] Microsoft Office: `brew install microsoft-office`
 - [ ] Slack: `brew install slack`
