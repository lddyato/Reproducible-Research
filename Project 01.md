

## Code for reading in the dataset and/or processing the data
```r
if(!file.exists('data')) dir.create('data')
fileUrl <- 'https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip'
download.file(fileUrl, destfile = './data/Factivity.zip')
unzip('./data/Factivity.zip', exdir = './data')
```


## Histogram of the total number of steps taken each day
## Mean and median number of steps taken each day
## Time series plot of the average number of steps taken
## The 5-minute interval that, on average, contains the maximum number of steps
## Code to describe and show a strategy for imputing missing data
## Histogram of the total number of steps taken each day after missing values are imputed
## Panel plot comparing the average number of steps taken per 5-minute interval across weekdays and weekends
## All of the R code needed to reproduce the results (numbers, plots, etc.) in the report
