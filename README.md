今まで管理していたファイルを移動  
$ cd ~/  
$ mkdir dotfiles  
$ mv .vimrc dotfiles  
$ mv .vim/.vimrc.local dotfiles  
$ mv .vim/.vimrc.local.bundles dotfiles  
$ mv .bash_profile dotfiles  
$ mv .wgetrc dotfiles  
$ mv Brewfile dotfiles  

シンボリックリンクを張る  
$ ln -sf ~/dotfiles/.vimrc ~/.vimrc  
$ ln -sf ~/dotfiles/.vimrc.local ~/.vimrc.local  
$ ln -sf ~/dotfiles/.vimrc.local.bundles ~/.vimrc.local.bundles  
$ ln -sf ~/dotfiles/snippets/php_functions.php ~/.vim/snippets/php_functions.php  
$ ln -sf ~/dotfiles/.bash_profile ~/.bash_profile  
$ ln -sf ~/dotfiles/.wgetrc ~/.wgetrc  
$ ln -sf ~/dotfiles/Brewfile ~/Brewfile  
