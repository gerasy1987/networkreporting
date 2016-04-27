[![Travis-CI Build
Status](https://travis-ci.org/dfeehan/networkreporting.svg?branch=master)](https://travis-ci.org/dfeehan/networkreporting)


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

The `networkreporting` package enables you to use several methods that many people currently think of as distinct.  Here are some vignettes for how to use the package:

* [Analyzing network scale-up data using the networkreporting package]( https://cran.rstudio.com/web/packages/networkreporting/vignettes/network_scaleup.html)
* Analyzing sibling method data using the networkreporting package] (Coming soon)

Branches
--------
* `cran` - will contain the version currently available on
  [CRAN](http://cran.r-project.org)
* `dev` - will have the most recent development release
* other branches will exist as needed


Wish list
---------
* if you would like to suggest a feature, please create an
  [issue](https://github.com/dfeehan/networkreporting/issues)
