## Bingo Board Generator (Web Edition)

This is a web version of [lazyguyy's bingo board generator](https://github.com/lazyguyy).
I figured running a web browser is easier than compiling a LaTeX template. You can access a
demo hosted by GitHub [right here](https://slyphix.github.io/bingo/).

You can customize field values by either uploading or linking a text file (think
[pastebin](https://pastebin.com) or [gist](https://gist.github.com)).
The first line will be used for the center field, the other field values will be selected
randomly (without replacement) from the remaining lines.

A sample board will be displayed as soon as a file has been read.
Use your browser's print preview to inspect the generated pages.

#### Pending features
- sensible error handling
- make the number of boards per page configurable
