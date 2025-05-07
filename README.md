# packageVignette

This is an example on how to distribute vignette via an R package.

### Setup

```{r}
library(devtools)
devtools::create("path/to/your/package")
```

```{r}
devtools::document()

devtools::build()
devtools::install()
```

