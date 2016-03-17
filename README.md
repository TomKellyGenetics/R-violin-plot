Modifications to the vioplot R package: https://cran.r-project.org/web/packages/vioplot/index.html

Citation of original packge:
Daniel Adler (2005). vioplot: Violin plot. R package version 0.2. http://wsopuppenkiste.wiso.uni-goettingen.de/~dadler

additional parameters:
`col`, `border`, `rectCol` - existing functions vectorised to give colours for each violin respectively

`lineCol` - added control of boxplot border and lines with vectorised colours for each violin as above

`main`,` sub`, `xlab`, `ylab` - added title specfication within function for consistency with familiar usage, e.g., with boxplot / beanplot

Clone to local machine with

`cd <working_dir>`

`git clone git@github.com:TomKellyGenetics/R-violin-plot.git`

Load function into R with

`source("<working_dir>/R-violin-plot/my.vioplot.R")`

Run `my.vioplot()` as you would `vioplot()` with additional graphical parameters intended to be familiar to `boxplot()` users


Note for novices: it is not advisable to clone a git repo into a directory already tracked with git / version control. It is acceptable to use <working_dir> as the working directory of your R session but only if this directory is not already tracked by Git or RStudio Projects. If you are using version control for your R session please use another directory to source this script. 
