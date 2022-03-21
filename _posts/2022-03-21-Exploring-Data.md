---
title: AP Statistics Exploring Data
categories:
- AP Statistics
excerpt:
 Descriptive methods
 different methods for using collected data by organizing and summarizing it.
 depends on the type of data being collected.
feature_image: "https://picsum.photos/2560/600?image=872"
---

# Collecting Data

## Descriptive methods

different methods for using collected data by organizing and summarizing it.

depends on the type of data being collected.

# Types of Variables

### Categorical (qualitative)

places the individuals being studied into one of several groups or categories. 

ex. color, sex

### Numerical (quantitative)

can be analyzed using arithmetic operations 

ex. weight, IQ

# Types of Descriptive Methods

## Tabular Methods

$n$

number of observations

**frequency** $f$

# times it occurs

**relative frequency** $rf$ 

$$
 rf = \frac{f}{n}
$$

% times it occurs

**cumulative frequency** $cf$

# of observations ≤ to specific value 

**frequency distribution table**

table giving all possible values of a variable and their frequencies

# Graphical Methods:

## Qualitative Data

### Categorical Data

- **Bar Charts**
    
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cf4d535d-b515-49f9-a78d-1e25f05701aa/Untitled.png)
    
- **Pie Charts**
    
    rarely the best method of displaying data and have been shown to be misleading and hard to read accurately
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/14b7518c-1d0a-49a3-a9c1-ec80eabb5d6f/Untitled.png)
    

### Comparing Categorical Data with Two or More Groups

- **Segmented Bar Charts**
    
    takes the distribution from each group and arranges them along either the horizontal or vertical axis and shows the **relative frequency** of each group represented in one bar for each group
    
    used to show frequency with bars of various sizes or relative frequency where all bars are the same size regardless of group size
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/58e43a45-387e-4b98-a24f-4648ad082623/Untitled.png)
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04eec460-f463-4cef-8dad-3a485f8b4251/Untitled.png)
    
- **Mosaic Plots**
    
    alternative way to compare groups of categorical data distributions
    
    almost identical to a relative frequency segmented bar chart
    
    ! **difference** ! how to use x-axis
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5d87339a-27d2-455f-9ee2-927ce7a6637e/Untitled.png)
    

## Quantitative Data

### **Examining Graphs**

- center
    - mean
    - median
    - mode
- spread
    - range
    - standart deviation, variance of a distribution
- shape
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6df1ab1b-9745-47c5-8084-34a82eaa2c94/Untitled.png)
    
    - Symmetric distribution
    - Skewed distribution
- Patterns & Deviations
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/97ec590c-7a58-4cfa-8bcc-351de0d01944/Untitled.png)
    
    - clusters
    - gaps
    - outliers
        
        1.5 times the interquartile range(25th/75th %)
        

### Continuous Variables

- **Dot plots**
    
    effective for smaller data sets
    
    → for large data sets, box plot 
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c492c38a-47f8-4737-8c2e-fc037d4fd3be/Untitled.png)
    
- **Stemplots**
    
    
    | advantage | disadvantage |
    | --- | --- |
    |  shows every value |  inconvenient for large data sets  |
    
    **Stem** left-most part of each observation 
    
    **Leaf** remaining part
    
    can determine how data is *shaped and spread* and *center*
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a2126b4-d05d-47f2-ab76-61ff68975174/Untitled.png)
    
- **Histograms**
    
    useful for displaying *patterns* in large data sets
    
    can’t see how the data is spread out specifically
    
    can be drown using $f, rf, \%$
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5d070bd1-560b-40c6-a958-8fe53f4aa0eb/Untitled.png)
    
- **Cumulative Frequency Charts**
    
    S-shaped
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8056320-eb64-4243-9ae9-5a9f29a71fa7/Untitled.png)
    

# Univariate Data

### Summarizing Distributions

**Population** 

entire group of individuals or things that we are interested in

**Sample** 

part of the population that is actually studied

### Describing Distribution

- Center
- Spread
- Shape

## Numerical Methods

### Measures of Central Tendency

**Mean**

arithmetic mean (**average**)

affected by extreme or outlier measurements

- **Population Mean** $\mu$

$$
\mu = \frac{\sum^N_{i =1}X_i}{N}
$$

- **Sample Mean $\bar X$**

$$
\bar X = \frac{\sum_{i=1}^n X_i}{n}
$$

**Median $M$**

measure of central tendency

not affected by outliers

$$
l = \frac{n+1}{2}
$$

$$
⁍ = the value of the ⁍ measurement
$$

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/adef670c-1a83-4dcb-a0f3-5eb64fe64c8c/Untitled.png)

<aside>
💡 IF left skewed, mean <median

</aside>

### Measures of Variation (Spread)

**Range $R$**

difference between the largest and the smallest measurement in a data set

not reliable because it depends only on the two extreme measurement and doesn’t account for others

$$
R = range = largest\ measurement - smallest\ measurement
$$

**Interquartile range $IQR$**

range of middle 50% of data

not affected by outliers

<aside>
💡 If you use median as center, you should use IQR as range

</aside>

$$
IQR = Q_3 - Q_1
$$

**Standard Deviation**  

more useful measure than range

takes every measurement into account

affected by outliers

if there is outlier, IQR may be more useful 

- **Population Standard Deviation** $\sigma$

$$
\sigma = \sqrt{\frac{\sum_{i=1}^N(x_i-\mu)^2}{N}}
$$

- **Sample Standard Deviation $s$**

$$
s = \sqrt{\frac{\sum_{i=1}^N(x_i-\bar x)^2}{n-1}}
$$

<aside>
💡 0 means all are identical

</aside>

<aside>
💡 larger standard deviation indicates larger spread among the measurements

</aside>

**Variance** 

always positive

$$
{standard\ deviation}^2
$$

### Measures of Position

**Percentiles**

divide a set of values into 100 equal parts

$$
⁍
$$

**Quartiles**

$$
Q_1 = P_{25}
$$

$$
Q_2 = P_{50} = median
$$

$$
Q_3 = P_{75}
$$

**Standardized Scores** or **z-scores**

$$
z~score=\frac{measurement-mean}{standard\ deviation}
$$

| negative | positive |
| --- | --- |
| smaller than mean | larger than mean |

# Graphing Univariate Data

## Graphical Summaries

even same revenue data seems different due to y-axis

- **Box plots**
    
    box-and-whiskers plot
    
    based on measures of position 
    
    useful for identifying outliers and the general shape of the distribution
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f84d3b82-78b4-4a50-8cfd-616fccdec949/Untitled.png)
    

## Effect of changing units on summary measures

| Summary Measure | ⁍ | ⁍ |
| --- | --- | --- |
| Mean | ⁍ | ⁍ |
| Median | ⁍ | ⁍ |
| Range | ⁍ | ⁍ |
| Standard Deviation | ⁍ | ⁍ |
| Quartiles | ⁍ | ⁍ |
| Interquartile Range | IQR(Y)=IQR(X)\ unaffected | ⁍ |

## Comparing Distributions of Two or More Groups

- **Parallel dot plots**
    
    showing the errors made by both scanners
    
    used to compare two or more data sets
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5240711f-5a23-4ce4-b2ab-b81422a14860/Untitled.png)
    
- **Parallel box plots**
    
    showing the errors by both scanners
    
    used to compare two or more data sets
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1b04cb1c-f3f9-4caa-b4b8-83b6659053e9/Untitled.png)
    
- **Back-to-back stem plots**
    
    showing the errors by both scanners
    
    can only be used to compare two data sets
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/297f466e-c070-42f3-98fb-42490a75f120/Untitled.png)
    
- **Two histograms**
    
    showing the errors by both scanners
    
    not a great option
    
    use same scale for both 
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3bde42f-d1af-4f12-97a0-d6338134a71b/Untitled.png)
    
- **Multiple frequency polygrams (line graph)**
    
    **frequency polygram** 
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/076be965-cbd9-4b8c-a822-6511a941b1db/Untitled.png)
    

## Exploring Bivariate Data

**Bivariate Data** 

two different variables collected from each item in a study

**Linear regression** two different quantitative variables have a linear relation

| Scatterplot | graphical summary measure |
| --- | --- |
| correlation coefficient | numerical summary measure |

## Graphing Categorical Bivariate Data

### Scatterplot

used to describe the nature, degree, and direction of the relation between two variables x and y

**shape** 

| linear | non-linear |
| --- | --- |

**Direction** 

| Positive (direct) relation | Negative (inverse) relation |
| --- | --- |
| increases | decreases |

**Strength of relationship**

| Strong | Weak | No |
| --- | --- | --- |
| close to the line | loosely scattered | scattered w/o pattern |

# Numerical methods for continuous bivariate data

## Correlation Coefficient

**Pearson’s correlation coefficient** 

numeric measure of the strength & direct of the linear relation between two quantitative variables

| population correlation coefficient | sample correlation coefficient |
| --- | --- |
| ⁍ | ⁍ |
|  | ⁍ |

**Direction**

| Positive | negative |
| --- | --- |

**Strength**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3f1d4afa-71c6-421b-8fb7-ed1ffcb26e06/Untitled.png)

**relation between slope of the line(b) and the correlation coefficient(r)**

$$
b = r(\frac{S_y}{S_x})
$$
_Originally from The Princeton Review_
