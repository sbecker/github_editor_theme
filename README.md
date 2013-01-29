# GitHub Theme

This is a GitHub theme for TextMate, Sublime Text and Vim.

## Using with TextMate 1

To install it:

`$ cd ~/Library/Application\ Support/TextMate/Themes && curl -O https://raw.github.com/sbecker/github_editor_theme/master/GitHub.tmTheme`

## Vim

To install it:

`$ cd ~/.vim/colors/ && curl -O https://raw.github.com/sbecker/github_editor_theme/master/github.vim`

To activate it in vim, run the command `:colorscheme github` or make it persistent in your `.vimrc`.

### Info

The TextMate theme was transferred with [`coloration`](http://coloration.sickill.net/) and was optimized by hand. Works also for 256-bit color terminal and gui.

But there is more to optimize:

 * colors for builtins for python
 * literals like \n not highlighted
 * italics don't work

## Changelog

 **2011-12-4**

  * `String` with *light* background
  * `Function Parameters` now italic
  * `Library objects` now bold and colored
  * `Function Meta Call Arguments` now italic
  * `Function Call` normal

Copyright (c) 2008 Scott Becker, released under the MIT license
