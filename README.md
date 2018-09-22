## Project Description 
This is the famous titanic challenge to determinre the survivors of titanic passengers

## packages used 
- pandas 
- matplotlib
- sklearn

## used data set 
[titanic data set](https://www.kaggle.com/hesh97/titanicdataset-traincsv)

## Algorithms used
- Random selection (mke women only survivors, as most of the sruvivors were women)  &rightarrow; accuracy : 0.786756
- Logistic Regression &rightarrow; accuracy : 0.8013
- Logistic Regression of higher degree
    - second degree : &rightarrow; accuracy : 0.8215
    - third degree : &rightarrow; accuracy : 0.7946
- Decission Tree 
    - with no specifications &rightarrow; accuracy : 1.0  (overfitting)
    - with max_depth = 8, min_samples_split = 10  &rightarrow; accuracy : 0.81