---
title: "My report"
author: "TingTing"
date: "May 29, 2019"
output: 
  html_document:
      keep_md: true
---

*This is some formatting*

**Some other formats**

- item 1
- item 2


1. list 1
1. list 2




```r
library(gapminder)
library(ggplot2)
library(tidyverse)

data(gapminder)
head(gapminder)
```

![](rr-demo_files/figure-html/gdp_lifeexp_plot-1.png)<!-- -->


```r
ggplot(data=gapminder, mapping = aes(x=year, y = lifeExp))+
    geom_point()
```

![](rr-demo_files/figure-html/lifeexp_over_time-1.png)<!-- -->



The largest populaitono f any country in this dataset is 81.757.


**Some other formats**
