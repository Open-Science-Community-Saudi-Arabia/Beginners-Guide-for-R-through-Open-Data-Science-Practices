---
title: Setup
---

## For all operating systems

> ## Install a good text editor
> Before you start, it is handy to dispose of a jack-of-all-trades text editor.  
> [Sublime Text](https://www.sublimetext.com/) is a flexible platform agnostic text editor for code and markdown syntax. For instance, it can open R scripts and markdown `.md` text files and color-code their languages accordingly. 
> 1. Go to the Sublime Text [download page](https://www.sublimetext.com/3).
> 2. Select your OS (Linux, Mac or Windows) and install it.
{: .prereq}

What needs to be installed are the R and RStudio softwares as well as related R packages. You will also have to install the version control `git` software. There are _two different options_ for you to consider. Option 1 is favored.  

## Option 1: using RStudio Cloud

The preferred option to install all softwares and packages is to use RStudio Cloud. See [this nice introduction to RStudio Cloud](https://www.youtube.com/watch?v=SFpzr21Pavg)   


> ## Before you start
>
> Before the training, please make sure you have done the following: 
>
> 1. Download and install **up-to-date versions** of:
>    - R: [https://cloud.r-project.org](https://cloud.r-project.org)
>    - RStudio: [http://www.rstudio.com/download](http://www.rstudio.com/download) 
>    - Git: [https://git-scm.com/downloads](https://git-scm.com/downloads) 
>
> 2. Within R/RStudio, install these packages:
>    - `tidyverse`
>    - `skimr`
>    - `plotly`
>    - `nycflights13`
>
> To do so, open R and use the `install.packages()` function. 
>
> ~~~
> install.packages("tidyverse")
> install.packages("skimr")
> install.packages("plotly")
> install.packages("nycflights13")
> ~~~
> {: .language-r}
{: .prereq}


{% include links.md %}
