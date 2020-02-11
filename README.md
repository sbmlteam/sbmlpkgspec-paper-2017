SBMLPkgSpec paper 2017 LaTeX source files<img width="14%" align="right" src=".graphics/sbml-badge.svg">
===================================================

This repository contains the source files for the 2017 BMC paper titled "SBMLPkgSpec: A LaTeX Style File for SBML Package Specification Documents".


Table of contents
-----------------

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Authors and history](#authors-and-history)
* [Acknowledgments](#authors-and-acknowledgments)


Introduction
------------

This repository contains the author's LaTeX source files for the paper 
[SBMLPkgSpec: A LaTeX Style File for SBML Package Specification Documents](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-017-2788-1) published in 2017.


Installation
------------

Clone this repository using the normal `git` software you would use, whether command line or graphical.  For example, using the git command line tools, you could run the following command in a shell terminal:

```
git clone git@github.com:sbmlteam/sbmlpkgspec-paper-2017.git
```


Usage
-----

The paper's main file is [sbmlpkgspec-paper.tex](sbmlpkgspec-paper.tex).  To compile it and produce a PDF file, use the following sequence:

```
pdflatex sbmlpkgspec-paper
bibtex sbmlpkgspec-paper
pdflatex sbmlpkgspec-paper
pdflatex sbmlpkgspec-paper
pdflatex sbmlpkgspec-paper
```


License
-------

Software produced by the SBML project is licensed under the [LGPL version 2.1 license](https://choosealicense.com/licenses/lgpl-2.1/).  Please see the [LICENSE](LICENSE) file for more information.


Authors and history
---------------------------

Michael Hucka wrote the paper in 2017.


Acknowledgments
---------------

Funding for this and other SBML work has come from the [National Institute of General Medical Sciences](https://www.nigms.nih.gov) via grant NIH R01&nbsp;GM070923 (Principal Investigator: Michael Hucka).

<br>
<div align="center">
  <a href="https://www.nigms.nih.gov">
    <img valign="middle"  height="100" src=".graphics/US-NIH-NIGMS-Logo.svg">
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.caltech.edu">
    <img valign="middle" height="130" src=".graphics/caltech-round.png">
  </a>
</div>
