# Dlithe_assignment
## Assignments uploaded on github
## Author: Disha S K

## Practice lab 2_3 Sept 2021
In this particular assignment, a random range of numbers is created using range() function. A list of the numbers in the range can also be viewed as in list(range(0,20)) which displays values from 0 to 19 in the form of list.
Range of even numbers, odd numbers can be created by giving the step value along with the initial and final value of the range. Minnimum and maximum values in a list can also be displayed using min() or max() functions.
The difference between pop() and remove() is also analysed where pop() would remove an element using its index value whereas remove() would remove the element mentioned along parenthesis directly.


## Practice lab 6 Sept 2021
In this assignment, defining a function and calling the function is learnt.
A function "Method" is defined which would display the results of the following functions: .split(), .update(), .format(), continue
Making use of enumerate() function on a string and creating dictionary using enumerate() is also practiced.
List and dictionary comprehension related coding is also practiced using certain examples having one line of code.


## Practice lab 11 Sept 2021
In this assignment,importing new libraries into phyton for various AI ML related applications is learnt and practiced.
linspace() command imported from numpy is used to create an array. The numpy library is imported as : import numpy as np
np.eye(7) creates an 7*7 matrix with diagonal elements as 1. Also required diagonals elements can also be specified as a list and then matrix can be formed using np.diag()
Creating array using rand,randn is also practiced by importing : from numpy.random import rand, from numpy.random import randn
Fetching elements from an array is also coded and practiced.
arr = np.arange(40)
arr.reshape((8, 5))
the above lines of code creates an 8*5 matrix with range of numbers from 0 to 39.


## Practice lab 16 Sept 2021
For this particular assignment, iris_csv.csv file was downloaded from the source. In the assignemt, reading an csv file was learnt for which library pandas had to be imported at the start.
data.head() is used inorder to retrun first n rows of the data.
data.sample(10) gives an sample of  any 10 data rows.
data.columns() gives the names of all the columns present in the data.
data.shape() gives the size of the data in terms of rows and columns.
Slicing of the data was also practiced for the example.If you need the information of only some particular columns, you need to specify them in a list:
specific_data=data[["class","sepallength"]]
data.iloc(5) is used which will give access to select the fifth row of the entire data.
data.loc[data["class"] == "Iris-setosa"]  which gives an easy access to select data from column class having value "Iris-setosa."
sum, mean, median, min(), max() of the columns was also coded to get the results of the entire data.
data.rename(columns=newcols,inplace=True) is used in the code to rename certain name of the columns.
data.head(10).style.highlight_max(color='lightgreen', axis=0): codes of this type has been practiced to highlight certain rows of the specified column.
data.isnull() detects missing values in the given series of the data.
data.isnull().sum() returns number of missing elements in the data set.

Seaborn is an open-source Python library built on top of matplotlib. It is used for data visualization and exploratory data analysis.
import seaborn as sns is used to import the library to use its functions.
The various plots like heatmap,pairplot etc are used in the code within the arguements and the same data is then pictorially visualized.
Pictorial representation of data gives a clear picture of the information and can be analyzed well.
