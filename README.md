# School_District_Analysis

School District Analysis using Python, Pandas Library, Numpy Library, Anaconda & Jupyter Notebook

## Overview of Project

The School Board would like to understand various key performance metrics of the different school districts and schools so that they would be able to decide budget according to the analysis. We will be working with Maria to provide the initial analysis based on data collected from many students and schools across the school district.

The School Board is satisfied with the understanding that we have provided in our work Maria, it has been distinguished that there have all the earmarks of being a few inconsistencies in the information, specifically in the math and perusing scores of the grade nine students at Thomas High School. To ensure these outcomes don't skew the analysis, the Board has asked us to again work with Maria to eliminate the effect of these outcomes by changing all the grade 9 Thomas High School math and reading scores to Nan (Null).

The School Board will like to understand the impact of changing all the grade 9 math and reading scores at Thomas High School to Nan - we will now review how this change impacted various parts of the analysis relative to when it was ran including the Thomas High School grade 9 scores.

## Resources

### Softwares: 

Python 3.10.3, Visual Studio Code 1.65, Anaconda 5.0, Jupyter Notebook 6.4.8, Pandas

### Data Sources: 

PyCitySchools.ipynb, schools_complete.csv & students_complete.csv

## Results Analysis:

### Impact on District Analysis:

#### Original Analysis

Pic 1

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. 

#### Adjusted Analysis

pic 2

Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate. The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have a large impact on the district analysis as:

    - Each metric decresing by less that 0.5 percentage point each (meaning scores changed by less than 0.5%)
    - The total student count is 39,170, the grade 9 students only make up 1.2% of the total student count

### Impact on the School Summary & Thomas High School Relative Performance

#### Original Analysis

pic 3

In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board.

#### Adjusted Analysis

pic 4

After adjusting the 9th grade data, Thomas High School ranked at 13th position from 2nd rank.

### How does replacing the ninth-grade scores affect the following:

#### Original Analysis:

##### Average Math Scores
pic 5

##### Average Reading Scores
pic 6

In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests.

#### Adjusted Analysis:

##### Average Math Scores
pic 7

##### Average Reading Scores
pic 8

Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.

### Scores by school spending

#### Original Analysis:

pic 9

Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes.

#### Adjusted Analysis:

pic10

By changing the 9th grade scores, there was very little spending impact.

### Scores by school size

### Original Analysis:

Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes.

pic11

#### Adjusted Analysis:

pic12

There was very little impact by campus size due to changing the 9th grade scores.

### Scores by school type

Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.

#### Original Analysis

pic13

#### Adjusted Analysis

pic 14

There was very little impact by school type by changing the 9th grade scores.

## Summary: 

The major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed dramatically from 90.94% to 65.07%.

2. Thomas High School's ranking dropped from 2nd to 13th in the district of 15 campuses.

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

4. In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.



