# Intro
Hi! 

## CouRse aims 
- Introduce you to R 
- Basic concepts in data analysis
- "Cool" visuals 

## CouRse outline
1. [Lesson 1: R basics](../lessons/lesson1.md)
2. [Lesson 2: More R](../lessons/lesson2.md)
3. [Lesson 3: A fun example](../lessons/lesson3.md)
4. [Lesson 4: Another potentially fun example.](../lessons/lesson4.md)
5. [Lesson 5: So shiny!](../lessons/lesson5.md) 

## What is R? 
- Statistical and graphical language
- Follower of [S](https://en.wikipedia.org/wiki/S_(programming_language))

## What is it good foR?  
- Data mining/analysis 
- Data visualization and graphics
- Statistics! 
- Glorified calculator? 

## How do I...
### Install R
Start off by downloading [R](https://cran.r-project.org/) and then [RStudio](https://www.rstudio.com/).
- [Installing R for Windows](installwindows.md)
- [Installing R for Mac](installmac.md)
- [Installing R for Unix](installunix.md)

## Is it installed? Does it Run? 
### Use R 
- We will get to more fun stuff later, but first things first: 
#### Run RStudio
- Click it! 

### Packages, Repositories, oh my!
- Packages are code (and other!) bundles. 
- Repositories are where packages are located. Most are in [CRAN](https://cran.r-project.org/web/packages/). [Bioconductor](https://www.bioconductor.org/packages/release/BiocViews.html) and also [github](https://github.com/trending/r). 
- More on this [here](http://r-pkgs.had.co.nz/) and [here](https://www.datacamp.com/community/tutorials/r-packages-guide). 
#### Install packages
From CRAN: 
``` 
install.packages("very_important_package")
```
From Bioconductor: 
``` 
source("http://bioconductor.org/biocLite.R")
biocLite("very_important_package")
```
Or (for the next release)
``` 
if (!require("BiocManager"))
    install.packages("BiocManager")
BiocManager::install("my_super_cool_package")
```
From github:
```  
install.packages("devtools")
library(devtools)
devtools::install_github("very_cool_developer/very_important_tool")
```
#### Load libraries 
```
library(very_important_package)
library(very_important_tool)
require(very_important_data)
```

## WheRe to get help
- https://www.rstudio.com/
- https://www.r-bloggers.com/
- https://www.statmethods.net/index.html

## OtheR useful stuff 
- https://plot.ly/r/
- https://shiny.rstudio.com/
- https://rmarkdown.rstudio.com/
- https://www.rstudio.com/resources/cheatsheets/ 
- http://swirlstats.com/
- https://www.tidyverse.org/
- https://www.listendata.com/p/r-programming-tutorials.html
- http://genomicsclass.github.io/book/
- https://twitter.com/@RLangTip 
- https://twitter.com/hashtag/rstats?src=hash
- http://serialmentor.com/dataviz/
- https://adv-r.hadley.nz/
- https://peerj.com/collections/50-practicaldatascistats/
- http://www-huber.embl.de/csama2018/#home
- https://elifesciences.org/labs/cad57bcf/composing-reproducible-manuscripts-using-r-markdown
