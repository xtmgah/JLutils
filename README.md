JLutils
=======

[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/0.1.0/active.svg)](http://www.repostatus.org/#active) 
[![Travis-CI Build Status](https://travis-ci.org/larmarange/JLutils.svg?branch=master)](https://travis-ci.org/larmarange/JLutils)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/JLutils)](https://cran.r-project.org/package=JLutils)


**Online documentation:** <http://larmarange.github.io/JLutils/>

A collection of diverse R functions who don't fit (yet?) in another package. Please note that some functions could be removed from `JLutils` once incorporated in a more appropriate package.

Une collection de fonctions diverses R qui n'ont pas (encore ?) trouvé de place dans un autre package. Veuillez noter que certaines fonctions peuvent être retirées de `JLutils` une fois incorporées dans un package plus approprié.

How to install / Installation 
--------------

Execute the following code within `R`:

Exécutez le code suivant dans `R` :

```r
if (!require(devtools)){
	install.packages('devtools')
	library(devtools)
}
install_github("larmarange/JLutils")
```

### Alternative

```r
source("https://install-github.me/larmarange/JLutils")
```
