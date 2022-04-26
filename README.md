# Setup Config Files

An easy way to setup my personal settings for terminal and xcode

## Previous requirements

- [x]  Install [Homebrew](https://brew.sh/)
- [x] Install [Visual Studio Code](https://code.visualstudio.com)

## Terminal

1. Install [oh-my-zhs](https://ohmyz.sh)
2. Install [powerlevel9k](https://github.com/Powerlevel9k/powerlevel9k/wiki/Install-Instructions#step-2-install-a-powerline-font) theme or anyone that you want
3. Open ` .zhsrc`  file and replace their content with `.terminal-files/zhsrc` from this repo
3.1. __DO NOT FORGET__ Replace `USER-NAME` with your `user name` at `export ZSH="/Users/USER-NAME/.oh-my-zsh"` in `.zhsrc` file

4. Download __`Hack`__ font from [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) or any other font that you want

5. Open terminal preferences and `(cmd + ,)`
6. Go to profiles
7. Select add profile
8. Import `terminal-files/custom-96.terminal` profile and select as your default
9. Close and restart the terminal to see the changes