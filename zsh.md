# zsh安装


### 安装
```sh
sudo apt install zsh
```

### oh-my-zsh
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

### oh-my-zsh 插件

#### zsh-syntax-highlighting
```sh
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

#### zsh-autosuggestions
```sh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

### zsh配置文件

#### 主题
```sh
ZSH_THEME="robbyrussell"  # default
ZSH_THEME="ys"
ZSH_THEME="simple"
```

```sh
plugins=( git zsh-syntax-highlighting zsh-autosuggestions )
```

#### 修改shell
```sh
ps #查看当前的shell
chsh -s /bin/zsh #修改shell为zsh
```
