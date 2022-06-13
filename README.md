# COSC 5340 Data Science and Big Data Analysis

**Dataset**: https://archive.ics.uci.edu/ml/datasets/Abalone

**Implementation**
1. Import the dataset
2. Check data description
3. Check Missing value
4. Check Unique values
5. Transform the ‘Sex’ from object type to int type.
6. Check missing value
7. Calculate similarities for nominal, interval attributes.
8. Combining the matrix
9. Generate a csv file Similarity Matrix-abalone.csv

**Similarity for the attribute (NOMINAL ATTRIBUTE)**

Using s = 1 if p=q; s=0 if p!=q

**Similarity for the attribute  (RATIO ATTRIBUTE)**

Using d = |p-q|; s = 1/(1+d)

**Check for any number of missing value**
data.isnull().sum()
