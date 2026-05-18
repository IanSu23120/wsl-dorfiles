# wsl2 dotfiles


## add enviroment variable
``` ~/.profile
export DISPLAY=${DISPLAY:-:0}
export XMODIFIERS="@im=fcitx"
export GTK_IM_MODULE=fcitx
export QT_IM_MODULE=fcitx
export GLFW_IM_MODULE=ibus
```


## use stow to link config
