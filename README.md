# EXAM: Ex vivo allograft monitoring dashboard <img src="images/hex-exam.png" align="right" width=139 height=139 alt="" />

EXAM (ex vivo allograft monitoring) is an analytics dashboard for the hypothermic machine perfusion data in deceased-donor kidney transplantation.

## Background
Deceased-donor kidney allografts are exposed to injury during ex vivo transport due to the lack of blood oxygen supply. Hypothermic machine perfusion (HMP) effectively reduces the risk of delayed graft function in kidney transplant recipients compared to standard cold storage. However, no software implementation is available to read, process, and analyze HMP data for state-of-the-art visualization and quality control.

EXAM can read, process, and visualize raw data from the LifePort kidney transporter (Organ Recovery Systems, USA).

## Project description
EXAM was written in the R programming language and is based on the following tools.
* [Quarto Dashboard](https://quarto.org/docs/dashboards/), an interactive dashboard for R
* [plotly](https://plotly.com/graphing-libraries/), a graphics library for interactive charts
* [shiny](https://shiny.posit.co/), R package for interactive web applications
* [swt](https://github.com/Swisstransplant/swt), the Swisstransplant R package

A detailed project description is provided in the reference at the bottom.

## Screenshot
![Screenshot of the EXAM dashboard.](images/screenshot.png)

## Live dashboard
The dashboard is available at <https://data.swisstransplant.org/exam/>.

## Validation
We have compared the EXAM tool with numerous case reports created by the software ORS Data Station. We made one such [case report available](https://github.com/Swisstransplant/EXAM/blob/main/examples/LifePort%20DataStation%20Case%20Report%20ST-0001-Example.pdf); it can be compared to data from `ST-0001-Example` in the live dashboard.

## References
Schwab S, Steck H, Binet I, Elmer A, Ender W, Franscini N, Haidar F, Kuhn C, Sidler D, Storni F, Krügel N, Immer F. EXAM: Ex-vivo allograft monitoring dashboard for the analysis of hypothermic machine perfusion data in deceased-donor kidney transplantation. *PLOS Digit Health*. 2024;3(12):e0000691. [doi:10.1371/journal.pdig.0000691](http://dx.doi.org/10.1371/journal.pdig.0000691)
