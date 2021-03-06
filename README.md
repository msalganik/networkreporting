networkreporting
================

network reporting methods in R

(package under development)

The development of this software was supported by a grant from the National Institutes of Health (R01-HD075666).

Installing
-----------

You can install:

* the latest released version from CRAN with

    ```R
    install.packages("networkreporting")
    ````

* the latest development version from github with

    ```R
    if (packageVersion("devtools") < 1.6) {
      install.packages("devtools")
    }
    devtools::install_github("dfeehan/networkreporting")
    ```

Vignettes
---------
* [Analyzing network scale-up data using the networkreporting package]( https://cran.rstudio.com/web/packages/networkreporting/vignettes/network_scaleup.html)

Branches
--------
* `cran` - will contain the version currently available on
  [CRAN](http://cran.r-project.org)
* `dev` - will have the most recent development release
* other branches will exist as needed


Wish list
---------
* make it easy to get uncertainty intervals for the IV checks
* for network survival, make it easy to use the two alternate estimators which
  are appropriate when additional information about population distribution is
  available (see Rwanda mortality paper)
