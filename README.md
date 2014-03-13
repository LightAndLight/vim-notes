This fork of xolox's vim-notes repo allows unimpeded usage of a preceding
%-sign in the title of a note. This is to facilitate the use of LaTeX in
conjunction with vim-notes.

Example:

test.note
```TeX
%test

\documentclass{article}
\title{Test Document}
\author{Isaac Elliott}

\begin{document}
    \maketitle
    ...
\end{document}

```

For information on vim-notes usage see: https://github.com/xolox/vim-notes/blob/master/README.md
