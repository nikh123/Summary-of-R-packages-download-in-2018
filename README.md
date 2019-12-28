# Introduction
Here is the coding to obtain R package download summaries of 2018 into csv

# Required 
- R
- R studio
- jsonlite 
- Curl

# Code description

```
# Summary-of-R-packages-download-in-2018

#Install jsonlite

library(jsonlite)

#Gather data on R packages installed in 2018

Data=jsonlite::fromJSON("https://cranlogs.r-pkg.org/downloads/total/2018-01-01:2018-12-31")

#Convert the result in csv file

write.csv(Data,"/Users/nikhil/Desktop/codein/Data.csv")
```
# Screen recording
![](http://g.recordit.co/VeL5biu2of.gif)

# Author
- Nikhil
