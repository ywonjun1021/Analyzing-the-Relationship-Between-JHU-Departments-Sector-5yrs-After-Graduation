# Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation
Analyzed the different departments at JHU and saw the relationship of which sectors people work in 5 years after the graduation. Using the [NGLS Coalition PhD and Postdoc data][http://nglscoalition.org/coalition-data/#close], I analyzed the sector 5 years after graduation. The reason why I chose 5 years is becasue most people does not find a job right after graduation, but after 5 years, most people have their job. However, after 10 years after graduation, there is a possibility that people find their second job, and I wanted to analyze the first job people get after the graduation. 

#Cluster Analysis
Using [Tabula](https://tabula.technology/), I moved the pdf version of the data into an Excel file. 
Using cluster analysis, I calculated the z-score for "% for-profit," "% government," "% non-profit," and "% insufficient info." In addition, I calculated the distance squared and min distance squared for all sectors.
Then, I used the solver to find sum of minimum squared distance.

![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/Solver.png)

Then, I found three departments that were the center of the clusters.
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/3%20Departments%20.png)

1. Chemistry : High for-profit/ average government
2. Environmental Health & Engineering : High government/ Low non-profit
3. Biophysics & Program in Molecular Biophysics : Slightly below average government and non-profit






