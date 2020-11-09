# Pewlett Hackard Analysis

## Overview of the analysis
The objective of this analysis is determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, we will write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.  The following reports will be produced:

- The Number of Retiring Employees by Title
- The Employees Eligible for the Mentorship Program
- A written report on the employee database analysis
  
## Resources
- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employee.csv, salaries.csv, titles.csv
- Software: PostgreSQL, pgAdmin, VisualCode

## Results
The analysis of the Ride Sharing data show that:
  - Less urban cities have much lower of rides (by definition), but have even lowr number of drivers, which makes average Fare per Ride and especially Average Fare per driver be signicantly higher, as shown in the table below:
  
- Ride-Sharing Summary
![Ride-Sharing summary](/analysis/Ride_Sharing_DF.png)
  
 -  The total fare in urban cities are signifincatly higher than nom-urbans as shown in the chart below.  But this is mistly explained by higher number of rides, but not as much as total of drivers, as shown in the table above.
 
- Pyber-Fare Summary
![Pyber_fare_summary](/analysis/PyBer_fare_summary.png) 
 
## Summary

Based on the results above, we have the following recommendations:

  - Although there are fewer rides on non urban cities, the number of drivers are not enough to support this demand.  Therefore the company should increase the bumber of drivers in those cities, which by consequence, have a higher compensation per ride.
  - As lower prices per ride ate correlated to higher number of rides, the copany should decrease the price in non-urban areas to increase demand.
  - By reallocating driver's to non-urban areas, there will be room to increase fares on urban cities, and inprove the break-even.
