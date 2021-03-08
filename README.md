---
output:
  pdf_document: default
  html_document: default
---
# Lecture2

git config --global user.email "dnjsehdzl12@daum.net"
  git config --global user.name "kangwondong"


# Installing Packages


```{r}
install.packages("tidyverse")
library(tidyverse)
install.packages("AmesHousing")
library(AmesHousing)
library(ggplot2)

```


# Data loading


```{r}
d<-AmesHousing::ames_raw
```

# Explore data

```{r}
glimpse(d)
summary(d)
```





























