# What is toggle-one-window?
We often focus on reading the content in current window, hoping to temporarily maximize the current window, after reading the content, restore the window layout.

toggle-one-window mainly solves the use of scenes,the first call save the current window layout configuration and delete other windows, and second call will restore the window layout before the maximum operation.

## Installation
1. Clone or download this repository (path of the folder is the `<path-to-toggle-one-window>` used below).
2. In your `~/.emacs`, add the following two lines:
```elisp
(add-to-list 'load-path "<path-to-toggle-one-window>") ; add toggle-one-window to your load-path
(require 'toggle-one-window)
```

## Usage
* toggle-one-window
