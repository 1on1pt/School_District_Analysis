# School_District_Analysis
School district analysis for Py City Schools.
## Overview of the School District Analysis
Maria, who is the Chief Data Scientist for the Py City School District, has been tasked with preparing all standardized test data for analysis and using this information to report on performance trends and patterns.  She has asked for my assistance in analyzing funding and standardized test score data so that this information can be presented to the school board and superintendent.

After the initial report was completed, the school board discovered that there was evidence of academic dishonesty where the Thomas High School ninth grade math and reading scores were altered.  The school board has asked that the math and reading scores at Thomas High School be replaced with NaNs while keeping the rest of the report intact.

This presentation will include a disussion on how removing the Thomas High School ninth grade math and reading scores from the original report affected the overall analysis.  The final school district analysis will ultimately assist the school board and superintendent in their budgeting process and setting priorities.

**This comprehensive school district analysis included the following metrics:**
* The District Summary
* The School Summary
* The Top 5 Performing Schools
* The Bottom 5 Performing Schools
* The Average Math Grade for Each Grade Level from Each School
* The Average Reading Grade for Each Grade Level from Each School
* The Scores by School Spending Per Student, by School Size, and by School Type

### Resources
Data Source: schools_complete.csv; students_complete.csv

Code: PyCitySchools_Challenge.ipynb

Software: Python 3.7.6; Pandas 1.3.5; Jupyter Notebook

## Results
### 1. How is the district summary affected?

* The total number of students in the district summary was the most significant change when comparing the original summary (39,170 students) with the revised summary (38,709 students) for an overall difference of 461 less students in the revised summary.

**Original Summary**

![image](https://user-images.githubusercontent.com/94148420/149846032-c2ba37b8-f52f-49ea-8093-cb6fe37bb62e.png)

**Revised Summary**

![image](https://user-images.githubusercontent.com/94148420/149845893-04d31948-b1df-42bb-8435-8ab6424a843d.png)

### 2. How is the school summary affected?

* Replacing the Thomas High School ninth grade math and reading scores with NaN did not significantly affect the overall school average math and reading scores, percent passing math and reading, and % overall passing.  The orignal versus revised summary demonstrated -.067 difference for average math score, +.047 for average reading score, -.086 for % passing math, -.290 for % passing reading, and -.318 for % overall passing.

**Original Summary**

![image](https://user-images.githubusercontent.com/94148420/149846913-b5b0520e-b500-49d3-8cb3-7b1ace53ffe9.png)

**Revised Summary**

![image](https://user-images.githubusercontent.com/94148420/149846637-48659107-28de-456e-83c0-cd2ab818a7b3.png)

### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* Replacing the Thomas High School ninth grade math and reading scores with NaN did not affect the high school's performance relative to the other schools.
* Thomas High School was able to maintain as the second highest performing high school in the district.

**Original Summary**

![image](https://user-images.githubusercontent.com/94148420/149848368-6b8a6f1f-46c7-4880-837e-aed892a0c637.png)


**Revised Summary**

![image](https://user-images.githubusercontent.com/94148420/149850229-a6ad7202-9310-4c5f-8241-db8cbc273c61.png)

### 4. How does replacing the ninth-grade scores affect the following:

* **Math and reading scores by grade**

  * Replacing the Thomas High School ninth grade math and reading scores resulted in NaNs in the 9th grade column.  Below is an example demonstrating the results comparing the original with the revised math score. 

**Math Score Original Summary**

![image](https://user-images.githubusercontent.com/94148420/149851867-62b91e28-4660-4c48-90bc-dd9964a1eec0.png)

**Math Score Revised Summary**

![image](https://user-images.githubusercontent.com/94148420/149851686-53c46767-0ac4-4bd2-8bd6-8ee9aa365e2c.png)

* **Scores by school spending**



**Original Summary**

![image](https://user-images.githubusercontent.com/94148420/149852670-d2663ab3-2f30-4e6e-9519-f8e59f1cb8fa.png)

**Revised Summary**

![image](https://user-images.githubusercontent.com/94148420/149852583-495ddcfa-7a63-4b3b-b5a5-524da1e200af.png)



* **Scores by school size**

**Original Summary**


**Revised Summary**

* **Scores by school type**


**Original Summary**


**Revised Summary**


## Summary
