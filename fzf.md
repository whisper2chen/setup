# fzf


## 安装
```sh
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## 配置
```sh
export FZF_DEFAULT_OPTS="--height 40% --layout=reverse --preview '(highlight -O ansi {} || cat {}) 2> /dev/null | head -500'"
```

## 快捷键
```sh
ctrl + r  #搜索命令历史记录
ctrl + t  or cd **<tab>触发 #快速检索目录
vi **<tab> #搜索文件并打开
```

