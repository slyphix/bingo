## Bingo Board Generator (Web Edition)

**Disclaimer:** I wrote this over the course of three days. The code base is a mess.

This is a web version of [lazyguyy's bingo board generator](https://github.com/lazyguyy/bingo-generator).
I figured running a web browser is easier than compiling a LaTeX template. You can access a
demo hosted on GitHub [right here](https://slyphix.github.io/bingo/).

You can customize field values by either uploading or linking to a text file (think
[pastebin](https://pastebin.com) or [gist](https://gist.github.com)).
The first line will be used for the center field, the other field values will be selected
randomly (without replacement) from the remaining lines.

Note, however, that your browser's security policies might prohibit accessing a text file
depending on where it originates from, so linking a text file might not always work.

A sample board will be displayed as soon as a file has been read.
Use your browser's print preview to inspect the generated pages.

#### Pending features
- sensible error handling
