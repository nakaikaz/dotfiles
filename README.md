今まで管理していたファイルを移動  
$ cd ~/  
$ mkdir dotfiles  
$ mv .vimrc dotfiles  
$ mv .vim/colors dotfiles  
$ mv .vim/ftdetect dotfiles  
$ mv .vim/indent dotfiles  
$ mv .bash_profile dotfiles  
$ mv .wgetrc dotfiles  
$ mv Brewfile dotfiles 

シンボリックリンクを張る  
$ ln -sf ~/dotfiles/.vimrc ~/.vimrc  
$ ln -sf ~/dotfiles/colors ~/.vim  
$ ln -sf ~/dotfiles/ftdetect ~/.vim  
$ ln -sf ~/dotfiles/indent ~/.vim  
$ ln -sf ~/dotfiles/.bash_profile ~/.bash_profile  
$ ln -sf ~/dotfiles/.wgetrc ~/.wgetrc  
$ ln -sf ~/dotfiles/Brewfile ~/Brewfile  
