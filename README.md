# My OpenSUSE KDE Plasma 6

## Partitions

200 GB for root (`/`) and its subdirectories as Btrfs partition.

465 GB for `/home` as Btrfs partition.

37 GB (having 32 GB of RAM) as Swap partition (it is used to hibernate the system).


## Third-parts repositories

- **Packman**
- **Nvidia**


## KDE Plasma 6

- Global Theme: **Breeze Dark**
- Colors: **Breeze Dark**
- Application Style: **Breeze**
- Plasma Style: **Breeze**
- Window Decorations: **Monochrome Blur**
- Icons: **Tela yellow dark**
- Cursors: **Bibata Modern Ice**
- System Sounds: **Ocean**
- Splash Screen: **openSUSE**

## .profile

```
alias ls='_ls --color=auto'
alias ll='ls -alF'
alias cls='clear'

# export PATH=$HOME/.cargo/bin:$PATH
# export PATH=$PATH:/opt/anaconda3/bin
```

## .bashrc

```
source ~/.profile

export PS1='\[\e[1;32m\]\u@\h\[\e[0m\]:\[\e[1;34m\]\w\[\e[0m\]\$ '
```

## TODO

- Gestures
- Disable touchpad when mouse is plugged in
- Fingerprint
