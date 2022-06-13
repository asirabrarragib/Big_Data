# COSC 5340 Data Science and Big Data Analysis

**Dataset**: https://www.kaggle.com/datasets/azminetoushikwasi/ucl-202122-uefa-champions-league

**Implementation**
1. Import the dataset
2. Check data description
3. Remove ‘player_name’, ‘club’, ‘minutes_played’
4. Check Missing value
5. Transform the ‘position’ from object type to int type
6. Check missing value
7. Remove null values
8. Calculate similarities for nominal, ordinal and interval attributes.
9. Combining the matrix
10. Generate a csv file Similarity Matrix.csv

**Similarity for the attribute (NOMINAL ATTRIBUTE)**

Using s = 1 if p=q; s=0 if p!=q

**Similarity for the attribute  (RATIO ATTRIBUTE)**

Using d = |p-q|; s = 1/(1+d)

**Similarity for the attribute '' (ORDINAL ATTRIBUTE)**

Using d = |p-q| / (n-1); s = 1 - d

**Check for any number of missing value**
data.isnull().sum()
