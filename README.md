
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- badges: start -->

# group8

[![R-CMD-check](https://github.com/DSCI-310/DSCI-310-Group-8-Package/workflows/R-CMD-check/badge.svg)](https://github.com/DSCI-310/DSCI-310-Group-8-Package/actions)

[![codecov](https://codecov.io/gh/DSCI-310/DSCI-310-Group-8-Package/branch/main/graph/badge.svg?token=QRIHLUGBLT)](https://codecov.io/gh/DSCI-310/DSCI-310-Group-8-Package)

<!-- badges: end -->

# Predicting Student Performance using Study Time - Package

## Group 8

## Group Members

Contributors:

Isabela Lucas Bruxellas (33569286) Tony Liang (39356993) Xue Wang
(50938547) Anam Hira (67844266)

## Project Summary

In this project, we will explore and predict students’ exam performance
about Electrical DC Machines based on their study time by using linear
regression (LN) and the K-nearest neighbors (K-NN) algorithm. This
result could help students gain insight into the necessary study time
for specific scores as well as help instructors better understand the
performance of students.

The repository with the analysis can be found
[here](https://github.com/DSCI-310/DSCI-310-Group-8)

This package contains the functions necessary for the analysis.

## Report

The analysis report can be found
[here](https://github.com/DSCI-310/DSCI-310-Group-8/blob/main/doc/student_performance_analysis_report.Rmd#).

## Installation

You can install the development version of group8 from
[GitHub](https://github.com/DSCI-310/DSCI-310-Group-8-package) with:

``` r
# install.packages("devtools")
devtools::install_github("DSCI-310/DSCI-310-Group-8-package")
```

## Usage

The DSCI-310-Group-8-package has four functions here,

-   num_na : a function that shows whether there is N/A value in the
    data frame and return to a number which shows how many N/A values in
    the input.

-   summary_fun : a function shows a summary statistic for each column
    in the original input.

-   visualize_vars : a function that test whether ggplot point graph of
    two variables from same date frame.

-   wrangle_data : a function that test whether contains the necessary
    variables and if it is then returns to a tidy data frame.

By running the code block above on your R file.

The usage for function references can be found
[here](https://dsci-310.github.io/DSCI-310-Group-8-package/reference/index.html)
.

Attention:

``` r
# install.packages("devtools")
```

Needs to used if devtools is not already installed in your local
repository. Otherwise, it can be skipped

## Dependencies

R version 4.1.1, Jupyter and R packages listed in
[environment.yml](https://github.com/DSCI-310/DSCI-310-Group-8/blob/main/environment.yml).

## Licenses

[DSCI-310-Group-8-package](https://github.com/DSCI-310/DSCI-310-Group-8-package)
was created by Isabela Lucas Bruxellas, Tony Liang, Xue Wang, Anam Hira.

This package is licensed under the MIT License and [Creative Commons
Attribution-NonCommerical-NoDerivatives 4.0 International
License](https://creativecommons.org/licenses/by-nc-nd/4.0/)
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:1" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />

Attention: In order to properly run this project, ensure that you are
using the same versions when running the project in the Dockerfile.
