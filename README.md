# Public Education In 4 Dashboards #

## Research Question ##
How does money change educational outcomes? Or are there other factors involved?

## Executive Summary ##
This study looks at the US Census data on Educational achievement for public schools. The NAEP (National Assessment for Educational Progress) program test Reading and Math achievement in both 4th and 8th grade in odd years to track educational progress. 

## Discussion of Data ##
The first pictures looks at NAEP Test by US States and Years (2005 to 2015): [Tableau Dashboard 1 of NAEP Data](https://public.tableau.com/profile/david2973#!/vizhome/NAEPScores2005to2015/NAEPScores?publish=yes)
![NAEP Scores](https://github.com/yuchild/Public_Education_In_3_Dashboards/blob/master/Pics/naep_scores.png)

A takeway here is that reading scores are lower than math scores and 4th grade scores are lower than 8th grade scores overall with an overall postive trend from 2005 to 2015.
![NAEP Scores by Subject Year Grade Level](https://github.com/yuchild/Public_Education_In_3_Dashboards/blob/master/Pics/naep_scores_subject_year_grade_level.png)

The NEAP heatmap shows that scores are lower in the lower parts of the United States. The focus in the following discussion will center on two states: California and Texas. Feel free to explore [Tableau Dashboard 2 of Revenues, NAEP Scores, Expenditures, and Enrollment](https://public.tableau.com/profile/david2973#!/vizhome/EnrollmentScoresRevenuesExpenditures/RevenueScoresExpenditureandEnrollment?publish=yes)

What is happening to California and Texas? Both states have high enrollments Revenues, and Expenditures. But Texas has a better outcome in terms of NAEP Scores compare to California. What is happening here? To help make a compairson, look at New York as a compairson. 
![Snapshot of California, Texas, and New York Compairson](https://github.com/yuchild/Public_Education_In_3_Dashboards/blob/master/Pics/rev_NAEP_exp_enroll.png)

New York has lower a lower student enrollment number but not by much. What is similar about New York and Texas is state wide testing. To graduate high school Texas uses the TAKS and New York uses the Regents. California does not have a test requirement to graduate. For information about these tests see table below:

|State|Test|Link|
|---|---|---|
|Texas|TAKS|[Link](https://en.wikipedia.org/wiki/State_of_Texas_Assessments_of_Academic_Readiness)|
|New York|Regents|[Link](https://en.wikipedia.org/wiki/Regents_Examinations)|

So it seems states with exit exams for graduation perfrom better on the NAEP, no suprise there. However, is there a deeper connection with funding? Explore this Tableau dashboard on [Tableau Dashboard 3: Enrollment and Student Demographics](https://public.tableau.com/profile/david2973#!/vizhome/StudentDemographicsbyState/EnrollmentandStudentDemographics?publish=yes)

Can we drill down even more to look at what those states are doing at the school district level? Explore this [Tableau Dashboard 4 on Per Pupil Spending](https://public.tableau.com/profile/david2973#!/vizhome/CensusDataByDistricts/PerPupilDashboard?publish=yes)

# Conclusions #
The data shows that education is tied to funding. Per pupil spending in California is highest in our disucssion about NAEP test results. A possible explaination is the graduation requirements of exit exams in Texas and New York that are not in place in California. 

# Limitations and References #
This study is a survey of data from [Kaggle](https://www.kaggle.com/noriuk/us-education-datasets-unification-project) and [US Census Bereau](https://www.census.gov/data/tables/2015/econ/school-finances/secondary-education-finance.html). Future studies will encorporate more longititudinal span of data from the US Census Bereau going back to 2005. 
