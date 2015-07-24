# mac_setup

http://lapwinglabs.com/blog/hacker-guide-to-setting-up-your-mac
https://github.com/matthewmueller/dots/blob/master/os/osx/apps.sh
https://gist.github.com/brandonb927/3195465

https://github.com/engeld/setup
https://github.com/engeld/dotfiles/

## first thing

0. install xcode from app store and command line tools
1. install homebrew & update
2. brew install coreutils   # Install GNU core utilities (those that come with OS X are outdated)
3. brew install findutils   # Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
4. brew install bash        # Install Bash 4
5. brew tap homebrew/dupes            
6. brew install homebrew/dupes/grep   # Install more recent versions of some OS X tools

## installed apps

http://macapps.link/
http://www.getmacapps.com/

Dev Tools
- Chrome / Chromium / Firefox
- PHPStorm / PHPStorm EAP
 - Add Config
 - Add Plugins
- Atom, Brackets, Sublime Text, MacVim
- BeyondCompare, Kaleidoscope
- Filezilla / Transmit+qlcolorcode
- Terminal / iTerm
- Git / SourceTree / Tower
- Composer
- brew, brew cask
- MAMP Pro
- Sequel Pro (installed via MAMP)
- Mailcatcher (installed via MAMP, Adress: http://127.0.0.1:1080)
- Virtualbox / Vagrant

Tools / Utilites
- Dropbox
- Flexiglass
- [Easy Move+Resize](https://github.com/dmarcotte/easy-move-resize)
- Karabiner / Seil
- CDock
- HyperDock
- HyperSwitch
- ShadowSweeper
- iStat Menus
- Bartender
- Geektool
 - Add Config
- Flux
- The Unarchiver
- TotalFinder
- Tunnelblick
- Appcleaner / AppZapper

Other Tools
- ArtRage
- Photoshop
- Deezer
- SoundCleod
- HipChat
- LibreOffice
- Microsoft Office Suite for Mac
- VLC
- Transmission

Chrome Extensions
- jetzt
- cVim (Enabled)
- EditThisCookie
- Full Page Screen Capture
- Ghostery
- Group Reddit Saved Links
- Https Everywhere (Enabled)
- iReader (Enabled)
- JSON Formatter (Enabled)
- Postman (Offline App)
- RES (Enabled)
- Stylish (Enabled)
 - Dark Wikipedia Rounded (Fixed Math Equations) (angepasst)
 - GitHub Dark
 - GitHub Wide
 - GitHub Gist Wide
 - Google - Material Design (angepasst)
 - Reddit Slate Nights 2.0 (Dark) (angepasst)
 - Youtube - Dark Grey
- Tampermonkey (Enabled)
 - YouTube Center: https://greasyfork.org/scripts/943-youtube-center/code/YouTube%20Center.user.js
- uBlock Origin (Enabled)
- Workflowy (Offline app)

## installed with brew
atomicparsley	cvs		htop-osx	lame		mpg123		php56		readline	unixodbc	zlib
autoconf	ffmpeg		httpie		libevent	ncurses		php56-xdebug	sip		w3m		zsh
automake	fish		icu4c		libpng		neovim		pkg-config	spidermonkey	wget
bdw-gc		fpp		imagemagick	libtool		node		portaudio	sqlite		x264
brew-cask	freetype	jpeg		libvo-aacenc	nspr		pyqt5		tig		xvid
cmake		gdbm		jq		libyaml		openssl		python3		tmux		xz
colordiff	gettext		jsawk		mercurial	pcre		qt5		tree		youtube-dl

- ack
- atomicparsley
- brew-cask
- colordiff
- ffmpeg
- fish
- fpp
- htop-osx
- httpie
- imagemagick
- jq
- jsawk
- libyaml
- mercurial
- mpg123
- ncurses
- neovim
- node
- php56-xdebug
- portaudio
- pyqt5
- python3
- tig
- tmux
- tree
- w3m
- wget
- youtube-dl
- zsh

https://github.com/engeld/dotfiles/blob/master/conf/Brewfile
