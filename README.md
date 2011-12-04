# GitHub Theme

This is a GitHub theme for TextMate and vim.

## TextMate

The basic colors are defined, but I'm sure it can be improved.

To use, copy it to ~/Library/Application\ Support/TextMate/Themes/

Or simply run:

`$ cd ~/Library/Application\ Support/TextMate/Themes && curl -O https://raw.github.com/sbecker/github_textmate_theme/master/GitHub.tmTheme`

Copyright (c) 2008 Scott Becker, released under the MIT license

### Changelog

 **2011-12-4**

  * `String` with *light* background
  * `Function Parameters` now italic
  * `Library objects` now bold and colored
  * `Function Meta Call Arguments` now italic
  * `Function Call` normal

## vim

The TextMate theme wars transferred with [`coloration`](http://coloration.sickill.net/) and was optimized by hand. Works also for 256-bit color terminal and gui.

To use it, copy `github.vim` to `~/.vim/colors/github.vim`.

And activate it in vim with the command: `:colorscheme github` or make it persistent in your `.vimrc`.

But there is more to optimize:

 * colors for builtins for python
 * literals like \n not highlighted
 * italics don't work