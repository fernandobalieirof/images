# How to use this repo?

Run

- `git clone --bare https://github.com/fernandoonrails/dotfiles.git $HOME/dotfiles`
- `alias images="/usr/bin/git --git-dir=$HOME/images --work-tree=$HOME/Pictures" >> $HOME/.bashrc`
- source your .bashrc file
- `images config --local status.showUntrackedFiles no` so that it doesn't show all the untracked files
- `images checkout`
