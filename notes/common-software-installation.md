# Common Software Installation

## System Prerequirement

My operation system is `ubuntu 22.04`.

## Install `zsh`

```bash
$ sudo apt install zsh
$ chsh -s /bin/zsh # set zsh as default shell
```

## Install `oh-my-zsh`

```bash
sh -c "$(curl -fsSL https://gitee.com/shmhlsy/oh-my-zsh-install.sh/raw/master/install.sh)"
vim ~/.zshrc # ZSH_THEME="random"
```

## Install `space vim`

```bash
curl -sLf https://spacevim.org/cn/install.sh | bash
```
