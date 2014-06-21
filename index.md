---
title       : Explore 1974 Motor Trend dataset
subtitle    : with shiny app
author      : Dmitry Kolodezev
job         : student
framework   : html5slides   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
## Explore 1974 Motor Trend dataset


If you goal 

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

---------------------
## Scatterplot
slide2


---------------------
## Regression coefficients
```
Model: lm(mpg~am+cyl+am:cyl)
```


```
##             Estimate Std. Error t value  Pr(>|t|)
## (Intercept)   30.874     3.1882   9.684 1.948e-10
## am            10.175     4.3046   2.364 2.526e-02
## cyl           -1.976     0.4485  -4.405 1.407e-04
## am:cyl        -1.305     0.7070  -1.846 7.551e-02
```

---------------------
## Box Plot
```
Model: lm(mpg~am+cyl+am:cyl)
```

![plot of chunk qqplot](assets/fig/qqplot.png) 

---------------------
## Resuduals Plot and QQ Plo
```
Model: lm(mpg~am+cyl+am:cyl)
```

![plot of chunk resplot](assets/fig/resplot.png) 

На этих страницах мы можем проверить 
