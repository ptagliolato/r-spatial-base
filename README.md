# r-spatial-base
Base docker image to containerize geospatial R-shiny applications.

Standalone usage example (e.g. to launch an interactive R shell): 

  sudo docker run -it ptagliolato/r-spatial-base:1.0.0 R --vanilla

------------------------------
Installed packages:

docker run ptagliolato/r-spatial-base:1.0.0 "R" "-e" "ppp<-installed.packages(); library(dplyr); paste(ppp[,1],ppp[,3],sep=':') %>% sort() %>% paste(collapse='\n') %>% cat" --vanilla

askpass:1.1
assertthat:0.2.1
backports:1.1.4
base:3.5.2
base64enc:0.1-3
BH:1.69.0-1
bitops:1.0-6
boot:1.3-20
brew:1.0-6
callr:3.3.1
class:7.3-15
classInt:0.3-3
cli:1.1.0
clipr:0.6.0
clisymbols:1.2.0
cluster:2.0.7-1
codetools:0.2-16
colorspace:1.4-1
commonmark:1.7
compiler:3.5.2
crayon:1.3.4
crosstalk:1.0.0
curl:4.0
datasets:3.5.2
DBI:1.0.0
desc:1.2.0
devtools:2.1.0
digest:0.6.20
docopt:0.6.1
dplyr:0.8.3
DT:0.7
e1071:1.7-2
ellipsis:0.2.0.1
evaluate:0.14
fansi:0.4.0
foreach:1.4.4
foreign:0.8-70
fs:1.3.1
gdalUtils:2.0.1.14
gdtools:0.1.9
ggmap:3.0.0
ggplot2:3.2.0
gh:1.0.1
git2r:0.26.1
glue:1.3.1
graphics:3.5.2
grDevices:3.5.2
grid:3.5.2
gridExtra:2.3
gtable:0.3.0
highr:0.8
htmltools:0.3.6
htmlwidgets:1.3
httpuv:1.5.1
httr:1.4.0
ini:0.3.1
iterators:1.0.10
jpeg:0.1-8
jsonlite:1.6
KernSmooth:2.23-15
knitr:1.23
labeling:0.3
later:0.8.0
lattice:0.20-38
lazyeval:0.2.2
leafem:0.0.1
leaflet:2.0.2
leaflet.extras:1.0.0
leafpop:0.0.1
littler:0.3.6
lubridate:1.7.4
magrittr:1.5
maptools:0.9-5
mapview:2.7.0
markdown:1.0
MASS:7.3-51.1
Matrix:1.2-15
memoise:1.1.0
methods:3.5.2
mgcv:1.8-27
mime:0.7
munsell:0.5.0
nlme:3.1-137
nnet:7.3-12
openssl:1.4.1
osmdata:0.1.1
parallel:3.5.2
pillar:1.4.2
pkgbuild:1.0.3
pkgconfig:2.0.2
pkgload:1.0.2
plogr:0.2.0
plyr:1.8.4
png:0.1-7
praise:1.0.0
prettyunits:1.0.2
processx:3.4.1
promises:1.0.1
ps:1.3.0
purrr:0.3.2
R.methodsS3:1.7.1
R.oo:1.22.0
R.utils:2.9.0
R6:2.4.0
raster:2.9-23
rcmdcheck:1.3.3
RColorBrewer:1.1-2
Rcpp:1.0.1
remotes:2.1.0
reshape2:1.4.3
rgdal:1.4-4
RgoogleMaps:1.4.3
rjson:0.2.20
rlang:0.4.0
rmarkdown:1.14
roxygen2:6.1.1
rpart:4.1-13
rprojroot:1.3-2
rstudioapi:0.10
rvest:0.3.4
satellite:1.0.1
scales:1.0.0
selectr:0.4-1
sessioninfo:1.1.1
sf:0.7-6
shiny:1.3.2
shinycssloaders:0.2.0
shinydashboard:0.7.1
shinydashboardPlus:0.7.5.9000
shinyjs:1.0
sourcetools:0.1.7
sp:1.3-1
spatial:7.3-11
splines:3.5.2
stats:3.5.2
stats4:3.5.2
stringi:1.4.3
stringr:1.4.0
survival:2.43-3
svglite:1.2.2
sys:3.2
tcltk:3.5.2
testthat:2.1.1
tibble:2.1.3
tidyr:0.8.3
tidyselect:0.2.5
tinytex:0.14
tools:3.5.2
units:0.6-3
usethis:1.5.1
utf8:1.1.4
utils:3.5.2
uuid:0.1-2
vctrs:0.2.0
viridis:0.5.1
viridisLite:0.3.0
webshot:0.5.1
whisker:0.3-2
withr:2.1.2
xfun:0.8
XML:3.98-1.20
xml2:1.2.0
xopen:1.0.0
xtable:1.8-4
yaml:2.2.0
zeallot:0.1.0
