# note_220301
# install nvim

## download

```shell
 wget https://github.com/neovim/neovim/releases/download/v0.6.1/nvim-linux64.tar.gz
 sudo cp nvim-linux64.tar.gz /usr/local/
 cd /usr/local
 sudo tar -zvxf nvim-linux64.tar.gz
```
## install

```shell
vi ~/.bashrc
# add 
export PATH="/usr/local/nvim-linux64/bin:$PATH"
source ~/.bashrc
```

# install Vim-plug

## download

```shell
sudo apt  install curl

sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
## config 

```shell
mkdir ~/.config/nvim/
wget https://raw.githubusercontent.com/fzxiehui/vimdoc/master/init.vim
```
## install npm && neovim

```shell
sudo apt install npm
sudo npm install n -g
sudo n stable
sudo npm install -g neovim
```

## install pip && pip3

```shell
 sudo apt install python-pip
 sudo apt install python3-pip
```

## install pynvim

```shell
sudo pip3 install pynvim
sudo pip install pynvim
```

## install git

```shell
sudo apt install git
```

## check path

```shell
nvim
:checkhealth
可以忽略Perl 

```
## install plug
```shell
nvim
:PlugInstall
```

## install coc 
```shell
:CocInstall coc-clangd  # C++环境插件
:CocInstall coc-cmake  # Cmake 支持
 
:CocInstall coc-git    # git 支持

:CocInstall coc-pyright #python 


:CocInstall coc-sh     # bash 环境支持
###  :CocInstall coc-snippets # python提供 snippets
###:CocInstall coc-vimlsp # lsp
##:CocInstall coc-yaml   # yaml
##:CocInstall coc-syntax
##:CocInstall coc-pairs
```

## install ctags

```shell
sudo apt install ctags
```
