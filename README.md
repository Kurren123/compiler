# The Elm Compiler on windows

You may have got an `Access violation` error when trying to run various elm commands on windows. The problem was with GHC (the compiler used to make the elm compiler). This version of the elm has been built from an older version of GHC (8.0.1) which doesn't have that bug, and any changes in the code required to work with that version were made.

Learn about the Elm programming language at [elm-lang.org](http://elm-lang.org/).


## Install

1. Install elm by following [these instructions][installer].
2. Download the [latest bugfix release](https://github.com/Kurren123/compiler/releases/download/0.19.0-bugfix/elm.zip), unzip and replace your elm.exe with the one just downloaded. For me the path was at `C:\Program Files (x86)\Elm\0.19\bin`
 [installer]: https://guide.elm-lang.org/install.html


## Help

[Original github thread](https://github.com/elm/compiler/issues/1797) discussing this issue.
