Homework \#1 – Pet Names Dataset
================
hadeel a
2021-02-15

**Student ID:2201004073**

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises

\`1.

(4 points)

Write your narrative here

> 52.519

\`2.

(4 points)

Write your narrative below &gt;variables:7

\`3. Copy the code provided in the homework documentation and paste it
here. &gt;seattlepets %&gt;% count(animal\_name, sort = TRUE)

> seattlepets %&gt;% group\_by(species) %&gt;% count(animal\_name, sort
> = TRUE)

> seattlepets %&gt;% count(species, sort = TRUE)

(4 points)

Write your narrative here \# A tibble: 13,930 x 2 animal\_name n <chr>
<int> 1 NA 483 2 Lucy 439 3 Charlie 387 4 Luna 355 5 Bella 331 6 Max 270
7 Daisy 261 8 Molly 240 9 Jack 232 10 Lily 232

# A tibble: 16,823 x 3

# Groups: species \[4\]

species animal\_name n <chr> <chr> <int> 1 Cat NA 406 2 Dog Lucy 337 3
Dog Charlie 306 4 Dog Bella 249 5 Dog Luna 244 6 Dog Daisy 221 7 Dog
Cooper 189 8 Dog Lola 187 9 Dog Max 186 10 Dog Molly 186

# A tibble: 4 x 2

species n <chr> <int> 1 Dog 35181 2 Cat 17294 3 Goat 38 4 Pig 6 \# …
with 16,813 more rows \# … with 13,920 more rows

\`4.

(10 points)

\`5. What names are more common for cats than dogs? The ones above the
line or the ones below the line?

Answer here

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data?

Answer here

(4 points)
