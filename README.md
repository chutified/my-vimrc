# .vimrc
These are my VIM files. Use at your own risk.

### Requirements: vim-plug (<a href="https://github.com/junegunn/vim-plug">github</a>)
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

### Installation
```bash
$ git clone https://github.com/chutified/myvim.git \
    && mv -f myvim ~/.vim/ \
    && echo "source ~/.vim/myvim/sources.vim" > ~/.vimrc \
    && vim +PlugInstall +qa
```
