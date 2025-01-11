# dotfiles

```
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
git clone --bare git@github.com:joaodlf/dotfiles.git $HOME/.dotfiles
dotfiles checkout
```
(Files that already exist in the system will need to be deleted/moved, checkout again)

For eventual submodules:
```
dotfiles submodule init
dotfiles submodule update
```

reference: https://medium.com/@simontoth/best-way-to-manage-your-dotfiles-2c45bb280049
