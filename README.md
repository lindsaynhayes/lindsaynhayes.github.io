# Website for Lindsay N. Hayes

[lindsaynhayes.github.io](https://lindsaynhayes.github.io)

## Notes:

-   Website created using [this](https://www.youtube.com/watch?v=RYf5HqU1pI4) tutorial by [Dr. Maria Tackett](https://maria-tackett.netlify.app) for RLadies Baltimore.

-   Website created using distill and postcard templates.

```{r, eval = FALSE}
#install.packages("postcards", "distill")
library(distill)
create_website(dir = ".", title = "Lindsay N. Hayes", gh_pages = TRUE)
create_theme(name = "theme") 
create_article(file = "test", template = "jolla", package = "postcards")
create_article(file = "test")
```

```{r, eval=FALSE}
# to update
# open Rproj
# update content
# Build Website to preview
# with index and _site.yml open run build website.
# push to github
```