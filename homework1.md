Homework \#1 – Pet Names Dataset
================
Amsha Fisal

**Student ID:2201000180**

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises

\#Answer Exercise1 \`1. 52519

(4 points)

\#Answer Exercise2

\`2. 7 variables

(4 points)

\#Answer Exercise3 1-Dog 2-Cat 3-Goat

\`3.seattlepets%&gt;%count(animal\_name, sort = TRUE)
seattlepets%&gt;%count(species, sort = TRUE)

(4 points)

\#Answe Exe4 Top 5 names for Dog Lucy  
Charlie  
Bella  
Luna  
Daisy Top 5 names for Cats NA Luna Lucy Lily Max (10 points)

\#ANSWER Exe5 \`5. What names are more common for cats than dogs? The
ones above the line or the ones below the line?

lily milo charli bella luna lala stella max molly maggie jack henry
pepper

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data?

positive, whenever increased name for dogs. increased name cat

(4 points)
