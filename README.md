# Yugabyte GIN slides

A slideshow for an internal YQL meeting on Yugabyte GIN indexes.

# Compile

The slides are made using LaTeX with beamer.  See the small
[Makefile][makefile] under `src` for full details.  If you're not familiar with
it, simply

1. install `xelatex`
1. `cd src`
1. `make`
1. open `main.pdf`

You can chose a different TeX compiler using `make TC=pdflatex`, for example.

# Present

Use `pdfpc` to open `main.pdf` in a presentation-friendly way.

# License

See [`LICENSE.txt`][license].

[license]: ./LICENSE.txt
[makefile]: ./src/Makefile
