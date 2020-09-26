# uio-master-latex-frontpage

A slightly modified version of the UiO master thesis template for latex.
This version introduces two quality of life changes:
1. You do **not** need to copy the contents of the duoforside folder into you latex folder, only the folder itself, avoiding a bloated directory.
2. It now works with revtex4-1, woop woop.

## How to use
It's almost the exact same, just add the folder path to the usepackage:
```
\usepackage{./duoforside/duomasterforside}
```
However, the folder name is hardcoded and must not be changed.

## Changes to make revtex work
Change line 20 of duoforside.tex to not use the T1 setting for the url package...

## Orignal source and author
The entire duoforside front page was created by Dag Langmyhr. For more information regarding the use, see:  
https://www.mn.uio.no/studier/master/duomasterforside-guide2019.pdf
