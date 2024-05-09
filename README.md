# latexextra.tex
A set of utilities for LaTeX documents.

Note that this is probably not something that you use right away. But hey, you can inspire yourself!

_Side note: Maybe I will comment the lines one day..._

In order to use this in your code, do:

```latex
\input{latexextra}
\showTODOtrue
\linkTODOfalse
\showNOTEtrue
```

You can use these variables:
- `\showTODO` hides all `\TODO{}` and `\TODOd{}`.
- `\linkTODO` hides forward-backward linkes from TODO lines.
- `\showNOTE` hides all `\note{}` and `\blocknote{}`.
