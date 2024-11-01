H-BRS Thesis Template
=====================

Small and easy to modify thesis template for my students.


Features:
---------
- English / German template (reacts to Babel language selection)
- Proper title page
- Proper declaration
- Examplary outline


Structure:
----------
- Main file is `thesis.tex`, it includes the others
- Some standard configs (like your name) are in `thesis_config.tex`
- Main setup/style/imports file is `FrontBackmatter/preamble.tex`.
- Folders:
  - FrontBackmatter: stuff for setup and frame around your content
  - content: in case you want to split chapters off into files
  - pics: for your figures etc.


FAQ:
----
- Why not a .sty / .cls file?
  KISS: Keep it stupid simple. Newcomers often strugle with them and things
  shall be as easy to change / adapt as possible.
- Why pdfLatex and not luatex/xetex?
  Same as above and pdfLatex is still predominant. Nothing stops advanced
  users to go with these more modern engines, but this template should
  work in an easy way for novices too.


Other templates:
----------------

- https://berrendorf.inf.h-brs.de/lehre/abschlussarbeiten/index.html
- https://git.fslab.de/fsl/H-BRS_Latex_Vorlage
- https://github.com/MartinX3-EducationOrganization/hbrs-latex-vorlage-arbeit
- https://github.com/mas-group/project-report
- https://ctan.org/pkg/classicthesis

