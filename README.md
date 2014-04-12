Installation
============

To install, add the following lines to your `~/.bashrc` or `~/.bash_profile`:

    source <path_to_git_prompt_repo>/bashrgb
    source <path_to_git_prompt_repo>/prompt_helpers
    source <path_to_git_prompt_repo>/git_prompt

Or you can `ln -s` those 3 files into your `~/bin`:

    ln -s <path_to_git_prompt_repo>/bashrgb ~/bin
    ln -s <path_to_git_prompt_repo>/prompt_helpers ~/bin
    ln -s <path_to_git_prompt_repo>/git_prompt ~/bin

And then simply add one line to your `~/.bashrc` or `~/.bash_profile`:

    source git_prompt

Features
========

If you are not in a git repo, you will see your computer name and current folder, for example:

    caetano: ~/programs/git-prompt

If you are in a git repo, you will see in addition the current git branch and a status indicator, for example:

    caetano: ~/programs/git-prompt on master ?

The status indicator can be:

* Nothing: no changes
* `?`: untracked files
* `!`: modified/renamed files
* `.`: new files
* `-`: deleted files

