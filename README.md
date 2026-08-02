# A fun Sokoban implementation for KLayout

See https://en.wikipedia.org/wiki/Sokoban for an
explanation of the game.

To install, copy the `sokoban.lym` file into the `pymacros` folder
in your Klayout home directory. This directory is found

* at `c:\users\<you>\KLayout\pymacros` on Windows
* at `~/.klayout/pymacros` on Linux

And run the script from KLayout's Macro IDE or
using the "Macros/Examples/Sokoban" menu.

It reads levels from files called `*.sok` next to this
source file. One level is integrated for demonstration.

Sources for levels are:
* https://www.sourcecode.se/sokoban/levels.php
  (Download as .txt and rename to .sok)
* https://github.com/Alonso-del-Arte/sokoban-levels

Disclaimer: the `.sok` parser is very simplistic.

