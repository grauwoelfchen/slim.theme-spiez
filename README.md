# Spiez

The theme for simple login manager slim.

## Setup

### slim

```zsh
# install slim (z.B. in Gentoo Linux)
% sudo emerge -av x11-misc/slim

# use slim
% $EDITOR /etc/conf.d/xdm
DISPLAYMANAGER="slim"

# set rc (z.B. in Gentoo Linux)
% sudo eselect rc add xdm default
```

Then specify `current_theme` in `/etc/slim.conf`

```
# edit /etc/slim.conf
current_theme spiez
```


### theme

Prepare this theme via `git clone`

```zsh
% cd /usr/share/slim/themes
% sudo mkdir spiez
% sudo chown USER:USER spiez
% cd spiez
% git clone https://github.com/grauwoelfchen/slim.theme-spiez.git .
```


## License

BSD 2-Clause License
