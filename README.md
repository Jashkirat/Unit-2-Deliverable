# Unit-2-Deliverable Stats and Public Health

### Statistics & Public Health 1: Cleaning and EDA

West Nile Virus (WNV) is a viral illness largely spread by mosquitoes. The disease is transmitted to a person when an infected mosquito bites them.

The city of Chicago, Illinois has been keeping track of mosquito populations and WNV prevalence using a series of traps that they place around the city. They are then able to study the captured specimens and monitor the state of WNV spread in the city.

You are given mosquito tracking data from 2008 to 2019.

In this deliverable, you will perform basic EDA and data wrangling to get familiar with the dataset from the city of Chicago.

#### Part 1 - Basic Data Wrangling

What is the shape of the dataframe?

Convert the 'Date' column to have a datetime format.

Pick two numeric and two categorical columns: What data they are storing? How are they distributed?

Are there any columns that contain duplicate information? If so, remove the redundant columns.

Are there any null values in the dataframe? If so, deal with them appropriately.

#### Part 2 - Basic EDA

Using an appropriate visual, or visuals, explore the relationship between mosquito number and date.

#### Part 3 - Advanced EDA

Using an appropriate visual, explore the relationship between mosquito species and WNV prevalence.

Using an appropriate visual, explore the relationship between the number of mosquitos caught and trap type.
Note: This visual should be a different type of visualization than the previous one

Using an appropriate visual, come up with an additional insight of your choice.

Note: This visual should be a different type of visualization than the previous two

### Statistics & Public Health 2: Data Analysis

Now that you are familiar with the data, we will move on to a set of analyses on the relationship between the different variables and the mosquito number, as well as the probability of finding West Nile Virus (WNV) at any particular time and location.

For this deliverable, you must use the provided cleaned dataset which differs from that for Part 1. Download the data here.

### Part 1 - Basic Analysis
Convert the WNV Present column into a binary column and create dummy variables from the Trap type column.

What is the average number of mosquitoes for each month? What trends do you notice?

### Part 2 - Statistical Analysis
Is there a statistically significant difference between the different mosquito species when looking at the occurrence of West Nile Virus?

Which columns are positively correlated with the number of mosquitoes caught? Which columns are negatively correlated? Are these correlations statistically significant?

### Part 3 - Advanced Statistical Analysis
Run a linear regression to determine how the independent variables affect the number of mosquitoes caught. Explain your model construction process. Analyze the model and the results and discuss the model’s limitations. This may end up being an iterative process.
Note:

You will likely see a low R^2 value, that is to be expected.
This dataset does not respond well to performing VIF analysis, so this is not required.

WNV Present must not be one of your independent variables.
Run a logistic regression to determine how the independent variables affect West Nile Virus presence. Explain your model construction process. Analyze the model and the results and discuss the model’s limitations. This may end up being an iterative process.
Note: Mosquito number should be one of your independent variables.