# Introduction to R 2018geo
2018.05.02<br>Person Lin

Introduction to R workshop material including R code, data and presentation at 2018 annual congress of Geological Society Located in Taipei &amp; Chinese Taipei Geophysical Society.

# Install 安裝
[軟體安裝介紹](https://yijutseng.github.io/DataScienceRBook/install.html)
1. [Install R 安裝R](https://cloud.r-project.org/)
2. [Install RStudio IDE 安裝RStudio整合開發軟體](https://www.rstudio.com/products/rstudio/download/#download)

## 安裝套件
```
install.packages(c("maps", "ggmap", "dplyr", "rgdal", "leaflet", "geosphere", "htmlwidgets", "xtable", "knitr",
                   "mapview", "automap", "here", "XML"))
```

## Run R in the cloud 在雲端跑R
1. [RStudio Cloud](https://rstudio.cloud/)

# R語言介紹

[An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf) R官方的R介紹電子書

[Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r) Free Introduction to R Programming Online Course | DataCamp免費R介紹課程

# Cheat sheets 速查表
[RStudio Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/)
1. [Base R](http://github.com/rstudio/cheatsheets/raw/master/base-r.pdf) R基本語法
2. [Advanced R](https://www.rstudio.com/wp-content/uploads/2016/02/advancedR.pdf) R進階語法
3. [RStudio IDE Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf) RStudio IDE說明
4. [R Markdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf) R Markdown 說明
5. [The leaflet package](https://github.com/rstudio/cheatsheets/raw/master/leaflet.pdf) leaflet互動地圖套件說明

# R coding style guide 程式碼風格指南

* [Google's R Style Guide](https://google.github.io/styleguide/Rguide.xml)
* [Style guide in "Advanced R" by Hadley Wickham](http://adv-r.had.co.nz/Style.html)
* [The tidyverse style guide](http://style.tidyverse.org/)

# Packages 套件介紹

## R packages for data science 資料科學家工具

[Tidyverse](https://www.tidyverse.org/)

* [ggplot2](http://ggplot2.tidyverse.org/), for data visualisation.
* [dplyr](http://dplyr.tidyverse.org/), for data manipulation.
* [tidyr](http://tidyr.tidyverse.org/), for data tidying.
* [readr](http://readr.tidyverse.org/), for data import.
* [purrr](http://purrr.tidyverse.org/), for functional programming.
* [tibble](http://tibble.tidyverse.org/), for tibbles, a modern re-imagining of data frames.
* [stringr](https://github.com/tidyverse/stringr), for strings.
* [forcats](https://github.com/hadley/forcats), for factors.

## Plot 繪圖類

[plotly](https://github.com/ropensci/plotly)An interactive graphing library for R 互動式繪圖

## Geoscience 地科類

[ETAS](http://cran.r-project.org/web/packages/ETAS/index.html) (Modeling earthquake data using Epidemic Type Aftershock Sequence model

[GRTo](http://cran.r-project.org/web/packages/GRTo/index.html): Tools for the analysis of Gutenberg-Richter distributions of earthquake magnitudes

[Rvelslant](http://cran.r-project.org/web/packages/Rvelslant/) Downhole Seismic Analysis in R

## GIS 地理資訊系統類

[mapedit](https://github.com/r-spatial/mapedit) Interactive editing of spatial data in R 互動式地圖編輯套件

[mapview](https://r-spatial.github.io/mapview/) Interactive viewing of spatial objects in R 互動式地圖展示套件

## Remote sensing 遙測類

[getSpatialData](https://github.com/16EAGLE/getSpatialData)

[RStoolbox](https://github.com/bleutner/RStoolbox)

# R resources R學習資源

[Awesome R](https://awesome-r.com/) A curated list of awesome R packages and tools.

[R Weekly](https://rweekly.org/) R週報，關於R的新知都在這！

[R 語言翻轉教室](http://datascienceandr.org/) 全中文R語言互動式教材

[GEOG 4/590: R for Earth-System Science](http://geog.uoregon.edu/bartlein/courses/geog490/index.html) 美國俄勒岡大學的R地球系統科學課程網站

[Data Analysis in the Geosciences](http://strata.uga.edu/8370/lecturenotes/introduction.html)喬治亞大學的地科資料分析課程網站

# R for MATLAB users
[R for MATLAB users 語法對照表 ](http://mathesaurus.sourceforge.net/octave-r.html)

[R package: **matlab**. Emulate MATLAB code using R](https://cran.r-project.org/web/packages/matlab/index.html)

[R package: **R.matlab**. Read and Write MAT Files and Call MATLAB from Within R](https://github.com/HenrikBengtsson/R.matlab)

[MATLAB® / R Reference, by David Hiebeler](http://www.math.umaine.edu/~hiebeler/comp/matlabR.html)

# R interface to Python

[reticulate: R interface to Python](https://blog.rstudio.com/2018/03/26/reticulate-r-interface-to-python/)

# R user group R使用者社群

[Taiwan R User Group / MLDM Monday](https://www.meetup.com/Taiwan-R/) 台灣最大R社群

[R-Ladies Taipei](https://www.meetup.com/R-Ladies-Taipei/) 女生專屬社群

# Other things to learn	其他可以學的東西

## Git 版本控制系統

1. Suzan Baert's [advice to beginners](https://suzan.rbind.io/2018/03/reflections-4-months-of-github/)
1. Suzan Baert's [Git note part 1](https://github.com/suzanbaert/Resources_and_Bookmarks/blob/master/GIT_01_Basics.md)
2. Suzan Baert's [Git note part 2](https://github.com/suzanbaert/Resources_and_Bookmarks/blob/master/GIT_02_Fixing_screwups.md)
3. Jenny Bryan's [Happy Git and GitHub for the useR](http://happygitwithr.com/)

Git Tutorial for Beginners: Command-Line Fundamentals

[![Git Tutorial for Beginners: Command-Line Fundamentals](https://img.youtube.com/vi/HVsySz-h9r4/0.jpg)](https://www.youtube.com/watch?v=HVsySz-h9r4)

## Docker
[Free Docker Books](https://github.com/TechBookHunter/Free-Docker-Books)

# Reference 參考文獻
1. 曾意儒Yi-Ju Tseng, [資料科學與R語言](https://yijutseng.github.io/DataScienceRBook/).
