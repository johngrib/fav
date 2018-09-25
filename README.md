# fav-dir

* `fav` is a shell script that helps you save and jump to your favorite directories and vim session directories.

## How to use

* `fav add` : Add the current path to your favorites list.
* `fav rm` : Removes the current path from your favorites list.
* `fav list` : View your favorites list.

## Install

* `fav` is dependent on [fzf](https://github.com/junegunn/fzf ).

1. [install fzf](https://github.com/junegunn/fzf#installation )
2. `git clone git@github.com:johngrib/fav-dir.git`
3. `./fav-dir/install.sh`
4. Add `[ -f ~/.local/bin/fav-dir.sh ] && source ~/.local/bin/fav-dir.sh` to your `.bashrc` or `.bash_profile`
