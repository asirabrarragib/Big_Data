##Dataset Information:

1.	Load the Dataset: Ablone Data Set Link: https://archive.ics.uci.edu/ml/datasets/Abalone
2.	Number of Instances: 4177
3.	Number of Attributes: 8

##Implementation Steps:
1.	Import numpy, pandas, seaborn, matplotlib.pyplot
2.	Load the datset.
3.	Check the information of the data to see whether is there any data type other than numerical data.
4.	Convert the “Sex” // M=2, F=0, and I =1
4.	We took 2000 instances for this assignment -2
5.	Check the information to see if all the attributes are numerical
6.	Use .describe function to see the mean, count, std and other measurement for the attributes
7.	Now use another function to print these measurements to “outputfile-abalone.txt” file.
8.	Now we will implement visualization steps
9.	We will count the number of each attributes by ploting histogram.
10.	We will use the graph plot to see the relation between height and diameter for sex attribute.
11.	We will use the graph plot to see the relation between height and whole weight for sex attribute.
12.	We will use the graph plot to see the relation between length and height for sex attribute.
13.	We will use the graph plot to see the relation between length and height for different ring attribute.
14.	We will generate the heatmap
15.	We will generate the box plot.
16.	We will generate pairplot.
