# neovim


### 安装

ubuntu ppa
```sh
sudo add-apt-repository ppa:neovim-ppa/stable     #老版本稳点
sudo add-apt-repository ppa:neovim-ppa/unstable   #最新版本 非正式
```

一些依赖
```sh
sudo apt install nodejs npm
sudo apt install python-dev python-pip python3-dev python3-pip
sudo apt install python3-neovim python-neovim
sudo apt install silversearcher-ag exuberant-ctags
pip2 install pynvim
pip3 install pynvim 
sudo npm install -g neovim
```

neovim
```sh
sudo apt install neovim
```

### 配置

```sh
git clone https://github.com/whisper2chen/nvim.git  ~/.config/nvim
nvim +PlugInstall +qall
```


### 插件
参考[nvim打造golang开发环境](https://www.mrsong.me/2019/12/29/nvim/)
