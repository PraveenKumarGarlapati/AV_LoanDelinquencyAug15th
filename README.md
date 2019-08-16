# AV_Loan Default Prediction
This is a Loan Delinquency Problem in Analytics Vidya, which started on Aug 15th

## Data Prep
* Data provided is quite clean.
* No missing values as such and all we need is some understanding of each of the columns


## Features

* In regards with new features, I've created few additional columns that shall help us aid in better predictions.
Here's the list of columns I created

* 1st Month of default (First Non-zero value in the columns m1 to m12)
* Total default months (Total Non-zeros)
* Total of the values in the columns m1 to m12 (Still trying to figure out what exactly these numbers represent)
* There were many cases where co-borrower credit score is given as 0. I've created a new column with the difference of Borrower
and Co-borrower Credit Score
