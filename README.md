# Book Retypesetting

## Robin Hartshorne, *Algebraic Geometry*

This project contains an unofficial retypesetting of Robin Hartshorne's *Algebraic Geometry* (Graduate Texts in Mathematics 52). It includes a faithful edition, a corrected edition, and a separate errata document keyed to the printed page numbers.

| Document | PDF | LaTeX |
| --- | --- | --- |
| Faithful edition | [PDF](Hartshorne-Algebraic-Geometry/hartshorne-faithful.pdf) | [Source directory](Hartshorne-Algebraic-Geometry/hartshorne-faithful/) |
| Corrected edition | [PDF](Hartshorne-Algebraic-Geometry/hartshorne-corrected.pdf) | [Source directory](Hartshorne-Algebraic-Geometry/hartshorne-corrected/) |
| Errata | [PDF](Hartshorne-Algebraic-Geometry/hartshorne-errata.pdf) | [Main source](Hartshorne-Algebraic-Geometry/hartshorne-errata.tex) · [Section files](Hartshorne-Algebraic-Geometry/errata/) |

Build each edition with XeLaTeX. Run the corresponding command from its source directory.

- `latexmk -xelatex hartshorne-faithful.tex`
- `latexmk -xelatex hartshorne-corrected.tex`

Build the errata from the `Hartshorne-Algebraic-Geometry` directory with `latexmk -xelatex hartshorne-errata.tex`.
