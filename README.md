# Website for Lindsay N. Hayes
[lindsaynhayes.github.io](https://lindsaynhayes.github.io)

## Notes: 
Webiste was created using [this](https://www.youtube.com/watch?v=RYf5HqU1pI4) tutorial by [Dr. Maria Tackett](https://maria-tackett.netlify.app) for RLadies Baltimore.

```{r}
#install.packages("postcards", "distill")
library(distill)
create_website(dir = ".", title = "Lindsay N. Hayes", gh_pages = TRUE)
create_theme(name = "theme") 
create_article(file = "home", template = "jolla", package = "postcards")
create_article(file = "article")
```