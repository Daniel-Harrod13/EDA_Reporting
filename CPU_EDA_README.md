# CPU EDA Report


## Overview

This Jupyter notebook contains an exploratory data analysis (EDA) report on CPU data. The analysis includes data cleaning, visualization, and statistical analysis to understand the performance and characteristics of different CPUs.

# EDA: CPU Benchmarks

```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 3825 entries, 0 to 3824
Data columns (total 12 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
 0   cpuName      3825 non-null   object 
 1   price        1967 non-null   float64
 2   cpuMark      3825 non-null   int64  
 3   cpuValue     1967 non-null   float64
 4   threadMark   3825 non-null   int64  
 5   threadValue  1967 non-null   float64
 6   TDP          3140 non-null   float64
 7   powerPerf    3140 non-null   object 
 8   cores        3825 non-null   int64  
 9   testDate     3825 non-null   int64  
 10  socket       3825 non-null   object 
 11  category     3825 non-null   object 
dtypes: float64(4), int64(4), object(4)
memory usage: 358.7+ KB

```

# Market Share of CPU types 

## Number of Cores vs Mutli-core Score 

## Turbo Clock Rate vs Single-core Score 


## Benchmark conclusion
#####  There is a postive correlation between number of cores and the multi-core score printed above. There is also a postive correlation between the turboclock rate and single-core score. 

## Number of CPU for Socket Type

#### We will now remove the unknowns from the figure above 

## Socket Types 
#### Using the figure above we can see that AM4 seems to be the most popular socket type used. 

