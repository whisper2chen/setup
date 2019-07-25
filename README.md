# setup
ubuntu 安装开发环境


## 常用基础工具
`sudo apt-get install -y vim git curl silversearcher-ag`

---

## zsh & oh-my-zsh
### zsh安装 
  `sudo apt-get install -y zsh`
  
### oh-my-zsh
  `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
  
#### zsh插件安装
#### zsh-syntax-highlighting
  `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`
  
#### zsh-autosuggestions
  `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
  
### zsh配置文件
  `ZSH_THEME="ys"`
  `
    plugins=(
    git
    fasd
    zsh-syntax-highlighting
    zsh-autosuggestions
  )
  `
  
  
---


## fzf
  #### 安装
    `git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf`
    `~/.fzf/install`
  #### 配置文件
    `export FZF_DEFAULT_OPTS="--height 40% --layout=reverse --preview '(highlight -O ansi {} || cat {}) 2> /dev/null | head -500'"`
  
