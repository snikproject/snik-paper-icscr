## About

Journal paper about the [SNIK](http://www.snik.eu) ontology for the *description of ontology* [call of the Semantic Web Journal](http://www.semantic-web-journal.net/calls).

## Contents

The following files are given in the repository (or directly in the `.zip` archive):

- `iosart2x.cls`, `iosart2x.cfg`, `ios1.bst` - LaTeX and BibTeX style files designed for IOS Press journal articles. Please do not change them. These files are already loaded in the respective template files;
- `paper.tex` is the paper itself;
- `paper.bib` is the BibTeX file of the paper;
- `compile` is the optional bash script that calls latexmk to compile the paper, you can also use pdflatex and bibtex directly but you may need to call them multiple times then;
- `show` is the optional bash script that calls `compile` and then opens the result in the default PDF viewer.
- `cycle.tex` generates the lifecycle image

## Layout and Style Instructions
Read [iosart2x.pdf](https://github.com/vtex-soft/texsupport.iospress-sw/archive/master.zip) for instructions on layout and style of the journal article. This document contains useful information regarding the structure of the document, proper tagging style, layout features, etc.

## Setup

- Install Git and obtain write access to the repository;
- Clone the repository;
- generate the lifecycle image cycle.pdf via `pdflatex cycle.tex`
- Install LaTeX style files (`iosart2x.cls`, `iosart2x.cfg`) in your TeX system (may not be necessary);
- Read the instructions (`iosart2x.pdf`) for the preparation of the document;
- Edit `paper.tex` and `paper.bib` to prepare the manuscript.

