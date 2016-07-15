---
title: "ETC2420 <br> Introduction to R, RStudio & RMarkdown"
author: Earo Wang <br> <earo.wang@gmail.com>
date: Lab 01
---



# View this slides in your browser

<center>
<http://rawgit.com/earowang/Statistical_Thinking/gh-pages/tutorials/lab01/index.html>
</center>

## Manual control
* **Left/Right arrow**: page up/down
* **C**: toggle table of content
* **A**: display current or all slides
* **S**: make fonts smaller
* **B**: make fonts bigger

# What is markdown?

> An **easy-to-read** and **easy-to-write** plain text format.

* Check out the [markdown homepage](https://daringfireball.net/projects/markdown/)
  for its philosophy
* Examples of basic syntax
    + Emphasis
        - `**bold**` ===> **bold**
        - `*italics*` ===> *italics*
    * Lists

```
* Examples of basic syntax
    + Emphasis
        - **bold**
        - *italics*
* Lists
```

* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* This slides is written in **R** + **Markdown** = **RMarkdown**!!

# Write report in RMarkdown

1. Start RStudio
2. Create a new project (`ETC2420`)for this unit
    + File -> New Project -> Existing Directory -> Empty Project
3. Open a new RMarkdown document and save it as `MYLab1.Rmd` 
    * File -> New File -> R Markdown -> OK -> Knit HTML
4. Look through this sample Rmd file
    + Meta information starting and ending with `---`
    + Embed R code like 
<pre>```{r cars} 
summary(cars)
```</pre>
    * Write as usuall but in markdown way

<meta name="copyright" content="LICENSE: CC BY-NC 3.0 US" />