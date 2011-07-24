===========================================================
_complete-recent-args -- complete words from recent history
===========================================================

install
=======

put ``_complete-recent-args`` under ``$fpath``, restart zsh.


usage
=====

press ``^X.``, select word you want to insert.


histbang
========

by default, the words are directly substituted. to have histbangs for these
words substituted instead, set a zstyle:

zstyle :complete-recent-args use-histbang yes

this can be useful if you want to apply modifiers to the histbang expression.
typing a colon in the menu completion will also conveniently not insert a space
after the completed expression.
