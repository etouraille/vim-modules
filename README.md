#Load Vim Plugin With pathogen#

Pathogen allow you to load vim plugins. There is also an other popular solution Vundle, which permits to keep track of your bundle in the .vimrc file.

[Pathogen is on Github](https://github.com/tpope/vim-pathogen) : Intallation is detailed there. The key point is that you have to copy in ~/.vim/autolaod directory and call it in your .vimrc : The call is sweet : patogen#infect().

The source 

#Keep Track of vim plugin with git submodules#

A submodule is often a bunch of files located in .vim/bundle/, tracked in a git repo. Submodule applied perfectly to that case. each bundle can be considered as a repo, and if you keep track of that repo, you can simply get them once you change your linux distribution. Simplest as simple. 

Here is an example of how create that repo and add the exemple nerdTree module as a git submodule. 

````bash
cd ~/.vim/bundle
    git init # Create git repo
    git submodule add https://github.com/scrooloose/nerdtree.git #add vim plugin as a git submodule.
    git commit -am 'Add module NERDTree'
```
You should add as many submodules as needed.
Then push to your remote repos and keep track of your vim bundles.
