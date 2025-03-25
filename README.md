# ascelike
Unofficial LaTeX class and bibliography style-files for ASCE documents 
(Amer. Soc. of Civil Engineers): journal manuscripts, camera-ready 
proceedings papers, and two-column likenesses of ASCE's journal articles

Version 3.0, March 2025

The package is freely available under the LaTeX Project Public License, 
version 1.1 or later.

The two main files are
  ascelike.cls - Document class file
  ascelike.bbx - Bibliographic entry style
  ascelike.cbx - Bibliographic citation style
  ascelike.bst - Bibliography style file - legacy version

Also included are example/documentation files:
  ascexmpl.tex - An example *.tex file, which also serves as documentation
                 of the options and usage of ascelike.cls 
  ascexmpl.bib - An example *.bib bibliographic data base
  ascexmpl.pdf - Output from ascexmpl.tex and ascexmpl.bib

With Version 3.0, bibliographies are produced with biblatex and the biber 
program.

The following supplementary files are REQUIRED by ascelike.cls:
ifthen.sty, setspace.sty, endfloat.sty, lineno.sty, biblatex.sty, babel.sty,
authblk.sty, caption.sty, float.sty, multicol.sty, newtxtext.sty, 
newtxmath.sty, and microtype.sty. Without these files, ascelike.cls will 
not work. All of these packages are available in the CTAN archive.

The ascelike package is also available on github.com.  Report problems 
and suggestions to Matthew R. Kuhn, kuhn_at_up.edu
