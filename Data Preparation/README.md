
# Data Preparation

### What is Exploratory Data Analysis (EDA)?
While classical statistics focused primarily on inference, i.e. the process of drawing conclusions about large datasets on the basis of small samples, exploratory data analysis or data analysis was a field (of which inference is a part) that began and gained momentum on the basis of work done by John W. Tukey. In 1962, he published a paper [The Future of Data Analysis](https://projecteuclid.org/download/pdf_1/euclid.aoms/1177704711), and in 1977 a book, [Exploratory Data Analysis](https://www.amazon.com/Exploratory-Data-Analysis-John-Tukey/dp/0201076160) (fun fact: He also coined the terms 'bit'(**bi**nary digi**t**) and 'software'). Hence EDA is a process of analyzing data sets to summarize their characterestics, mathematically or visually. [1]

### Understanding the data
The data that we will deal in this course comes from sources in the form of raw unstructured data which can't be understood by a software without refinement. Examples include electronic medical records (EMRs), images (jpegs), instant messages, etc. These types of data do not have a strict data model to adhere to. To convert this data to structured data such as ordered list, database table or spreadsheets, we must do the following -  
1. Identify data types
    - Numeric 
    - Categorical
    - Ordinal
2. Fit the dataset into a structured object
    - Rectangular 2D objects such as a spreadsheet, database table
        - Feature
        - Outcome
        - Records
    - Non rectangular data objects 
        - Time series data
        - Spatial data structure
        - Graphs

Once, we have converted the raw data to structured data, we can start analyzing the data. 
### Exploring Numerical Data
1. Analyzing data in a single number
    1. Finding estimates of location
        - Mean
        - Median
        The key factors in identifying the appropriate estimate of locations is **robustness**.
    2. Finding estimates of variability
        - Standard deviation
        - Estimate based on percentiles
2. Analyzing data as a distribution
    - Percentiles
    - Boxplots
    - Frequency tables
    - Histograms
    - Density estimates.

### Exploring Binary/Categorical Data
1. Analyzing data in a single number
    1. Mode
    2. Expected value
2. Analyzing data as a distribution
    1. Bar charts
    2. Pie charts

### References
[[1.]](https://en.wikipedia.org/wiki/Exploratory_data_analysis) Exploratory Data Analysis

[[2.]](https://www.techopedia.com/definition/13865/unstructured-data) Unstructured data definition

[[3.]](https://www.amazon.com/Practical-Statistics-Data-Scientists-Essential/dp/1491952962) Practical Statistics for Data Scientists
