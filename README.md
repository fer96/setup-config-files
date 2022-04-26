# Setup Config Files

An easy way to setup my personal settings for terminal and xcode

## Previous requirements

- [x]  Install [Homebrew](https://brew.sh/)
- [x] Install [Visual Studio Code](https://code.visualstudio.com)

## Terminal

1. Install [oh-my-zhs](https://ohmyz.sh)
2. Install [powerlevel9k](https://github.com/Powerlevel9k/powerlevel9k/wiki/Install-Instructions#step-2-install-a-powerline-font) theme or anyone that you want
3. Open ` .zhsrc`  file and replace their content with `.terminal-files/zhsrc` from this repo
4. __DO NOT FORGET__ Replace `USER-NAME` with your `user name` at `export ZSH="/Users/USER-NAME/.oh-my-zsh"` in `.zhsrc` file
5. Download __`Hack`__ font from [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) or any other font that you want
6. Open terminal preferences and `(cmd + ,)`
7. Go to profiles
8. Select add profile
9. Import `terminal-files/dark-colorful.terminal` profile and select as your default
10. Close and restart the terminal to see the changes

## Xcode

#### Codesnippets

1. Download `xcode-files/codesnippets` files or any other that you want
2. Open `~/Library/Developer/Xcode/UserData/CodeSnippets/`
3. Add your new snippets inside that folder
4. Close and restart Xcode

#### Sounds

1. Download `xcode-files/sounds` files or any other that you want
2. Open Xcode
3. Open Xcode Behaviors
4. Add one sound for any behaviour that you want

#### Theme 
1. Download `xcode-files/themes` from this repo
2. open `/Applications/Xcode.app/Contents/SharedFrameworks/DVTUserInterfaceKit.framework/Versions/A/Resources/FontAndColorThemes` 
3. Add `dark-colorful.xccolortheme` theme there
4. Select your new theme in Xcode
5. If you don't see your new theme in xcode just open one of the default xcode themes in any text editor and replace the content with your custom theme
