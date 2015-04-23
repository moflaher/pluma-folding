Code Folding for Pluma
========================

A simple plugin that adds keyboard-based code folding to Pluma.

Installation
--------------

- Move `folding.pluma-plugin` and `folding.py` into `~/.config/pluma/plugins`
- In Pluma, go to Edit &rarr; Preferences &rarr; Plugins to enable the plugin.

Usage
--------

* `Alt-Z` on selected lines will collapse them
* `Alt-Z` on an indented block's top line will collapse that block
* `Alt-Z` on a folded block will expand it
* `Alt-X` will collapse all blocks on the deepest indention column (you can keep pressing Alt-X until all indention levels are folded)
* `Shift-Alt-X` will expand all the collapsed blocks


Note
--------
Used https://github.com/aeischeid/gedit-folding.git for Fold Deepest modifications.
