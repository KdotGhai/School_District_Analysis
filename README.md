# School_District_Analysis
PyCitySchools with Pandas

<br /> &nbsp;&nbsp;&nbsp;&nbsp;In this module we will be utilizing *Jupyter Notebook* and *Pandas* to assist in the creation of a District Analysis of High Schools, we'll be breaking down the performance of these high schools based upon their standardized test-scores for math/reading. From there we will break down the performance of each student, each school, Overall performance, and school-type performance. Furthermore, we will create data-tables to look for correlations in budget per school, budget per student, and performance by school size. Lastly, we will be exempting data due to academic dishonesty occurring at *Thomas High School* and the entirety of its 9th graders are the once to be excluded from the data. With this exemption, we will display the difference in scores and performance in the school so that the schoolboard has easily digestible data to make decisions upon. <br /> 

**1.District Summary:**
  -<br /> &nbsp;&nbsp;&nbsp;&nbsp;Here we can notice there isnt much of a drastic change in District analsyis when exempting students, there isnt a large enough disparity in the total student count as well as, scores of students under the assumption there wasnt more academic dishonesty in student scores. <br />
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Original: <br /> 
   ![Original District Summary](Resources/images/original_district_summary.png)
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted: <br /> 
   ![Exempted District Summary](Resources/images/exempted_district_summary.png)
   
**2.School Summary:**
   -<br /> &nbsp;&nbsp;&nbsp;&nbsp;As we break down the data per school we canb egin to notice the devil in the details, *Thomas High School* performance is barely passing when including data of its 9th Graders. Afterward, once we'd exempted the entirety of their 9th grade students we see that the school performs better(the drastic difference in Overall Percentage Passing shows the impact of excluding data), ofcourse this data makes it biased if we had not included the orignal for comparison. <br />
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Original: <br /> 
   ![Original Per School Summary](Resources/images/original_per_school_summary-fixed.png)
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted: <br /> 
   ![Exempted Per School Summary](Resources/images/exempted_per_school_summary.png)

**3.Spending Per Student:**
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Overall, there were no major changes in spendinging per student as the number of exempted students is small and the difference in "spending per student isnt high enough to have a significant impact on the performance of the students. In fact, the data clecarly shows no clear correlation between spending per student as welll as, total budget having an impact on the schools performance for both math & reading. <br />

 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Original: <br /> 
   ![Original Per Student](Resources/images/original_spending_per_student.png)
 <br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted: <br /> 
   ![Exempted Per Student](Resources/images/exempted_spending_per_student.png)

**4. Top 5 & Bottom 5:**

<br /> &nbsp;&nbsp;&nbsp;&nbsp;Original Top 5: <br /> 
   ![Original  Top 5](Resources/images/original_top_five.png)
<br /> &nbsp;&nbsp;&nbsp;&nbsp;Original Bottom 5: <br /> 
   ![Original Bottom 5](Resources/images/original_bottom_five.png)

<br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted Top 5: <br /> 
   ![Exempted  Top 5](Resources/images/exempted_top_five.png)
<br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted Bottom 5: <br /> 
   ![Exempted Bottom 5](Resources/images/exempted_bottom_five.png)
   
**5.School Size Scores:**

<br /> &nbsp;&nbsp;&nbsp;&nbsp;Original School Size Scores: <br /> 
   ![Original School Size Scores](Resources/images/original_school_size_scores.png)
<br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted School Size Scores: <br /> 
   ![Exempted School Size Scores](Resources/images/exempted_school_size_scores.png)


**6.School Type Scores:**
<br /> &nbsp;&nbsp;&nbsp;&nbsp;Original School Type Scores: <br /> 
   ![Original School Type Scores](Resources/images/original_school_type.png)
<br /> &nbsp;&nbsp;&nbsp;&nbsp;Exempted School Type Scores: <br /> 
   ![Exempted School Type Scores](Resources/images/exempted_school_type.png)

