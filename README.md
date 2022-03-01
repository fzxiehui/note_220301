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
