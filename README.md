# Emerging Technologies Tasks Assessment
## Task One
### Description
Write a Python function called sqrt2 that calculates and
prints to the screen the square root of 2 to 100 decimal places. Your code should
not depend on any module from the standard library1 or otherwise. You should
research the task first and include references and a description of your algorithm.
***
## Task Two
### Description
The Chi-squared test for independence is a statistical
hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. The Wikipedia article gives the table below as an example,
stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
to verify this value and calculate the associated p value. You should include a short
note with references justifying your analysis in a markdown cell.
|            | A | B | C | D | Total |
|:-----------|:-:|:-:|:-:|:-:|:-----:|
|**White collar**|90 | 60|104|95 |349    |
|**Blue collar** |30 |50 |51 |20 |151    |
|**No collar**   |30 |40 |45 |35 |150    |
|**Total**       |150|150|200|150|650    |
***
## Task Three
### Description
The standard deviation of an array of numbers x is
calculated using numpy as: 

$$ np.sqrt(np.sum((x - np.mean(x))\**2)/len(x)) $$

However, Microsoft Excel has two different versions of the standard deviation calculation,
STDDEV.P and STDDEV.S . The STDDEV.P function performs the above
calculation but in the STDDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell
about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. Note that part of
this task is to figure out the terminology in the previous sentence.
***
## Task Four
### Description
Use scikit-learn to apply k-means clustering to
Fisher’s famous Iris data set. Explain in a Markdown cell how your code works and how accurate it might
be, and then explain how your model could be used to make predictions of species
of iris.
***
