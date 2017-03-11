# Justin Schulz's .vimrc.local

## Set Up

This is my local vim config, built on top of pivotal's vim-config with some changes I personally find useful. While I love pivotal's config, nothing here depends on using their set up.

1. If you wish to use pivotal's setup, [clone their project and follow their setup instructions](https://github.com/pivotal/vim-config).
  Otherwise, add this line to the bottom of your `~/.vimrc` file:

  ```
  if filereadable($HOME . "/.vimrc.local")
    source ~/.vimrc.local
  endif
  ```
2. Symlink the `.vimrc.local` in this project to `~/.vimrc.local`:

  ```
  ln -s ./.vimrc.local ~/.vimrc.local
  ```

Enjoy!
