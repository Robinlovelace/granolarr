



# RMarkdown



## Recap

**Prev**: Reproduciblity

- Reproduciblity and software engineering
- Reproduciblity in GIScience
- Guidelines

**Now**: RMarkdown

- Markdown
- RMarkdown



## Markdown

**Markdown** is a simple markup language

- allows to mark-up plain text 
- to specify more complex features (such as *italics text*)
- using a very simple [syntax](https://daringfireball.net/projects/markdown/syntax)

Markdown can be used in conjunction with numerous tools

- to produce HTML pages
- or even more complex formats (such as PDF)

These slides are written in Markdown



## Markdown example code

```
### This is a third level heading

Text can be specified as *italic* or **bold**

- and list can be created
    - very simply

1. also numbered lists
    1. [add a link like this](http://le.ac.uk)

|Tables |Can         |Be       |
|-------|------------|---------|
|a bit  |complicated |at first |
|but    |it gets     |easier   |
```



## Markdown example output

### This is a third level heading

Text can be specified as *italic* or **bold**

- and list can be created
    - very simply

1. also numbered lists
    1. [add a link like this](http://le.ac.uk)

|Tables |Can         |Be       |
|-------|------------|---------|
|a bit  |complicated |at first |
|but    |it gets     |easier   |



## RMarkdown example code

````
Let's write an example of **R** code including 

- a variable `a_variable`
- an assignment operation (i.e., `<-`)
- a mathematical operation (i.e., `+`)

```{r, echo=TRUE}
a_variable <- 0
a_variable <- a_variable + 1
a_variable <- a_variable + 1
a_variable <- a_variable + 1
a_variable
```
````


## Writing RMarkdown docs

**RMarkdown** documents contain both Markdown and R code. These files can be created in RStudio, and compiled to create an html page (like this document), a pdf, or a Microsoft Word document.

<center>
![](images/Lecture1_RMarkdown001.png){width=80% style="border: 1px solid black"}
</center>


## Summary

RMarkdown

- Markdown
- RMarkdown

**Next**: Git

- Git operations
- Git and RStudio


