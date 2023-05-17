# EXAM: Ex vivo allograft monitoring dashboard <img src="images/exam.png" align="right" width=120 height=139 alt="" />

EXAM (ex vivo allograft monitoring) is an analytics dashboard for the analysis of hypothermic machine perfusion data in deceased-donor kidney transplantation.

## Background
Deceased-donor kidney allografts are exposed to injury during ex vivo transport due to the lack of blood oxygen supply. Hypothermic machine perfusion (HMP) effectively reduces the risk of delayed graft function in kidney transplant recipients compared to standard cold storage. However, there is no software implementation available to read, process and analyze HMP data for state-of-the-art visualization and quality control.

## Project description
EXAM was written in the R programming language and is based on the following tools.
* [flexdashbord](https://pkgs.rstudio.com/flexdashboard/), a interactive dashboard for R
* [plotly](https://plotly.com/graphing-libraries/), a graphics library for interactive charts
* [shiny](https://shiny.posit.co/), R package for interactive web applications
* [swt](https://github.com/Swisstransplant/swt), the Swisstransplant R package

A detailed project description is provided in the reference at the bottom.

## Screenshot
![Screenshot of the EXAM dashboard.](images/screenshot.png)

## Live demo
A live demo is available at [https://swisstransplant.shinyapps.io/EXAM/](https://swisstransplant.shinyapps.io/EXAM/).

## How to install 

1. Install [R](https://cran.rstudio.com/) and [RStudio](https://posit.co/download/rstudio-desktop/)
2. Open RStudio and install all dependencies. Enter the following commands in the Console:
```r
install.packages("flexdashboard")
install.packages("plotly")
install.packages("shiny")
install.packages("rmarkdown")
````

3. Install the swt packages
```r
install.packages("devtools")
devtools::install_github("Swisstransplant/swt")
```

4. Download `EXAM.Rmd` from here, open it in RStudio and press "Run Document"

## References
Schwab, S., Steck, H., Binet, I., Elmer, A., Ender, W., Franscini, N., Haidar, F., Kuhn, C., Sidler, D., Storni, F., Krügel, N., & Immer, F. (2023). EXAM: Ex vivo allograft monitoring dashboard for the analysis of hypothermic machine perfusion data in deceased-donor kidney transplantation. *Research Square*. [doi:10.21203/rs.3.rs-2713168/v1](https://doi.org/10.21203/rs.3.rs-2713168/v1)

## Terms of use

Copyright 2023, Swisstransplant

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.

Please let Swisstransplant know if you want to contribute to the project. Also let Swisstransplant know if you are a transplant organization or hospital and would like to use EXAM for quality control. For contact information, see https://www.swisstransplant.org/.
