gitfiles
========

A collection of files used to customize my Git environment.

## Installation

1. Clone the repo, then symlink files used by Git/referenced in `.gitconfig`:

   ```sh
   $ git clone git://github.com/DavidCain/gitfiles.git
   $ ln -s gitfiles/.gitconfig_global ~/.gitconfig
   $ ln -s gitfiles/.gitignore_global ~/.gitignore
   $ ln -s gitfiles/git_template ~/.git_template
   ```

2. (Optional) install `diff-so-fancy` & configure for use:
    1. Install (as preferred): https://github.com/so-fancy/diff-so-fancy
    2. Set up as pager: `export GIT_PAGER="diff-so-fancy | less --tabs=4 -RFX"`
3. (Optional) install `ctags` for automatic tag updating
    1. Install preferred `ctags` implementation, make available in `$PATH`
    1. Run `git init` in any existing repositories to build hooks from template


(I use an install script in my [dotfiles][dotfiles] to automate the above process).

[dotfiles]: https://github.com/DavidCain/dotfiles
