
# Data Preparation

### What is Exploratory Data Analysis (EDA)?
While classical statistics focused primarily on inference, i.e. the process of drawing conclusions about large datasets on the basis of small samples, exploratory data analysis or data analysis was a field (of which inference is a part) that began and gained momentum on the basis of work done by John W. Tukey. In 1962, he published a paper [The Future of Data Analysis](https://projecteuclid.org/download/pdf_1/euclid.aoms/1177704711), and in 1977 a book, [Exploratory Data Analysis](https://www.amazon.com/Exploratory-Data-Analysis-John-Tukey/dp/0201076160) (fun fact: He also coined the terms 'bit'(**bi**nary digi**t**) and 'software'). Hence EDA is a process of analyzing data sets to summarize their characterestics, mathematically or visually. [1]

### Understanding the data
The data that we will deal in this course comes from sources in the form of raw unstructured data which can't be understood by a software without refinement. Examples include electronic medical records (EMRs), images (jpegs), instant messages, etc. These types of data do not have a strict data model to adhere to. To convert this data to structured data such as ordered list, database table or spreadsheets, we must do the following -  
1. __Identify data types__
    - Numeric: This can be continuous or discrete numerical values. For e.g. continuous such as temperature, discrete such as count of students in a classroom.
    - Categorical: This type of data takes a fixed set of values. For e.g. types of car (Hatchback, Sedan, SUV), types of diabetes etc.
    - Ordinal: This type of data has strict ordering among its elements. For e.g. rating of a movie (1,2,3,4,5). Binary and ordinal data is type of categorical data.
    
    Correct classification of data is important to determine method for data analysis, statistical model and visualization to represent the data.

    ---
    Additional Reading
    - [SQL Data Types](w3schools.com/sql/sql_datatypes.asp)
    - [Python Data Types](https://docs.python.org/3/library/datatypes.html)
    ---

2. __Fit the dataset into a structured object__
    Once we have identified the type of data, we must fit the data either in a rectangular 2D matrix or a non-rectangular data structure like a graph. 
    - __Rectangular data objects__
    
        Examples of rectangular 2D objects are spreadsheets and database table. The rows indicate records and columns indicate features or variables of a data set. We will define them below for clarity.
        - Feature: A characteristic of the data, specified in columns of a table, usually an independent variable. Also known as a variable, predictor, input or attribute.
        - Outcome: This is a dependent variable, usually a function of the independent variables or features. Outcome specifies the ouput or result of data analysis exercise. Also known as response, target.
        - Records: Each row in the data set is a record. Also known as observation, sample, case.
        Rectangular data in Python can be rendered using dataframe object of the [Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) library. Data frame can be created from dictionary (from_dict), from tuples and record arrays (from_record).
        
            ```python
            >>> import pandas as pd
            >>> data = {'col1': [1, 2], 'col2': [3, 4]}     # dictionary object
            >>> df = pd.DataFrame.from_dict(data)           # data frame created from dictionary object
            >>> df
               col1  col2
            0     1     3
            1     2     4
            ```
    ---
    Additional Reading
    - [DataFrame in Python](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
    - [DataFrame from Dict](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.from_dict.html#pandas.DataFrame.from_dict)
    - [DataFrame from Records](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.from_records.html#pandas.DataFrame.from_records)
    ---

    - __Non rectangular data objects__
        - Time series data: 
        - Spatial data structure:
        - Graphs:

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
