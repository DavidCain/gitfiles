gitfiles
========

A collection of files used to customize my Git environment.

## Installation

Clone the repo, then symlink files used by Git/referenced in `.gitconfig`:

    $ git clone git://github.com/DavidCain/gitfiles.git
    $ ln -s gitfiles/.gitconfig_global ~/.gitconfig
    $ ln -s gitfiles/.gitignore_global ~/.gitignore
    $ ln -s gitfiles/git_template ~/.git_template

(I use an install script in my [dotfiles][dotfiles] to do this)


[dotfiles]: https://github.com/DavidCain/dotfiles
