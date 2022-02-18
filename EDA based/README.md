# Exploratory Data Analysis 

### What is EDA ? 
**Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.**


## While Performing EDA ask following things...
### 1. Data Structure & Distributions
**Questions to Answer:**
- How many features do you have?
- How many observations do you have?
- What is the data type of each feature?
- From what you know about the features of your dataset, do the data types make sense? Do you need to change any?
- Do you have null values? 
- How much memory does this dataset use? Could this pose a problem for you later on?
- What is the distribution of each variable?
- Do there appear to be outliers? 
- Think about what the variables mean and what the histograms say about their values and their spread — are there any surprises?
- Are the max/min values reasonable for the variables? Do you see any values that look like errors?
- What is the mean for each variable? What do the means tell you about your dataset as a whole?

### 2. Null Values & Duplicates
**Questions to Answer:**
- Check the duplicated sum.
- Is the null value a result of the way data was recorded? (Was it kept Null Intentionally - we can decide this by carefully understanding the data)
- Can you drop the rows with null values without it significantly affecting your analysis?
- Looking at the distributions of the variables, can you justify filling in the missing values with the mean or median for that variable? (We use mean for Numerical Data with no Outliers, Median for Numerical Data with Outliers and we use Mode for Categorical data)
- If your data is time-series data, can you fill the missing values with interpolation?
- Are there so many missing values for a variable that you should drop that variable from your dataset?

### 3. Outliers
**Questions to Ask:**
- Do you have outliers (represented as dark circles on the boxplots) in your variables?
- Why do you think you have outliers?
- Do the outliers represent real observations (i.e. not errors)?
- Should you exclude these observations? If not, should you winsorize the values? 

### 4. Correlations/Relationships
**Questions to ask:**
- Which variables are most correlated with your target variable? (If applicable)
- Is there multicollinearity? (Two features that have a correlation > 0.8) How will this affect your model?
- Do you have variables that represent the same information? Can one be dropped?

### 5. Feature Engineering
- **Variable Transformation:** One-Hot-Encoding, Standardization, np.log(), np.sqrt(), box-cox-transformation, etc.
- **Creating New Features:**
      1. You suspect that the relationship of an outcome and a feature depends on a second feature → Create an interaction variabl
      2. You want to create linear relationships → Create quadratic or higher level functions
      3. You can think of variables/information that is missing from your dataset → Create this variable using a function of variables you do have
      
      

[Reference](https://levelup.gitconnected.com/cozy-up-with-your-data-6aedfb651172)
