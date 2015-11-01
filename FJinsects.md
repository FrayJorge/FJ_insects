---
title: "FJinsects"
author: "B"
date: "November 1, 2015"
output: html_document
---


<!---
use these command instead of the knit icon if you want the data and work loaded into the R workspace
  library(knitr)
  knit('FJinsects.rmd')
-->

To Do List
-------------------------

* Add X Axis label "Month" on Fig. 1
* Add X Axis label "Year" on Fig. 2
* Increase Fig.2 axis font size
* save as Jpeg


Data Sources
-------------------------

* Insect data through 2013 originally harvested from a sigmaplot file (Insect Data.jnb) received by email from pmeserve@uidaho.edu on 20150427.
* 2014 data harvested from two spreadsheets ("Barber data.03-14.unhide.wksht.xlsx" & "Malaise data.04-14.unhide.wksht.xlsx") received by email from pmeserve@uidaho.edu on 20151014
* Data saved as a csv file
* Data Definitions  
    - MO  (YearMo)
    - Session: (integer) Sequential numbering of months
    - NumsM (numeric) Malaise Trap: Number of individuals
    - BiomM (numeric) Malaise Trap: Biomass
    - NumsB (numeric) Barber (Pitfall) Trap: Number of individuals
    - BiomB (numeric) Barber (Pitfall) Trap: Biomass

Data Steps
-------------------------

* Load Packages



* Load Data
 


* Get coordinates for rainy year polygons (2003, 2006, 2011; May to May) by Session
    - xstart=c(1,31,91)
    - xend=c(7,43,103)
* Plot Monthly Values 



* Function to calculate means and standard errores (summarySE)


,breaks=c(10,100,1000)



* Add Month variable
* Aggregate data by month
* Plot values with standard errores



* add multiplots



