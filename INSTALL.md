### [Xcode](https://developer.apple.com/xcode/)

#### Install manually

1. Download using the [GitHub .zip download](https://github.com/dracula/xcode/archive/master.zip) option and unzip them.

2. Create the custom themes folder:

```
mkdir ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

3. Move `Dracula.xccolortheme` file to this custom themes folder.

#### [Homebrew](https://brew.sh)

Easily install from [dracula/homebrew-install](https://github.com/dracula/homebrew-install/blob/master/Casks/dracula-xcode.rb):

``` sh
brew tap dracula/install
brew install --cask dracula-xcode
```

#### Activating theme

1. _Xcode > Preferences > Themes_
2. Select the Dracula theme
