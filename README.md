[![Melpa Status](http://melpa.org/packages/default-text-scale-badge.svg)](http://melpa.org/#/default-text-scale)
[![Melpa Stable Status](http://stable.melpa.org/packages/default-text-scale-badge.svg)](http://stable.melpa.org/#/default-text-scale)
<a href="https://www.patreon.com/sanityinc"><img alt="Support me" src="https://img.shields.io/badge/Support%20Me-%F0%9F%92%97-ff69b4.svg"></a>

# Easily adjust the font size in all Emacs frames

This package provides commands for increasing or decreasing the
default font size in all GUI Emacs frames -- it is like an Emacs-wide
version of `text-scale-mode`.

It works by adjusting the height of the `default` face in the
`user` theme, which is always combined with any other loaded
themes.

It's handy for quickly adjusting the font size for readability or
impromptu screen-sharing.

**Note that as of Emacs 29, many users might prefer the built-in `global-text-scale-adjust` system.**

## Installation

Install `default-text-scale` from the [MELPA](http://melpa.org)
repository. The version of `default-text-scale` there will always be
up-to-date.

## Usage

You can then customize/enable the global minor mode
`default-text-scale-mode`, which binds <kbd>C-M-=</kbd> and
<kbd>C-M--</kbd> by default. Alternatively, bind the corresponding
commands yourself as desired.

## About

Author: Steve Purcell <steve at sanityinc dot com>

Homepage: https://github.com/purcell/default-text-scale

This little library was extracted from the author's
[full Emacs configuration](https://github.com/purcell/emacs.d), which
readers might find of interest.

<hr>

[💝 Support this project and my other Open Source work](https://www.patreon.com/sanityinc)

[💼 LinkedIn profile](https://uk.linkedin.com/in/stevepurcell)

[✍ sanityinc.com](http://www.sanityinc.com/)
