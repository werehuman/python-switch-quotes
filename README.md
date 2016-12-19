# python-switch-quotes

![Travis-CI build status](https://api.travis-ci.org/werehuman/python-switch-quotes.svg?branch=master)

Converts strings like `'this'` to strings like `"this"`.
Supports raw strings, docstrings and strings with escaped quotes.

![Example](http://i.imgur.com/xvjsbbs.gif)

# How to use

Clone this repository, open `python-switch-quotes.el` in Emacs and run `M-x package-install-from-buffer RET`.

Then put into your `init.el`:

```emacs
(require 'python-switch-quotes)
(define-key python-mode-map (kbd "C-c '") 'python-switch-quotes)
```
