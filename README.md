# dotfiles
###备份
cd ~/ 去到根目录

mv .vimrc ~/Users/luolei/Dropbox/dotfiles/vimrc`

mv .zshrc  ~/Users/luolei/Dropbox/dotfiles/zshrc

ln -s ~/Users/luolei/Dropbox/dotfiles/vimrc .vimrc

ln -s ~/Users/luolei/Dropbox/dotfiles/zshrc .zshrc

###还原
git clone git@github.com:username/dotfiles.git dotfiles

rm -rf .vimrc .zshrc //首先删除自身机器上原有的dotfiles

ln -s dotfiles/vimrc .vimrc

ln -s dotfiles/zshrc .zshrc

