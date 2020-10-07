# predict_activity

Read in Data ​

Check Casting:​

dplyr::glimpse(myData)​

Missing (NA) Values:​

For (i in 1:length(myData)){print(paste(names(myData[i]), sum(is,na(myData[i]))))) ​

What Do Zeros Mean?​

Sometimes a zero or -1 or -99 means missing data (depends on the data set)​

Data Interpolation​

Changing 0/NA/Missing values to some reasonable value like central tendency IE mean. 

Data Exploration​

Through data visualizations​

Data Transmogrification (transformation)​

Creating data from data IE text parsing​

Save data​

save(myData “myData.R”)​

myData<-load(“myData.R”)
