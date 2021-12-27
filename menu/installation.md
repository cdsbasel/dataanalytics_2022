---
layout: page
title: Installation instructions
---

You will need to bring a laptop for this course to work on data analytics practicals in R. Prior to the first session on Friday, March 12, please follow the instructions to install all necessary software and complete the preparatory RStudio Primer tutorial.

If you cannot bring a laptop to the course please let us know asap.

## 1 - Install Base-R and RStudio on your laptops

Use the following links to install the newest versions of Base-R und RStudio.

### Install Base-R
<a href="https://cloud.r-project.org/bin/windows/base/R-4.0.4-win.exe">R 4.0.4 (Windows)</a>,
<a href="https://cloud.r-project.org/bin/macosx/R-4.0.4.pkg">R 4.0.4 (Mac)</a><br>

### Install RStudio
<a href="https://download1.rstudio.org/desktop/windows/RStudio-1.4.1103.exe">RStudio 1.4 (Windows)</a>,
<a href="https://download1.rstudio.org/desktop/macos/RStudio-1.4.1103.dmg">RStudio 1.4 (Mac)</a>

## 2 - Install necessary packages

For this course we will rely on various R packages that need to be installed. To do this run the following code within your R Console within R Studio.

<font style="font-family: 'Lucida Console', Monaco, monospace;">
install.packages("tidyerse","caret","rpart","randomForest","e1071",
                 "party","partykit","glmnet","speff2trial","ISLR",
                 "mlbench","fastcluster","cstab","dbscan","psych",
                 "mclust")
</font>

Important: to avoid problems during the installation of packages, please enter *n*, when you are asked to install a package from source.

If you do not know how to run this code in R please let us know asap.

## 3 - Complete RStudio Primer

Go to <a href="https://rstudio.cloud/learn/primers/1.2"><b>this page</b></a> and complete the interactive course on R programming basics.

Feel free to explore other RStudio Primer's at <a href="https://rstudio.cloud/learn/primers">RStudio Primers</a>.
