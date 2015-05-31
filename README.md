# Lyx/Latex JTH PhD Thesis template
This repository contains a PhD thesis template for Jönköping University - School of Engineering.
It is a [Lyx 2.1](http://www.lyx.org/) template based on the KOMA-book class.
Lyx is a easy to use graphical front end to [Latex](http://www.latex-project.org/).
Since Lyx uses Latex in the background, the template (and everything created with it) can easily be exported to Latex from Lyx.

This template is loosely based on the [university of Leicester lyx template](http://www2.le.ac.uk/departments/mathematics/extranet/staff-material/staff-profiles/ab155/lyx) 

## Contents
- main.lyx - The main file, generate the full document using this file.
- titlepage1.lyx - Contains the title page. 
- Abstract.lyx
- Acknowledgements.lyx
- Statement of Co-Authorship.lyx
- SupplementsChapter.lyx - A chapter listing the titles of the appended papers
- Supplements.lyx - This file contains the actual content that will be reused in SupplementsChapter.lyx and Appended papers.lyx.
- Introduction.lyx
- Chapter1.lyx
- Chapter2.lyx
- Chapter3.lyx
- Appendix1.lyx
- Appended papers.lyx
- library.bib - A bibliography file containing some sources. Use JabRef or your favourite .bib editor to create or add your sources.
- marginsMain.lyx - Set the margins for the whole thesis here.
- jththesis.layout - Used in the background to get Lyx to display some of the Latex commands listed in jththesis.sty
- jththesis.sty - Latex style file containing changes to the KOMA script and some additional commands.
- varprop.sty - Contains commands to create variables with one or more properties. This is used to create the supplements data.
- Graphics\newSchoolLogo contains the new JTH logo, vectorized.
- Graphics\oldShoolLogo contains the outdated JTH logo, vectorized.
- It is adviced to use a seperate folder to store your graphics.