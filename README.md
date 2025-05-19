# ACM Data AI Stats Workplan

## Week 3 Goal: Cleaning the dataset

* Extract your target variables  
* Isolate the years  
* Rename any columns  
* Resolving null values  
* Normalization

## Week 3 Instructions:

* take a look at the data cleaning file i shared in resources and play around with the functions in there (try normalizing some of the variables)  
* try visualizations for some of the variables to check for outliers and distributions  
* look into iterators and what things to consider when choosing one

## Week 4 Goal: Prediction Modeling \- cleaning part 2  
Creating:

- Initial line plots  
- visualizations  
- Set ur iterator  
  - D, W, M

## Week 4 Instructions:

1. Set the datetime column as the index ( something like: df.set\_index("date", inplace=True))

note: Make sure the index is in datetime64 format

2. Plot the original time series (line plot)

note: come up with 1-2 sentences to describe the data and interpret the line plot

3. Resample the time series to  
1. Daily ('D')  
2. Weekly ('W')  
3. Monthly ('M')

note: For each, use .resample().mean() or .sum() depending on context

4. Plot each version (D, W, M) using line plots

note: Describe how the resampling affects the appearance and interpretation of the data