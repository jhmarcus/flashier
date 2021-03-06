# flashier

This package is in active development. The interface is likely to change from time to time.

Please note that `flashier` currently uses a development branch of package `ebnm`. To get the default `point.normal` priors (and some other prior types) working, you will need to run:

```devtools::install_github("stephenslab/ebnm", ref = "regular-normal")```

To get more flexible priors such as `normal.mixture` and `nonnegative` working, you will need to install `ashr`. Please install the latest version of `ashr` from GitHub (version 2.2-29 or higher is required):

```devtools::install_github("stephens999/ashr")```

Before diving in, I recommend taking a look at the vignettes. Do note, however, that they take a few minutes to build (it took me a little less than 5 minutes on a 2015 13" MacBook Pro). If you choose to build them, make sure you've installed the above packages first. Then run:

```devtools::install_github("willwerscheid/flashier", build_vignettes = TRUE)```

There are two vignettes:

```vignette("intro", package = "flashier")```

```vignette("advanced", package = "flashier")```
