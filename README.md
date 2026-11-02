# Dotfiles Template

## Personal Files

Put personal files in `users/<name>/` and link them with `python3 symlink.py
--user <name>`. For example, add `users/<name>/.gitconfig.local` with your git
name and email.

## Vim Bindings

To enable Vim bindings in zsh, readline, and IPython, add
`export DOTFILES_VIM_MODE=1` to `users/<name>/profile/local`.
