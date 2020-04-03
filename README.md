# Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation
Analyzed the different departments at JHU and saw the relationship of which sectors people work 5 years after graduation. Using the [NGLS Coalition PhD and Postdoc data][http://nglscoalition.org/coalition-data/#close], I analyzed the sector 5 years after graduation. The reason why I chose 5 years is because most people do not find a job right after graduation, but after 5 years, most people have their job. However, after 10 years after graduation, there is a possibility that people find their second job, and I wanted to analyze the first job people get after graduation. 

#Cluster Analysis
Using [Tabula](https://tabula.technology/), I moved the pdf version of the data into an Excel file. 
I calculated the z-scores, the distance squared, and min distance squared for all sectors.
Then, I used the solver to find the sum of minimum squared distance.
## Solver
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/Solver.png)

Then, I found three departments that were the center of the clusters.
![alt](https://github.com/ywonjun1021/Analyzing-the-Relationship-Between-JHU-Departments-Sector-5yrs-After-Graduation/blob/master/3%20Departments%20.png)

1. Chemistry : High for-profit/ average government
2. Environmental Health & Engineering : High government/ Low non-profit
3. Biophysics & Program in Molecular Biophysics : Slightly below average government and non-profit

## Cluster Id and Summary of Findings
![alt]()



## Implications
In the future, Johns Hopkins University can guide students from each department for their career path so they can end up in the sector they want. Knowing the information about which sectors the students ended up in from different department, students can predict their career path vaguely. 








