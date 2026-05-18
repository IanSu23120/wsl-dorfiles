# wsl2 dotfiles
紀錄一些使用配置問題


## add enviroment variable
``` ~/.profile
export DISPLAY=${DISPLAY:-:0}
export XMODIFIERS="@im=fcitx"
export GTK_IM_MODULE=fcitx
export QT_IM_MODULE=fcitx
export GLFW_IM_MODULE=ibus
```


## use stow to link config




## ssh
在本機端加入agent 才能讓container使用ssh
1. add ssh-agent
``` sh
ssh-add ~/.ssh/id_ed25519
```
2. 進入container
``` sh
ssh -T git@github.com
```
