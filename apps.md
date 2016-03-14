# mac_setup

http://lapwinglabs.com/blog/hacker-guide-to-setting-up-your-mac <br>
https://github.com/matthewmueller/dots/blob/master/os/osx/apps.sh <br>
https://gist.github.com/brandonb927/3195465 <br>

https://github.com/engeld/setup <br>
https://github.com/engeld/dotfiles/ <br>

TODO: <br>
--> more automation like:
https://github.com/bkuhlmann/osx
https://github.com/kangax/osx
https://github.com/tylucaskelley/osx/blob/master/osx.sh
https://github.com/sajnikanth/osx/blob/master/install_apps

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

# Dev Tools
- Chrome / Chromium / Firefox
- PHPStorm / PHPStorm EAP
 - Add Config
 - Add Plugins
- Atom, Brackets, Sublime Text, MacVim
- BeyondCompare, Kaleidoscope
- Filezilla / Transmit+qlcolorcode
- Terminal / iTerm
 - Add Config
- Git / SourceTree / Tower
- Composer
- brew, brew cask
- MAMP Pro
- Sequel Pro (installed via MAMP)
- Mailcatcher (installed via MAMP, Adress: http://127.0.0.1:1080)
- Virtualbox / Vagrant

# Tools / Utilites
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

# Other Tools
- ArtRage
- Photoshop
- Deezer
- SoundCleod
- HipChat
- LibreOffice
- Microsoft Office Suite for Mac
- VLC
- Transmission

# Chrome Extensions
- cVim (Enabled)
- Https Everywhere (Enabled)
- iReader (Enabled)
- JSON Formatter (Enabled)
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
- jetzt
- EditThisCookie
- Full Page Screen Capture
- Ghostery
- Group Reddit Saved Links
- Postman (Offline App)
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

## HOMEBREW
    - [Readline](http://tiswww.case.edu/php/chet/readline/rltop.html)
    - [OpenSSL](https://openssl.org)
    - [GPG](https://www.gnupg.org)
    - [Bash](https://www.gnu.org/software/bash)
    - [Bash Completion](http://bash-completion.alioth.debian.org)
    - [tmux](http://tmux.sourceforge.net)
    - [Mosh](http://mosh.mit.edu)
    - [Vim](http://www.vim.org)
    - [asciinema](https://asciinema.org)
    - [ShellCheck](https://github.com/koalaman/shellcheck)
    - [Colorized Cat](https://github.com/jingweno/ccat)
    - [Tree](http://mama.indstate.edu/users/ice/tree)
    - [hr](https://github.com/LuRsT/hr)
    - [Git](http://git-scm.com)
    - [Mecurial](http://mercurial.selenic.com)
    - [Hub](https://github.com/defunkt/hub)
    - [GHI](https://github.com/stephencelis/ghi)
    - [CTags](http://ctags.sourceforge.net)
    - [Tag](https://github.com/jdberry/tag)
    - [jq](http://stedolan.github.com/jq)
    - [The Silver Surfer](https://github.com/ggreer/the_silver_searcher)
    - [FZF](https://github.com/junegunn/fzf)
    - [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml)
    - [HTTPie](https://github.com/jkbrzt/httpie)
    - [Ioping](https://code.google.com/p/ioping)
    - [Network Grep](http://ngrep.sourceforge.net)
    - [ImageMagick](http://www.imagemagick.org)
    - [Graphviz](http://www.graphviz.org)
    - [FLAC](https://www.xiph.org/flac)
    - [FFmpeg](http://ffmpeg.org)
    - [Gifsicle](http://www.lcdf.org/gifsicle)
    - [Node.js](http://nodejs.org)
    - [Phantom.js](http://phantomjs.org)
    - [Ruby](http://www.ruby-lang.org)
    - [Rust](https://www.rust-lang.org)
    - [Go](http://golang.org)
    - [Nginx](http://wiki.nginx.org)
    - [Pow](http://pow.cx)
    - [Memcached](http://memcached.org)
    - [Redis](http://redis.io)
    - [mycli](http://mycli.net/)
    - [lnav](http://lnav.org/)
    - [cloc](https://github.com/AlDanial/cloc)
    - [Watchman](https://github.com/facebook/watchman)

https://github.com/engeld/dotfiles/blob/master/conf/Brewfile
