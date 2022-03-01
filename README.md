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
