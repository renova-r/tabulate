# tabulate

Pretty console output for tables, with control over cell colors, font types, borders and nested tables, built on bundled C++ headers.

Compatibility updates by Renova.

Version 0.1.0.9001 makes one metadata change: the `SystemRequirements: C++11` field was removed from `DESCRIPTION`. No R, C++ or documentation file was changed.

## Install

From R-universe:

```r
install.packages("tabulate", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/tabulate@renova-0.1.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

tabulate was written by Daniel Falbel (maintainer). It includes code by Pranav Srinivas Kumar (Tabulate, MIT), Martin Moene (variant-lite and string-view-lite, Boost Software License 1.0) and Ihor Kalnytskyi (Termcolor, BSD); their notices are kept in `src/tabulate.h`. License: MIT + file LICENSE (see [LICENSE](LICENSE) and [LICENSE.md](LICENSE.md)).
