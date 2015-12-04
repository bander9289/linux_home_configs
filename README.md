# Brandon Anderson's default config files that live in home directory of Linux.

```
git init
git remote add origin git@github.com:bander9289/linux_home_configs.git
git fetch
git checkout -t origin/master
```

# Other setup notes

## Trackpoint middle click also pastes when scrolling
.Xmodmap moves paste to right-click

## Access unstable packages from debian as source to build
sudo echo "deb-src http://http.debian.net/debian sid main contrib non-free" > /etc/apt/sources.list.d/unstable.list

## Lock screen from i3
Add 'bindsym Mod1+Control+l exec slock'  to ~/.i3status.conf
