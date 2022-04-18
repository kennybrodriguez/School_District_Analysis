# School_District_Analysis

## Overview
This project involved analyzing test data for a high school district. This involved importing the data, formatting, and running an analysis using Pandas. The aim of the project was to ensure the testing data remained accurate. Irregularities in Thomas High Schools 9th grade class is what prompted the change to 'nullify' their grades. Reran the analysis to see what changes occurred.

## Results

### District
- Total schools remained the same at 15
- total students remained the same at 39,170
- total budget remained the same at $24,649,428.00
- average math score dropped from 79 to 78.9
- average reading score remained the same at 81.9
- percentage passing math dropped from 75 to 74.8
- percentage passing reading dropped from 86 to 85.7
- overall percentage passing both dropped from 65 to 64.9
![Results](/Resources/1.PNG)

### School
After changing the 9th grade class test scores for Thomas High school, we see a major change
- dropped the overall passing percentage from 90.94 to 65.07
- percentage passing reading dropped from 97.3 to 69.66
- percentage passing math dropped from 93.27 to 66.9
- average math score changed from 83.41 to 83.35
![Results](/Resources/2.PNG)


After updating the student count to reflect only grades 10-12
- Overall passing changed from 90.94 to 90.63
- % passing reading changed from 97.30 to 97.01
- % passing math changed from 93.27 to 93.18
- average reading score changed from 83.84 to 83.89
- average math score changeed from 83.41 to 83.35
![Results](/Resources/3.PNG)

## Summary
After altering the grade of the 9th grade class at Thomas High school, there was a minor change to the overall district data due size of the 9th grade class in comparison to the total student body of the district. The per_school summary changed quite a bit with the nullification of the 9th grade test scores for Thomas High school. This dropped the overall passing percentage from 90.94 to 65.07. The percentage passing reading dropped from 97.3 to 69.66 and the percentage passing math dropped from 93.27 to 66.9. 

These changes were taking into account the total student body of Thomas High School. We see that this caused the numbers to be skewed. Once we adjust for just grades 10-12, we see that actually the per school results for Thomas High School are similar to the previous results. This is displayed above under "School". This helps paint a clearer picture of Thomas High School without the 9th grade class and hopefully help make clearer decisions on the data. 