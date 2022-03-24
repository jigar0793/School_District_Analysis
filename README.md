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

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. 

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872500-d7992a0d-b365-4147-b5de-ddbef71efbc8.png">

#### Adjusted Analysis

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872546-6f28654d-09c4-44ee-827f-f70bf6f3d288.png">

Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate. The change of adding Nan to all grade 9 and Thomas High School math and reading scores did not have a large impact on the district analysis as:

    - Each metric decresing by less that 0.5 percentage point each (meaning scores changed by less than 0.5%)
    - The total student count is 39,170, the grade 9 students only make up 1.2% of the total student count

### Impact on the School Summary & Thomas High School Relative Performance

#### Original Analysis

In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872593-556f7888-afc3-406d-bc00-e364f062b0d7.png">

#### Adjusted Analysis

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872644-3e0d8dae-a52f-43ba-9b14-cca6f59d659b.png">

After adjusting the 9th grade data, Thomas High School ranked at 13th position from 2nd rank.

### How does replacing the ninth-grade scores affect the following:

#### Original Analysis:

##### Average Math Scores
<img width="305" alt="image" src="https://user-images.githubusercontent.com/94248676/159872707-85c7a2e8-8dd0-4ebf-987c-099b498c3b65.png">

##### Average Reading Scores
<img width="308" alt="image" src="https://user-images.githubusercontent.com/94248676/159872767-bdc2b8f5-64e3-4d6f-bff6-f293a1092c77.png">

In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests.

#### Adjusted Analysis:

##### Average Math Scores
<img width="305" alt="image" src="https://user-images.githubusercontent.com/94248676/159872830-13841a36-0a66-44e7-982a-31373a7fd97b.png">

##### Average Reading Scores
<img width="307" alt="image" src="https://user-images.githubusercontent.com/94248676/159872871-d33d5a0a-8f8d-49d5-8112-6e9be545288b.png">

Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.

### Scores by school spending

#### Original Analysis:

Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872964-b079c80d-acad-4f5b-96c7-02e8ee5e4b78.png">

#### Adjusted Analysis:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159872997-dc5e57f2-a75e-430d-a1c3-44aa42e7a49b.png">

By changing the 9th grade scores, there was very little spending impact.

### Scores by school size

### Original Analysis:

Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159873040-2b1c954e-0e94-4ca5-9215-7a06e5b7ef99.png">

#### Adjusted Analysis:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159873079-0acbdf42-a785-4f65-a6dc-15d1b1375d17.png">

There was very little impact by campus size due to changing the 9th grade scores.

### Scores by school type

Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.

#### Original Analysis

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159873129-04249eeb-e8b0-453b-9a4d-0e99c035e181.png">

#### Adjusted Analysis

<img width="468" alt="image" src="https://user-images.githubusercontent.com/94248676/159873165-bc456aad-0882-4c66-9ce0-fc1d534febb2.png">

There was very little impact by school type by changing the 9th grade scores.

## Summary: 

The major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed dramatically from 90.94% to 65.07%.

2. Thomas High School's ranking dropped from 2nd to 13th in the district of 15 campuses.

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

4. In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.



