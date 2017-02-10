### Course

This is material for a small tutorial on LaTeX and reproducible document generation.


### Install

For full productivity, install [LaTeX](https://www.latex-project.org/get) 
and an editor, for which I suggest [TexMaker](http://www.xm1math.net/texmaker/download.html).

To avoid installations, sign up at [sharelatex](https://de.sharelatex.com/register) or [overleaf](https://www.overleaf.com/signup).
Sharelatex seems to be [slightly better](https://www.google.de/search?q=sharelatex+vs+overleaf) and is open source.


### R

For reprodicible research, automated report generation and syntax-higlighted code inclusion, use [rmarkdown](http://rmarkdown.rstudio.com/).
To couple that with the power of LaTeX, you do have to install the latter locally.

Install a recent version of [R](https://github.com/brry/rhydro#install) and 
[Rstudio](https://www.rstudio.com/products/rstudio/download) (scroll down).

In R, run `install.packages("rmarkdown")`, which will also install knitr.

In Rstudio, go to `tools -> global options -> Sweave` and set "weave Rnw files using" to `knitr`.


### Test

To check whether everything is running, download and unzip the [example presentation](https://github.com/brry/latex/raw/master/PresLatexKnitrExample.zip).

Open `rdwd_pres.Rnw` and click "compile PDF" (CTRL+SHIFT+K).


### Schedule

**Part 1 (Berry, 1 hour)**

* 05 min: general LaTeX intro
* 10: doc structure, document class beamer
* 10: compiling
* 05: sectioning
* 10: including figures
* 05: onslide, pause, <+->
* 05: knitr intro
* 10: real life example

**10 min break**

**Part 2 (Irene, 45 min)**

* 05: document class
* 10: subsections, Table of contents (TOC)
* 10: tables (Website tex table generator)
* 10: equations
* 10: templates


