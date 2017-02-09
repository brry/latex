### small latex course


### LaTeX on computer

https://www.latex-project.org/get/

http://www.xm1math.net/texmaker/download.html (or another editor, if you prefer)


### LaTeX online

The previous two installations can be avoided if you sign up at shareLatex or overleaf:

https://de.sharelatex.com/register

https://www.overleaf.com/signup

Seems like [sharelatex is slightly better](https://www.google.de/search?q=sharelatex+vs+overleaf), but use whatever.


### reprodicible research, automated report generation, code inclusion

https://www.rstudio.com/products/rstudio/download/ (scroll down, recent version highly recommended!)

in R, run     `install.packages("rmarkdown")`       (Will also install knitr)

in Rstudio: go to `tools -> global options -> Sweave` and set "weave Rnw files using" to `knitr`


### test

To check whether everything is running, download and unzip the [example presentation](https://github.com/brry/latex/raw/master/PresLatexKnitrExample.zip).

Open `rdwd_pres.Rnw` and click "compile PDF" (CTRL+SHIFT+K).
