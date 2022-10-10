# Getting Started

## Install `autoload``

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Open vim and install plugins

After opening vim, run the following command

```
:PlugInstall
```

## Compile YouCompleteMe core library

```
cd $HOME/.vim/plugins
python install.py
```

If this command fails with an error about a static vs dynamic library, you'll need to use
the python interpreter that came with your installation. A common remedy to this is to
use `/usr/bin/python3` instead of `python`.

