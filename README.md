# Machine Learning Challenge

 ## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden exoplanets outside of our solar system.

Machine learning models were created to classify candidate exoplanets from the raw dataset. I imported the dataset and then ran different machine learning models on the data.

## Results

A K Nearest Neighbors classifier was tried, but it only yielded an accuracy of 66.1%

Better success was found using SVM(Support Vector Machine). Initially, various combinations of X values were tried, but the highest accuracy achieved was 61.4%.

Next, all available X values were tried, including the error values. With a linear kernel, I obtained a testing accuracy of 88.8%. Other kernels were attempted but none of them could beat the score of the linear model.

The linear model has a high accuracy and might be able to identify new exoplanets, however it should be tuned and tested further before being used in any real world application. My model could also be further tested using other machine learning methods and testing the accuracy against the models that have already been tried on it.

## Tools/Packages Used
- Python
- Jupyter Notebook
- Sci-kit learn library
- Pandas
  
  
  Kelby(@Kelby-Wilson)

