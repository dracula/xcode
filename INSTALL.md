### [Xcode](https://developer.apple.com/xcode)

#### Git Installation

Clone the repository to stay updated:

```bash
git clone https://github.com/dracula/xcode.git
```

#### Manual Installation

Download the [GitHub `.zip` file](https://github.com/dracula/xcode/archive/main.zip) and extract it.

#### Homebrew Installation

Install via [dracula/homebrew-install](https://github.com/dracula/homebrew-install/blob/master/Casks/dracula-xcode.rb):

```bash
brew tap dracula/install
brew install --cask dracula-xcode
```

#### Theme Setup

**For Git/Manual installations only:**

1. Create the themes directory:

```bash
mkdir ~/Library/Developer/Xcode/UserData/FontAndColorThemes
```

2. Move `Dracula.xccolortheme` or `Alucard.xccolortheme` to the themes folder.

**For all installation methods:**

1. Open _Xcode > Preferences > Themes_
2. Select Dracula Theme
