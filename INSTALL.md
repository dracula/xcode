### [Xcode](https://developer.apple.com/xcode/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/xcode.git

Creating the custom themes folder:

    $ mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/

And a symbolic link to this custom themes folder:

    $ ln -s $DRACULA_THEME/Dracula.xccolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/Dracula.xccolortheme

_P.S.: Remember that you should replace `$DRACULA_THEME` with the actual directory for this command to work._

#### Install manually

1.  Download using the [GitHub .zip download](https://github.com/dracula/xcode/archive/master.zip) option and unzip them.
2.  Create the custom themes folder: `~/Library/Developer/Xcode/UserData/FontAndColorThemes/`
3.  Move `Dracula.xccolortheme` file to this custom themes folder.

#### Activating theme

1.  _Xcode > Preferences > Fonts & Colors_
2.  Select the Dracula theme
