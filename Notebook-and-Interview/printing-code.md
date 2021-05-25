# Printing code

## On a Mac
To print code on a mac, use homebrew to install enscript, then use enscript to  print the code.

```console
lilia@Deep-Thought ~ % brew install enscript
lilia@Deep-Thought ~ % enscript --color -CE -p code.ps main.cpp
```

Breakdown:
* `--color` - Uses color
* `-C` - Include line numbers
* `-E` - Highlights the code(like the code editor does)
* `-p` - Outputs the result to a postscript file if you want to look at the code before printing. Without this it will just go directly to the printer
* `code.ps` - Postscript file for the code to be outputed to, goes with the `-p` tag
* `main.cpp` - File to be printed

[Enscript website](https://linux.die.net/man/1/enscript)
