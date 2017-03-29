Two Paired Means CLE
================

``` r
zinc =  read.table("https://onlinecourses.science.psu.edu/stat500/sites/onlinecourses.science.psu.edu.stat500/files/data/zinc_conc.txt", 
                   header=T, fileEncoding="UTF-16LE")
zinc$difference = zinc$bottom - zinc$surface
summary(zinc)
```

    ##      bottom          surface         difference    
    ##  Min.   :0.2660   Min.   :0.2380   Min.   :0.0150  
    ##  1st Qu.:0.4845   1st Qu.:0.4103   1st Qu.:0.0355  
    ##  Median :0.5780   Median :0.4690   Median :0.0840  
    ##  Mean   :0.5649   Mean   :0.4845   Mean   :0.0804  
    ##  3rd Qu.:0.6930   3rd Qu.:0.6080   3rd Qu.:0.1100  
    ##  Max.   :0.7230   Max.   :0.6320   Max.   :0.1770
