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

```ruby
#authenticate 
token <- create_token(
  app = "rstatsanalysis21",
  consumer_key = api_key,
  consumer_secret = api_secret_key,
  access_token = access_token,
  access_secret = access_token_secret)

#you should get the following notion on your browser:
#'Authentication complete. Please close this page and return to R.'

#check to see if token is loaded
get_token()
```


```ruby
#install.packages("tidytext")
#load twitter library 
library(rtweet)
library(ggplot2)
library(dplyr)
library(tidytext)
library(igraph)
library(ggraph)
```
