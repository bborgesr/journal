---
title: Hello Blog
author: 'Barbara'
date: '2017-12-08'
slug: hello-blog
categories: [reference]
tags: [hugo, blogdown]
---

## The holy grails of information
- <https://bookdown.org/yihui/blogdown>
- <https://gohugo.io/getting-started/configuration/#configure-blackfriday>

Courtesy of <https://gohugo.io/content-management/shortcodes/>:
{{< youtube w7Ft2ymGmfc >}}

## Options that need to be set:

```r
options(servr.daemon = TRUE, blogdown.author = "Barbara")
```

## Some info right off the bat (for free!!)
This is a post written in plain Markdown (`*.md`) instead of R Markdown (`*.Rmd`). The major differences are:

1. You cannot run any R code in a plain Markdown document, whereas in an R Markdown document, you can embed R code chunks (```` ```{r} ````);
2. A plain Markdown post is rendered through [Blackfriday](https://gohugo.io/overview/configuration/), and an R Markdown document is compiled by [**rmarkdown**](http://rmarkdown.rstudio.com) and [Pandoc](http://pandoc.org).

There are many differences in syntax between Blackfriday's Markdown and Pandoc's Markdown. For example, you can write a task list with Blackfriday but not with Pandoc:

- [x] Write an R package.
- [ ] Write a book.
- [ ] ...
- [ ] Profit!
