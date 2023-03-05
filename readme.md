

git submodule init .
git submodule update .
cd ~/.oh-my-zsh
rm -rf custom
ln -s ~/dotfiles/.oh-my-zsh/custom custom
