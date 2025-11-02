# NerdFetch
 A POSIX \*nix (Linux, macOS, Android, BSD, etc) fetch script using Nerdfonts (and others)

### Dependencies

- [Any Nerdfonts font](https://www.nerdfonts.com/font-downloads), [Cozette](https://github.com/slavfox/Cozette), or [Phosphor](https://github.com/phosphor-icons/homepage/releases/tag/v2.0.0)
- [POSIX.1-2017 compliant shell](#shells-tested)
- [Anything but Windows](#oses-tested)

#### How to switch fonts

- Nerdfonts is used by default
- Use `-c` for Cozette
- Use `-p` for Phosphor
- Use `-e` for Emojis

### To install and run
The only way to install this tweaked version of nerdfetch is to `git clone` the repo and move the `nerdfetch` file to a location in your PATH.
For more info scroll down to Manually Install.

#### Manually Install

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://raw.githubusercontent.com/acuccoder/NerdFetch/main/nerdfetch -o /usr/bin/nerdfetch
sudo chmod +x /usr/bin/nerdfetch
nerdfetch
```

#### Android with Termux

Copy-paste this into Termux:

```sh
curl -fsSL https://raw.githubusercontent.com/acuccoder/NerdFetch/main/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

#### Run once

Note that this will ***not*** install the program.

```sh
curl -fsSL https://raw.githubusercontent.com/acuccoder/NerdFetch/main/nerdfetch | sh
```

### Features

- Strong cross-OS compatability
- Not bloated
- Portable
- POSIX

### OSes tested

- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- Gentoo based Linux
- RedHat based Linux
- OpenSUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux
- BirbOS Linux
- macOS
- Android
- FreeBSD
- OpenBSD
- NetBSD
- OpenWrt

### Shells tested

- Bourne Again Shell (`bash`)
- Z Shell (`zsh`)
- Almquist Shell (`ash`), Debian Almquist Shell (`dash`)  
- KornShell (`ksh`), MirBSD KornShell (`mksh`)
- Oil Shell (`osh`)
- Yet Another Shell (`yash`)

### Known issue(s)

- `nsh` is currently unsupported (https://github.com/ThatOneCalculator/NerdFetch/issues/46)
