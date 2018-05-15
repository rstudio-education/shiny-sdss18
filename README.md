# Shiny Essentials

[Symposium on Data Science and Statistics 2018](https://ww2.amstat.org/meetings/sdss/2018/index.cfm)
Wed, May 16, 1:30 PM - 5:30 PM 
Grand Ballroom G

## Workshop description

Shiny is an R package that makes it easy to build interactive web apps straight 
from R. You can host standalone apps on a webpage or embed them in R Markdown 
documents or build dashboards. This short course will introduce you to the 
basics of building web applications with Shiny, essentials of reactive 
programming, and how to customize and deploy your apps for others to use. 
Please bring a laptop with you to the course.

## Pre-workshop communication

I’m looking forward to meeting everyone joining the Shiny Essentials workshop 
this week!

The workshop starts Wed, May 16 at 1:30pm in Grand Ballroom G, but you may 
want to arrive a little before 1:30pm to get set up.

### Equipment

Please bring a laptop with a web browser and a power cord.

### Setup

#### Option 1: RStudio Cloud :cloud:

I have set up an RStudio Cloud space for the workshop, with all the packages 
you will need pre-installed. The space will also include all the starter code 
you will need for the exercises.

If you choose to use this space, you should not need to install any software 
or packages (and you don’t need to worry about the rest of the instructions 
listed below).

#### Option 2: Local Installation :computer:

However if you would like to use your own setup, please make sure that you have 
R and RStudio installed.

  - R - 3.4.4 or above: https://cran.r-project.org/
  - RStudio - 1.1.446 or above: https://www.rstudio.com/products/rstudio/download/preview/

It is also recommended that you pre-install the packages we will use at the 
workshop. The package installation instructions are as follows

```
# Install

from_cran <- c("DT", "glue", "flexdashboard", "rmarkdown", "shiny", 
               "shinydashboard", "shinythemes", "tidyverse")

install.packages(from_cran, repos = "http://cran.rstudio.com")

# Load

library(DT)
library(glue)
... # load the remaining packages similarly
```

The install.packages command may install additional packages, which can take 
some time. Hence it is recommended that you install them ahead of time, 
if possible.

If you will be using your own setup, and especially if you have never used 
Shiny before, please try the following before you arrive:

In RStudio, go to File :arrow_right: Shiny Web App to to create and click on 
the Run App button. If this works without any issues, you’re ready to go!

If you have any questions, please email me at mine@rstudio.com. 
See you soon at SDSS!
