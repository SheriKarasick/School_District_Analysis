# School_District_Analysis
Prepared for PyCitySchools School District 

By Sharon Karasick

## Key Metric Summary
<p align="float: right">
  <img src="/PyCityPlay.png" width="200" title="PyCitySchools">
</p>
  This analysis examines the strengths of the PyCitySchools District and makes strategic recommendations based on key performance data. With the No Child Left Behind policy enactment, every district's goal is to ensure that all students are provided with the resources required to succeed in attaining core mathematical and reading skills, as measured by standardized performance examinations.  Each school and district strives to acheive the goal of a 70% passing rate for every student. This report will support the PyCitySchools District with identifying where district and school teams are not attaining this goal and frame conversations on next steps.

  While this data provides a powerful analysis examining results by school size, budget per student, and school type (District vs Charter).  Key social, professional staffing, and special education data is not incorporated into this report that would be critical in undertanding the nuances of this data required to make recommendations for improvements. However, this data analysis - as a high level framework, provides sufficient information to allow those additional questions to be contextualized and examined for additional analysis leading to district decisionmaking about strategic resource use.  
  The most notable findings are highlighted in this table:

Category | Reading Scores | Math Scores
For Thomas High School | Decreased by 26% | Decreased by 27%
Overall Averages | answer | answer
School Size | Medium Category Decreased Significantly | Medium Category Decreased Significantly
School Type | District Schools Decreased Significantly | District Schools Decreased Significantly
School by Cost per Student | 3rd Bin Decreased Significantly | 3rd Bin Decreased Significantly

### Key District Metrics, presented in table format

  In this analysis, we examine the analytical consequences of removing a group of 461 freshman students from Thomas High School.  Following concerns that some of the data is suspect, and the extent of the data issue is unknown,  the district would like to know how much exclusion of that data set from the District analysis will influence findings and decisionmaking. Data dashboards with reading and math data removed for 461 students will be noted as *Alternate*.
* District data remained largely unchanged.
* Percentage of students passing math and the overall students passing decreased by 1% point each. 

###### District Dashboard with All Students
<img src="/district_summary1.png" width="725" height="69" title="DistrictDashboard">

###### District Dashboard Alternate 
<img src="/district_summary2.png" width="725" height="69" title="DistrictDashboard">

### Overall District School Summary
Results summary for the 15 schools contained in the PyCitySchools District.
* No other school would be influenced by this data change except Thomas High School.
* Thomas High School experienced a notable decrease in reading and math scores with means decreasing by 27% and 26% respectively and the overall pass rate for both exams combined decreasing by 26%.

###### Summary Data by School
<img src="/school_summary1.png" width="725" title="School Dashboard">

###### Summary Data by School (Alternate)
<img src="/school_summary2.png" width="725" title="School Dashboard">

## Top 5 schools (based on overall pass rate)
The change influenced the ranking of schools in the District.  Thomas High School fell off the list of top five schools.

###### Top Five Schools in District
<img src="/school_top1.png" width="725" title="School Dashboard">

###### Top Five Schools in District (Alternative)
<img src="/school_top2.png" width="725" title="School Dashboard">

## Bottom 5 schools (based on overall pass rate)
The change did not influence the content of the list.

###### Bottom Five Schools in District
<img src="/school_bottom1.png" width="725" title="School Dashboard">

###### Bottom Five Schools in District (Alternative)
<img src="/school_bottom2.png" width="725" title="School Dashboard">

## School Performance Based on Grade

Given the parameters of the change, the 9th grade cohort at Thomas High School will appear as a NaN, other grades at Thomas High School, and all other grades at all other schools will be the same as prior to the data change.

## School Performance Based on Budget per Student
* Values changed downward for the bin of schools that containted Thomas High School, as expected.

###### Performance by Per Student Budget
<img src="/school_spend1.png" width="725" title="School Dashboard">

###### Performance by Per Student Budget (Alternative)
<img src="/school_spend2.png" width="725" title="School Dashboard">

## School performace based on size
* Values changed downward for the size of schools that containted Thomas High School, as expected.

###### Performance by School Size
<img src="/school_size1.png" width="725" title="School Dashboard">

###### Performance by School Size (Alternative)
<img src="/school_size2.png" width="725" title="School Dashboard">

## School performance based on type of school
* Values changed downward for the type of schools that containted Thomas High School, as expected.

###### Performance by School Type
<img src="/school_type1.png" width="725" title="School Dashboard">

###### Performance by School Type (Alternative)
<img src="/school_type2.png" width="725" title="School Dashboard">


## Resources used
* Jupyter Notebook File: PyCitySchools_Challenge.ipynb
* Source File with School Data: schools_complete.csv
* Source File with Student Data: students_complete.csv


