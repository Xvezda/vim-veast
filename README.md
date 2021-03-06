# veast.vim
![GitHub](https://img.shields.io/github/license/Xvezda/vim-veast)
[![Action Status](https://github.com/Xvezda/vim-veast/workflows/Vim%20CI/badge.svg)](https://github.com/Xvezda/vim-veast/actions)

Veast is a library for vim script which highly inspired by [lodash](https://github.com/lodash/lodash) and [underscore](https://github.com/jashkenas/underscore).

It contains useful helper functions, which provides efficient way to writing vim plugins.


## Usage

You can either directly include veast to your vim plugin project or make dependency by using plugin manager(e.g. pathogen, vim-plug etc.) to make it works.

### Direct method
```sh
# Create autoload
mkdir -p <your_project_path>/autoload
# Copy veast library
cp plugin/veast.vim <your_project_path>/autoload/
```

### Plugin manager method

e.g. vim-plug
```vim
call plug#begin()
Plug 'Xvezda/vim-veast'
" ...
call plug#end()
```

### Include

```vim
runtime! autoload/veast.vim
```


## Test

[vader.vim](https://github.com/junegunn/vader.vim) required

`make test`


## Use case

* [vim-nobin](https://github.com/Xvezda/vim-nobin)
