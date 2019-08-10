``` r
minVal <- 0
maxVal <- 100
mymean <- (maxVal - minVal)/2
x = rnorm(20, mean = mymean, sd = mymean/3)
x
```

    ##  [1] 63.21132 51.65157 48.53797 62.86547 60.30935 38.03658 50.92695
    ##  [8] 58.94756 84.63625 81.18072 70.31186 47.64566 83.26646 48.13193
    ## [15] 80.12130 43.94677 69.33005 18.92379 33.49504 50.55072

``` r
hist(x)
```

![](hello-world_files/figure-markdown_github/unnamed-chunk-2-1.png)
