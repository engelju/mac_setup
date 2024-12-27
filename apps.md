# mac_setup

## Dev Tools
- Jetbrains Toolbox
    - Install IntelliJ and GoLand
    - Restore old layout:
        - ClassicUI: https://plugins.jetbrains.com/plugin/24468-classic-ui
        - https://dev.to/rytis/bring-back-old-intellij-theme-somewhat-5d6g
- Sublime Text
    - https://www.youtube.com/watch?v=Rb5wFjo3diE
- Visual Studio Code
- OrbStack
- Neovim + NormalVim
    - https://github.com/engelju/NormalNvim
- iTerm2

## Must-Have
- Firefox
    - Settings
    - about:config
        - layout.css.devPixelsPerPx to 1.1
    - Extensions
        - Adaptive Tab Bar Color
        - Bitwarden Passwort Manager
        - Enhancer for Youtube + Unhook
        - Old Reddit Redirect + Reddit Enhancement Suite
        - Refined Github
        - Stylus: Styles see Repo
        - uBlock Origin (Enabled)
        - Vimium
    - Lepton: https://github.com/black7375/Firefox-UI-Fix
- Microsoft Office Suite for Mac
- Dropbox / OneDrive
- Spotify
- VLC
- Transmission

## Tools / Utilites
- AltTab
- Caffeine
- CoconutBattery
- Hammerspoon
    - Shortcuts for Apps
        - cmd+1 fuer iTerm
        - cmd+2 fuer Firefox
        - cmd+3 fuer Sublime Text
    - Basic Window Manager
    - Blue Border for Active Window (window-highlight.lua)
    - Other Stuff
        - https://github.com/Adam13531/AdamsApple/tree/main/hammerspoon
        - https://www.hammerspoon.org/Spoons/
- Mission Control Plus
- [Easy Move+Resize](https://github.com/dmarcotte/easy-move-resize)
    - [Flexiglass](https://anjuta.com/flexiglass)
    - [SwiftShift](https://www.swiftshift.app/)
- Flux
- Appcleaner

### Outdated
- Karabiner / Seil
- [HyperSwitch](https://www.bahoom.com/hyperswitch/)
- [HyperDock](https://www.bahoom.com/hyperdock)
- [CDock](https://www.macenhance.com/cdock)
- [ShadowSweeper](https://www.irradiatedsoftware.com/labs/)

## HOMEBREW
Install Brewfile: https://homebrew-file.readthedocs.io/en/latest/installation.html

```bash
# tap repositories and their packages
tap homebrew/core
brew abseil
brew aom
brew aribb24
brew asciinema
brew autoconf
brew autoenv
brew automake
brew bat
brew bdw-gc
brew brotli
brew ca-certificates
brew cairo
brew ccat
brew certifi
brew cjson
brew colordiff
brew dav1d
brew fd
brew ffmpeg
brew flac
brew fontconfig
brew freetype
brew frei0r
brew fribidi
brew fzf
brew gettext
brew ghostscript
brew giflib
brew git-delta
brew gitu
brew gitui
brew glib
brew gmp
brew gnutls
brew graphite2
brew harfbuzz
brew highway
brew htop
brew httpie
brew icu4c@76
brew imagemagick
brew imath
brew jasper
brew jbig2dec
brew jpeg-turbo
brew jpeg-xl
brew jq
brew lame
brew lazydocker
brew lazygit
brew leptonica
brew libarchive
brew libass
brew libb2
brew libbluray
brew libde265
brew libdeflate
brew libevent
brew libgit2
brew libheif
brew libidn
brew libidn2
brew liblqr
brew libmicrohttpd
brew libnghttp2
brew libogg
brew libomp
brew libplacebo
brew libpng
brew libraw
brew librist
brew libsamplerate
brew libsndfile
brew libsodium
brew libsoxr
brew libssh
brew libssh2
brew libtasn1
brew libtiff
brew libtool
brew libunibreak
brew libunistring
brew libuv
brew libvidstab
brew libvmaf
brew libvorbis
brew libvpx
brew libvterm
brew libx11
brew libxau
brew libxcb
brew libxdmcp
brew libxext
brew libxrender
brew little-cms2
brew lpeg
brew lua
brew luajit
brew luarocks
brew luv
brew lz4
brew lzo
brew m4
brew mbedtls
brew miniupnpc
brew mise
brew molten-vk
brew mosh
brew mpdecimal
brew mpg123
brew mpv
brew msgpack
brew mujs
brew ncurses
brew neovim
brew nettle
brew oniguruma
brew opencore-amr
brew openexr
brew openjpeg
brew openssl@3
brew opus
brew p11-kit
brew pango
brew pcre
brew pcre2
brew pixman
brew protobuf
brew pv
brew python-packaging
brew python@3.13
brew rav1e
brew readline
brew ripgrep
brew rubberband
brew screen
brew sdl2
brew shaderc
brew shared-mime-info
brew shellcheck
brew snappy
brew speex
brew sqlite
brew srt
brew svt-av1
brew tesseract
brew the_silver_searcher
brew theora
brew tig
brew tmux
brew transmission-cli
brew tree
brew tree-sitter
brew uchardet
brew unbound
brew unibilium
brew usage
brew utf8proc
brew vapoursynth
brew vulkan-headers
brew vulkan-loader
brew w3m
brew webp
brew wget
brew x264
brew x265
brew xorgproto
brew xvid
brew xz
brew yarn
brew yazi
brew yq
brew yt-dlp
brew zeromq
brew zimg
brew zstd

tap homebrew/cask
cask alt-tab
cask appcleaner
cask coconutbattery
cask domzilla-caffeine
cask dropbox
cask easy-move+resize
cask elgato-stream-deck
cask firefox
cask flux
cask git-credential-manager
cask hammerspoon
cask iterm2
cask jetbrains-toolbox
cask jordanbaird-ice
cask microsoft-auto-update
cask microsoft-office
cask microsoft-teams
cask mission-control-plus
cask orbstack
cask spotify
cask steam
cask sublime-text
cask visual-studio-code
cask vlc
cask whatsapp
# nerd-fonts casks

tap pablopunk/brew

tap rcmdnk/file
brew brew-file

# App Store applications
appstore 426410278 Flexiglass (1.8)
```

