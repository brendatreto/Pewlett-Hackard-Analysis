# Pewlett-Hackard-Analysis

## Overview
In preparation for the upcoming 'silver tsunami' PH is getting its data ready. They had a thorough collection of data from its employees, but it needed an upgrade. Using newer programming languages, we intended to make it easier to read and analyze.

## Resources
- pgAdming4
- PostgreSQL

## Results
*Fig 1. Titles of retiring employees*

![unique_titles](https://user-images.githubusercontent.com/22451540/153690094-aeaa713d-b5b4-4af0-a67f-ff275d8feef3.PNG)

*Fig 2. Number of employees retiring per department*

![retiring_titles](https://user-images.githubusercontent.com/22451540/153690192-b27c262c-6b80-434f-92e3-c7a5c2dced9f.PNG)

*Fig 3. Eligible employees for the mentorship program*

![mentorship_elegibility](https://user-images.githubusercontent.com/22451540/153690264-df7a4242-7a73-40ca-b6cd-1ff403bc9744.PNG)

These images show the result of the analysis, and we can confidently say:
1. Almost 70% of the retiring employees hold a senior position
2. Managerial positions will not be affected by this 'silver tsunami' which can make the transition easier
3. There is a severe mismatch in the number of mentorship eligible employees (1,549) and retiring employees (~133,000) (or positions to fill).
4. Most eligible employees for the mentorship programs also hold senior positions.


## Summary 
In a perfect scenario, as the silver tsunami approaches, the company needs to prepare and look for 13,505 new employees. This number is the result of evaluating the number of people that are currently working at PH, have been there since 1985 to 1988, and were between 1962 and 1965 to be eligible to leave work. The plan is to offer these people the mentorship program so that they can keep mentoring new employees. In theory these employees are enough, and because they hold senior positions, they are qualified. Nevertheless PH needs to have a backup plan in order to avoid overworking the employees.

*Fig 4. Query of retiring employees by gender*

![Additional_query1](https://user-images.githubusercontent.com/22451540/153691513-002e5a0c-7641-43e2-8ae9-e27a481af110.PNG)

![Additional_query2](https://user-images.githubusercontent.com/22451540/153691515-949300a5-e96e-45b5-b101-79314e77838b.PNG)


This additional query shows that there is a big imbalance between male and female retiring employees which can serve to analyze its practices and evaluate if there needs to be any adjustment made to make the company more committed with equality.

*Fig 5. Retiring employees by gender*

![retiring_gndr](https://user-images.githubusercontent.com/22451540/153691581-3ef5d5cd-1cc8-414b-a34d-ccecc72ac7f2.PNG)


The same query was repeated for the mentorship eligibility 

*Fig 6. Query of eligible employees by gender

![gender_elegibilty](https://user-images.githubusercontent.com/22451540/153691790-116d068a-7959-462e-98dc-7080b73f437e.PNG)

*Fig 7. Eligible employees by gender*

![elegibility](https://user-images.githubusercontent.com/22451540/153691744-53e382f8-6312-429a-a038-f477564d0947.PNG)


The results are remarkably similar. The company needs to take conscious steps to include more women in the decision-making positions and ensure parity.


## Concluding thoughts
Using newer tools to perform the analysis allows companies, -and any interested party- to perform more in-depth queries and look for key information that will let them make better decisions based on the actual data, eliminating biases, and enriching the results.
