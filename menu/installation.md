---
layout: page
title: Installation instructions
---

You will need to bring a laptop for this course to work on data analytics practicals in R. Prior to the first session on Friday, March 12, please follow the instructions to install all necessary software and complete the preparatory RStudio Primer tutorial.

If you cannot bring a laptop to the course please let us know asap.

## 1 - Install Base-R and RStudio on your laptops

Use the following links to install the newest versions of Base-R und RStudio.

### Install Base-R
<a href="https://cran.r-project.org/bin/windows/base/R-4.1.2-win.exe">R 4.1.2 (Windows)</a>,
<a href="https://cran.r-project.org/bin/macosx/base/R-4.1.2.pkg">R 4.1.2 (Mac)</a><br>

### Install RStudio
<a href="https://download1.rstudio.org/desktop/windows/RStudio-2022.02.0-443.exe">RStudio 2022 (Windows)</a>,
<a href="https://download1.rstudio.org/desktop/macos/RStudio-2022.02.0-443.dmg">RStudio 2022 (Mac)</a>

## 2 - Install necessary packages

For this course we will rely on various R packages that need to be installed. To do this run the following code within your R Console within R Studio.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
install.packages("tidyerse","ggthemes","lme4")
</font>

Important: to avoid problems during the installation of packages, please enter *n*, when you are asked to install a package from source.
