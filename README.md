# Finite Fields notes

Notes for the undergraduate Finite Fields course (Algebraic Cryptography - Mod 2) at University of Trento, academic year 2017/2018.

The pdf file is available in the Releases.

## Manual build

The notes are compiled via latexmk with the custom class `edoars-notes.cls` found in this repository as a submodule. You will need to have an up-to-date distribution of LaTeX and the Latexmk utility.

First clone the repository and submodules:

``` sh
git clone --recurse-submodules https://github.com/edoars/finite-fields-notes
```

Then build the notes with `make`:

``` sh
make all
```

The latex document will be compiled into `main.pdf`.
