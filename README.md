# Brandon Anderson's default config files that live in home directory of Linux.

```
git clone git@github.com:bander9289/linux_home_configs.git .
```

# Other setup notes

## Trackpoint middle click also pastes when scrolling
.Xmodmap moves paste to right-click

## Access unstable packages from debian as source to build
sudo echo "deb-src http://http.debian.net/debian sid main contrib non-free" > /etc/apt/sources.list.d/unstable.list
