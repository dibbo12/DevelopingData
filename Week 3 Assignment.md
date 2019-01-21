---
title: "Developing Data Products"
author: "Dibyajyoti Basak, 20th January 2019"
date: "20th January 2019"
output: ioslides_presentation
hitheme: tomorrow
knit: slidify::knit2slides
mode: selfcontained
highlighter: highlight.js
subtitle: Week 3 Assignment
framework: io2012
widgets: []
---

#Code to plot, using plotly package, and using the mtcars dataset

suppressPackageStartupMessages(library(plotly)) mtcars

#read.csv("C:/Users/dibbo/Downloads/mtcars/mtcars.csv") try(plot_ly(data = mtcars, x = ~wt, y = ~mpg, color = ~as.factor(cyl), size = ~hp, text = ~paste("Weight: ", wt, 'MPG:', mpg), type = "scatter", mode = "markers") %>% #layout(title = "Car Data"))
---


```
## Error in file(con, "rb"): cannot open the connection
```

---
##If plot doesn't show please click on the following link
[Plot link](http://rpubs.com/dibbo12/459806)












