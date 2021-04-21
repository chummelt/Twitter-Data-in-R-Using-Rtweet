# Twitter-Data-in-R-Using-Rtweet

This is a tutorial for scrapting Twitter data with R. This tutorial is divided into two parts:
1. Connection to Twitter
2. Using Twitter data for descriptive analysis

### 1. Connecting to Twitter



```ruby
rm(list=ls())
#check https://cran.r-project.org/web/packages/rtweet/vignettes/auth.html for a more detailed description

#install.packages("rtweet")
library(rtweet)
```
```ruby
#store api keys (replace with your own keys)
api_key <- "(replace with your own keys)"
api_secret_key <- "(replace with your own keys)"
access_token <- "(replace with your own keys)"
access_token_secret <- "(replace with your own keys)"
```


