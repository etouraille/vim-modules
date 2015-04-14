#Load Vim Plugin With pathogen#

Pathogen allow you to load specific plugins

[Pathogen on Github](https://github.com/tpope/vim-pathogen)

The source 

#Keep Track of vim plugin with git submodules#

When you will reinstall your bundle, you will have simply to clone your repos bundle
Each blugin is a submodule, so that you can simply have last update. 

````bash
cd ~/.vim/bundle
    git init # Create git repo
    git submodule add https://github.com/scrooloose/nerdtree.git #add vim plugin as a git submodule.
    git commit -am 'Add module NERDTree'
```
You should add as many submodules as needed.
Then push to your remote repos

