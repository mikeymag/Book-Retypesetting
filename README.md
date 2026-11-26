# Book Retypesetting

## 1. Robin Hartshorne, *Algebraic Geometry*

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

## 2. Jürgen Neukirch, *Algebraic Number Theory*

This project contains an unofficial retypesetting of Jürgen Neukirch's *Algebraic Number Theory*, translated by Norbert Schappacher. It includes a faithful edition, a corrected edition, and a separate errata document keyed to the printed page numbers.

| Document | PDF | LaTeX |
| --- | --- | --- |
| Faithful edition | [PDF](Neukirch-Algebraic-Number-Theory/Neukirch_Faithful.pdf) | [Main source](Neukirch-Algebraic-Number-Theory/Neukirch_Faithful.tex) · [Chapter files](Neukirch-Algebraic-Number-Theory/Faithful/) |
| Corrected edition | [PDF](Neukirch-Algebraic-Number-Theory/Neukirch_Corrected.pdf) | [Main source](Neukirch-Algebraic-Number-Theory/Neukirch_Corrected.tex) · [Chapter files](Neukirch-Algebraic-Number-Theory/Corrected/) |
| Errata | [PDF](Neukirch-Algebraic-Number-Theory/Neukirch_Errata.pdf) | [Main source](Neukirch-Algebraic-Number-Theory/Neukirch_Errata.tex) |

Build the editions and errata with XeLaTeX. Run the corresponding command from the `Neukirch-Algebraic-Number-Theory` directory.

- `latexmk -xelatex Neukirch_Faithful.tex`
- `latexmk -xelatex Neukirch_Corrected.tex`
- `latexmk -xelatex Neukirch_Errata.tex`
