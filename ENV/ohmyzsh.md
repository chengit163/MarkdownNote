### [ohmyzsh](https://ohmyz.sh/)

##### [github](https://github.com/ohmyzsh/ohmyzsh)

##### [gitee](https://gitee.com/mirrors/oh-my-zsh)

##### zsh

```sh
cat /etc/shells
echo $SHELL 
# sudo apt install zsh
# brew install zsh
```

#####  安装

```sh
sh -c "$(curl -fsSL https://gitee.com/mirrors/oh-my-zsh/raw/master/tools/install.sh)"
```

##### 主题

```sh
git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

```sh
cd ~/.oh-my-zsh/custom/themes && ls
```

vi ~/.zshrc
ZSH_THEME="powerlevel10k/powerlevel10k"
source ~/.zshrc
p10k configure

##### 卸载与更新

```sh
uninstall_oh_my_zsh
upgrade_oh_my_zsh
```

