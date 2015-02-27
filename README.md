[![Melpa Status](http://melpa.org/packages/default-text-scale-badge.svg)](http://melpa.org/#/default-text-scale)
[![Melpa Stable Status](http://stable.melpa.org/packages/default-text-scale-badge.svg)](http://stable.melpa.org/#/default-text-scale)

# Easily adjust the font size in all Emacs frames

This package provides commands for increasing or decreasing the
default font size in all GUI Emacs frames -- it is like an Emacs-wide
version of `text-scale-mode`.

It works by adjusting the height of the `default` face in the
`user` theme, which is always combined with any other loaded
themes.

## Installation

### Manual

Ensure `default-text-scale.el` is in a directory on your load-path, and
add the following to your `~/.emacs` or `~/.emacs.d/init.el`:

``` lisp
(require default-text-scale)
(global-set-key (kbd "C-M-=") 'default-text-scale-increase)
(global-set-key (kbd "C-M--") 'default-text-scale-decrease)
```

### MELPA

If you're an Emacs 24 user or you have a recent version of
`package.el` you can install `default-text-scale` from the
[MELPA](http://melpa.org) repository. The version of
`default-text-scale` there will always be up-to-date.

``` lisp
(global-set-key (kbd "C-M-=") 'default-text-scale-increase)
(global-set-key (kbd "C-M--") 'default-text-scale-decrease)
```

## About

Author: Steve Purcell <steve at sanityinc dot com>
Homepage: https://github.com/purcell/default-text-scale

This little library was extracted from the author's
[full Emacs configuration](https://github.com/purcell/emacs.d), which
readers might find of interest.

<hr>

[![](http://api.coderwall.com/purcell/endorsecount.png)](http://coderwall.com/purcell)

[![](http://www.linkedin.com/img/webpromo/btn_liprofile_blue_80x15.png)](http://uk.linkedin.com/in/stevepurcell)

[Steve Purcell's blog](http://www.sanityinc.com/) // [@sanityinc on Twitter](https://twitter.com/sanityinc)

