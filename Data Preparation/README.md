
# Data Preparation

### What is Exploratory Data Analysis (EDA)?
While classical statistics focused primarily on inference, i.e. the process of drawing conclusions about large datasets on the basis of small samples, exploratory data analysis or data analysis was a field (of which inference is a part) that began and gained momentum on the basis of work done by John W. Tukey. In 1962, he published a paper [The Future of Data Analysis](https://projecteuclid.org/download/pdf_1/euclid.aoms/1177704711), and in 1977 a book, [Exploratory Data Analysis](https://www.amazon.com/Exploratory-Data-Analysis-John-Tukey/dp/0201076160) (fun fact: He also coined the terms 'bit'(**bi**nary digi**t**) and 'software'). Hence EDA is a process of analyzing data sets to summarize their characterestics, mathematically or visually.

### Understanding the data*
Exploratory data analysis is essential step before we begin identifying patterns in data. It helps us answer the following questions - 
1. Is the data accurate? Are there any outliers? All entries are valid and present?
2. Which models to use on the data?
3. How are the independent variables correlated?
4. How are the independent and dependent variables correlated?

The exploratory data analysis methods can be classified in the following ways -
1. Graphical vs non-graphical
    1. Graphical methods - summarize the data in a diagrammatic or pictorial way
    2. Non-graphical methods - calculation of summary statistics
2. Univariate vs multivariate exploration 
    1. Univariate methods - look at one variable (data column) at a time.
    2. Multivariate methods - look at two or more variables at a time to explore relationships.
    
Each category of exploratory data analysis explained.
1. Univariate graphical methods
    - Goals: 
        - Understand the sample distribution of the variable in consideration and draw tentative conclusions for the population distributions most compatible with the sample distribution. 
        - Identify outliers 
    - Methods based on types of data:
        - **Categorical Data**: The following three characteristics are of most interest in categorical data. 
            - Frequency of values: Count of a categorical value for a variable.
            - Relative frequency or proportion of values: Proportion of the above frequency to overall data points of that variable.
        - **Quantitative Data**
        - **Central Tendency**
        - **Spread**
        - **Skewness and kurtosis**

2.  Univariate graphical methods
    - Goals:
    - Methods:
        - **Histograms**
        - **Stem-and-leaf plots**
        - **Boxplots**
        - **Quantile-normal plots**
        
3.  Multivariate non-graphical methods
    - Goals:
    - Methods:
        - **Cross-tabulation**
        - **Correlation for categorical data**
        - **Univariate statistics by category**
        - **Correlation and covariance**
        - **Covariance and correlation matrices**
        
4. Multivariate graphical methods
    - Goals:
    - Methods:
        - **Univariate graphs by category**
        - **Scatterplots**

### Collecting the data 

### Cleaning the data


*[This](https://www.stat.cmu.edu/~hseltman/309/Book/chapter4.pdf) chapter on exploratory data analysis is the basis of the section understanding the data. (some parts have been copied)
