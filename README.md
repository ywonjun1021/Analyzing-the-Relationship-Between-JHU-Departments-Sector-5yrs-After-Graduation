# Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation
Analyzed the different departments at JHU and saw the relationship of which sectors people work 5 years after graduation. Using the [NGLS Coalition PhD and Postdoc data][http://nglscoalition.org/coalition-data/#close], I analyzed the sector 5 years after graduation. The reason why I chose 5 years is that most people do not find a job right after graduation, but after 5 years, most people have their job. However, after 10 years after graduation, there is a possibility that people find their second job, and I wanted to analyze the first job people get after graduation. 

#Cluster Analysis
Using [Tabula](https://tabula.technology/), I moved the pdf version of the data into an Excel file. 
I calculated the z-scores, the distance squared, and min distance squared for all sectors.
Then, I used the solver to find the sum of minimum squared distance.
## Solver
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/Solver.png)

Then, I found three departments that were the center of the clusters.
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/3%20Departments%20.png)


## Cluster Id and Summary of Findings
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/Cluster%20id.png)
For cluster 1, very few are high for-profit and average government
For cluster 2, less than half is high government and low non-profit.
Out of 21 departments, 11 departments were under cluster 3. This means that more than half is slightly below average government and non-profit. 


## Implications
Johns Hopkins can guide students from each department for their career path so they can end up in the sector they want. Knowing the information about which sectors the students ended up in from different department, students can predict their career path. 








