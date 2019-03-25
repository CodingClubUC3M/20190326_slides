---
title: Hello Jekyll!
author: Bernardo D'Auria
date: '2019-03-05'
slug: hello-jekyll
categories:
  - graphs
tags: []

layout: posts
---

This is my first plot that cointains an R graph

```{r}
library(ggplot2)
ggplot(iris,aes(x=Sepal.Width,y=Sepal.Length)) + geom_point()
```

and an external picture

![colored cats](https://goo.gl/TRS6bL)