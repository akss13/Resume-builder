Resume builder
=========================

A simple way to build resume based on deedy resume template. It creates a static url for generated resume.

## What's going on?
The project is based on [deedy resume](https://github.com/deedy/Deedy-Resume). Once you make changes to the source file(<b>.tex</b>) in your preferred editor and push, it generates the output pdf file in the repo itself. Then you may add the repo as a submodule to your other git repo.

## Notes
- The pdf file is generated using xelatex.
- For publications to work compile the <b>.tex</b> first. Then compile <b>.bib</b> file. Then compile <b>.tex</b> again.
- Remember to pull changes before commiting changes again since <b>.pdf</b> file gets uploaded to the same branch.