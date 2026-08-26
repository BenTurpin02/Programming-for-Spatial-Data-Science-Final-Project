# Programming-for-Spatial-Data-Science-Final-Project
Submission for my final project for GEOG5415M

This data science project makes use of Leeds-based Secondary School Attendance Data and Deprivation data, both obtained from Data Mill North, to assess the potential relationship the two variables might share. It also makes use of geometry data of Leeds' LSOAs, obtained from the Office of National Statistics, to display spatial variation within the city of the relationship between deprivation and attendance rates. 

Prolonged absences from school have been shown to have significant impacts on the mental health of students, along with negative impacts to their academic achievements and subsequent future prospects (Middleton et al., 2025). The relationship between higher neighbourhood deprivation and forms of school absence (truancy, sickness-related absence, and temporary exclusion) has been found in contemporary literature (Klein et al., 2020) and appears to be an established trend. This report will attempt to find whether such trends are present within different LSOAs within Leeds. Through this, findings can be used to better inform local policy decisions to raise secondary school attendance levels.


This report makes use of three datasets:
| Source | Publisher | Dataset | Role |
|---|---|---|---|
| Data Mill North | Leeds City Council | Secondary School Attendance 2018/19 | Dependent variable |
| Data Mill North | Department for Communities and Local Government | Indices of Deprivation 2015 | Independent variable |
| ONS Open Geography Portal | Office for National Statistics | Leeds LSOA 2011 Boundaries | Spatial Analysis |


The Secondary School Attendance dataset bases its data on records of students living within certain LSOAs, rather than the attendance rates of schools in different LSOAs. It includes the number of secondary education sessions available within an LSOA, the number of education sessions attended, and an attendance percentage calculated from those two figures.

This makes it ideal for joining with the Indices of Deprivation dataset as both describe the same resident population area. The Indices of Deprivation Dataset expresses deprivation through an overall Index of Multiple Deprivation (IMD) score, made by combining seven domains of deprivation each with different weighting:
* Income Deprivation (22.5%)

* Employment Deprivation (22.5%)

* Education, Skills and Training Deprivation (13.5%)

* Health Deprivation and Disability (13.5%)

* Crime (9.3%)

* Barriers to Housing and Services (9.3%)

* Living Environment Deprivation (9.3%)


The LSOA 2011 boundaries for Leeds come courtesy of the Office for National Statistics, and are used for their geometry data allowing for spatial visualisation of results.
