---
title       : Slidify Presentation
subtitle    : Lego Set Database Explorer
author      : Adrian Hay
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

<style>
.reveal h1 {
    font-size: 2em;
    color: #fff7e6;
    text-align: left;
    padding-bottom: 10px;
    font-family: Impact, sans-serif;
}

.reveal h2 {
    font-size: 1.5em;
    color: #fff7e6;
    text-align: left;
    padding-bottom: 10px;
    font-family: Impact, sans-serif;
}

.reveal p {
    font-size: 0.75em;
    color: #fff7e6;
    text-align: left;
    padding-bottom: 10px;
    font-family: Verdana, sans-serif;
}


</style>


# Developing Data Products
## Course Project
-------------------------------------


LEGO Sets Visualization




Adrian Hay

---

## Introduction

This presentation is part of the Course Project for the Coursera Developing Data Products class. The peer assessed assignment has two parts. First, we need to create a Shiny application and deploy it on Rstudio's servers. Second, we should use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about the application. This presentation adresses the second part of the course project.

The app developed for the first part of the assignment is avalilable at:

https://pistacio.shinyapps.io/dataproducts/

Source code for ui.R and server.R files are available on the GitHub:

https://github.com/Pistacio/DataProducts_Project.git


---

## Visualizating LEGO sets information

This App is for searching and visulizating LEGO Sets information.    
The dataset is from [Rebrickable.com](http://rebrickable.com/) that contains the basic information of each set (set id, year, number of pieces, theme, set name).  
Data Source: http://rebrickable.com/downloads  

**Note**: Since I didn't use the API to collect data, the current data might not be 100% accurate. 


---


## LEGO sets dataset

The dataset is from [Rebrickable.com](http://rebrickable.com/) that contains the basic information of each set (set id, year, number of pieces, theme, set name).  
Data Source: http://rebrickable.com/downloads 

![width](pic11.png) 

--- 

## Visualization 


![width](pic22.png) 
