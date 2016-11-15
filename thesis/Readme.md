## Thesis
This example has been extracted from the master thesis by Gideon Müller (2015), which is published here: http://www.fz-juelich.de/pgi/pgi-1/DE/Leistungen/MasterDiplomDr/_node.html

--------------------


This Readme will try to list all relevant dependencies which are not covered by TeX packages.

First of all, shell escape must be enabled via `--shell-escape` or `pdflatex -write-18`.
Secondly, gnuplot needs to be installed (not just the gnuplot tex package).

A list of the most important packages needed:
- xcolor
- tikz
- tikz-3dplot
- pgfplots
- pgfplotstable
- pgffor
- pgfmath

*Please note that the design in this thesis was in large parts taken from the classicthesis package*.

If you provide a Signature.pdf, you may make the declaration appear signed in it's pdf form.
If you provide a Coverimage.pdf, you may add it to the Coverpage, which needs to be compiled separately.


#### Usage
In order to  change the title etc., go into *Header.tex*.
For colors, line and graph stylings, go into *Styles.tex*.
Packages are added and most commands configured in *Settings_Tex.tex*.
Additional tikz/pgf commands and settings are done in *Settings_Tikz.tex*.