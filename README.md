# My OpenSUSE KDE Plasma 6

## Installation notes

### Black screen

Use `nomodeset` and then remove it, otherwise trouble during resolution setup.

### Nvidia

Do not add third-part repositories during installation.

Follow [this](https://en.opensuse.org/SDB:NVIDIA_drivers) to install NVIDIA drivers. `zypper install-new-recommends` worked. When you reboot, you must reach secure boot.

## Partitions

Only one root partition.

38 GB (having 32 GB of RAM) as Swap partition (it is used to hibernate the system).


## Third-parts repositories

- **Packman**
- **Nvidia**


## KDE Plasma 6

- Global Theme: **Breeze Dark**
- Colors: **Breeze Dark**
- Application Style: **Breeze**
- Plasma Style: **Breeze**
- Window Decorations: **Monochrome Blur**
- Icons: **Tela Manjaro dark**
- Color: `#097969`
- Cursors: **Bibata Modern Ice**
- System Sounds: **Ocean**
- Splash Screen: **openSUSE**

## Zsh

Thema: `bira`

## Bash

### .profile

```
alias ls='_ls --color=auto'
alias ll='ls -alF'
alias cls='clear'

# export PATH=$HOME/.cargo/bin:$PATH
# export PATH=$PATH:/opt/anaconda3/bin
```

### .bashrc

```
source ~/.profile

export PS1='\[\e[1;32m\]\u@\h\[\e[0m\]:\[\e[1;34m\]\w\[\e[0m\]\$ '
```

## TODO

- Gestures
- Disable touchpad when mouse is plugged in
- Fingerprint
