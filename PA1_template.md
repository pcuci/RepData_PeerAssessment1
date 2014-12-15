# Reproducible Research: Peer Assessment 1



## Loading and preprocessing the data

```r
activity <- read.csv("./activity.zip")
```

```
## Warning in read.table(file = file, header = header, sep = sep, quote =
## quote, : line 1 appears to contain embedded nulls
```

```
## Warning in read.table(file = file, header = header, sep = sep, quote =
## quote, : line 2 appears to contain embedded nulls
```

```
## Warning in read.table(file = file, header = header, sep = sep, quote =
## quote, : line 4 appears to contain embedded nulls
```

```
## Warning in scan(file = file, what = what, sep = sep, quote = quote, dec =
## dec, : embedded nul(s) found in input
```

```r
str(activity)
```

```
## 'data.frame':	316 obs. of  1 variable:
##  $ PK...: Factor w/ 286 levels "","(\027",")\xac\002ɪ\020\xc2*\x84\xb0",..: 207 35 36 42 42 38 114 75 110 4 ...
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
