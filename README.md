# Study of Billionaires

An exploratory data analysis (EDA) of studying top wealth rankings about billionaires.

The source for the [billionaires.csv](https://think.cs.vt.edu/corgis/datasets/csv/billionaires/billionaires.csv) dataset stems from Forbes World's Billionaires lists from 1996-2014. There are 22 variables and 2614 observations. The [host](https://think.cs.vt.edu/corgis/csv/billionaires/) of the data is from the [CORGIS Dataset Project](https://corgis-edu.github.io/corgis/). For more detailed descriptions, please visit: <https://think.cs.vt.edu/corgis/csv/billionaires>.

In this project, our goal is to figure out what factors contribute to the rank in which certain billionaires fall. The rank is comparing the income between billionaires and we are interested in whether age, gender, company type, location, inherited through family, or the year the company was founded, played a large factor in their rank. Before we analysis, we only select year 2014. We utilized a simple linear regression modeling on the relationship between age and wealth, and a randomization testing on gender and wealth. 

We found that there is a positive linear relationship between wealth and age, and there is no significant evidence that there is a difference between the mean of wealth worth in billions for male and that for female in 2014. Even though there is no difference between two means. The proportion of female billionaires is much smaller than that of male billionaires.

### Group Members

Christie Yang  
Everett Cheng  
Yuan Zhang  
Zhuojian Wei
