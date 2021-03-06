---
title: "index"
author: "kaniska"
date: "February 7, 2016"
output: html_document
runtime: shiny
---
--- .class #id
## Goal of the Presentation

1. Here we demonstrate how the Population Distribution by Counties.
2. We further show how easily one can see the demographic distribution per ethnic group by selecting ethnic group and selecting the population density range. 

This R Markdown document is made interactive using Shiny. Unlike the more traditional workflow of creating static reports, you can now create documents that allow your readers to change the assumptions underlying your analysis and see the results immediately. 

To learn more, see [Interactive Documents](http://rmarkdown.rstudio.com/authoring_shiny.html).

--- .class #id
## Inputs and Outputs

You can embed Shiny inputs and outputs in your document. Outputs are automatically updated whenever inputs change.  This demonstrates how a standard R plot can be made interactive by wrapping it in the Shiny `renderPlot` function. The `selectInput` and `sliderInput` functions create the input widgets used to drive the plot.

--- .class #id
## Embedded Application

It's also possible to embed an entire Shiny application within an R Markdown document using the `shinyAppDir` function. This example embeds a Shiny application located in another directory:


```
## Error in shinyAppDir(system.file("../data-product", package = "shiny"), : No Shiny application exists at the path ""
```

Note the use of the `height` parameter to determine how much vertical space the embedded application should occupy.

You can also use the `shinyApp` function to define an application inline rather then in an external directory.

In all of R code chunks above the `echo = FALSE` attribute is used. This is to prevent the R code within the chunk from rendering in the document alongside the Shiny components.



