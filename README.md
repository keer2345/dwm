## dotfiles
- [My dotfiles](https://github.com/keer2345/dotfiles)
## Install

```shell
git clone https://git.suckless.org/dwm --depth=1
git clone https://git.suckless.org/st --depth=1
git clone https://git.suckless.org/dmenu --depth=1
git clone https://git.suckless.org/slstatus --depth=1
```
```shell
make
sudo make clean install
```
```shell
sudo systemctl disable lxdm.service
cp /etc/X11/xinit/xinitrc .xinitrc
```

## Materials 
- https://space.bilibili.com/479651586
- https://zhuanlan.zhihu.com/p/183861786
- https://zhuanlan.zhihu.com/p/112536524
- https://zhuanlan.zhihu.com/p/346719806?ivk_sa=1024320u

## Configuration
### Alsa
```sh
yay -S alas-utils
```
Run `alsamixer` and press `F6` to check default sound card.

`cat ~/.asoundrc`:
```sh
defaults.pcm.card 1
defaults.pcm.device 0
defaults.ctl.card 1
```
```sh
amixer sget Master
```


## Other
- [My slstatus](https://github.com/keer2345/slstatus)
