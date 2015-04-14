#Load Vim Plugin With pathogen#

Pathogen allow you to load specific plugins

[Pathogen on Github](https://github.com/tpope/vim-pathogen)

#Keep Track of vim plugin with submodule#

When you will reinstall your bundle, you will have simply to clone your repos bundle
Each blugin is a submodule, so that you can simply have last update. 

````bash
    cd ~/.vim/plugin
    git init
    git submodule add https://github.com/scrooloose/nerdtree.git
    git commit -am 'Add module NERDTree'
```
Then push to your repos.

