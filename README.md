# `intexgral` – A LaTeX package for typesetting integrals

## Description

The package provides a central macro `\integral` that helps typeset integrals. As it only contains one argument – the integrand – its use is heavily dependent of a *keyval* interface. The latter allows the user to customise many elements of an integral, including:

__On the package side__
- Adaptation of the style to physics papers convention.
- Selection of the order of limits input.

__On the macro side__
- Changing the symbol.
- Automate the composition of integrals with limits.
- Fine adjustment of differentials.
- Inclusion of the Jacobian.

The package also offers a couple of auxiliary macros to help enhance the use of some keys:

- `\NewLimitsKeyword` (and its variant) to associate keywords with common limits. 
- `\NewDifferentialKeyword` (and its variant) to associate keywords to common lists of differential (and Jacobian).
- `\differentials` to precisely place the differentials wherever the user wants to. 

## Author

This package is maintained by Valentin Dao: vdao.texdev@gmail.com

Contribution: Anthony Saint-Criq

## Licence

Released under the LaTeX Project Public License v1.3c or later. See https://www.latex-project.org/lppl.txt

This work has the LPPL maintenance status `maintained`.

## Files

The bundle contains the following files:
```
README.md               This file.
intexgral.sty           The package itself.
intexgral-doc-en.pdf    The english package documentation in PDF format. 
intexgral-doc-fr.pdf    The french package documentation in PDF format. 
intexgral-doc-en.tex    The master file that produced intexgral-doc-en.pdf.
intexgral-doc-fr.tex    The master file that produced intexgral-doc-fr.pdf.
```

