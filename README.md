# School_District_Analysis1

Overview:

  The purpose of this anaylsis was to introduce the pandas in jupyter notebook. Pandas were useful to quickly and simply manipulate and extract information from multiple data sets. In this challenge, a district wanted to gather information and data breakdowns based on its high schools' test scores from a standardized test (reading and math). The district has 15 different high schools (7 district, 8 charter), each with 4 grades. At one of the schools there was supected academic dishonesty, so all of the test scores for the 9th grade were deemed defunct.

Results:

  The district wide summary indicated that there were 39,170 students. ~75% passed math, ~86% passed reading, and ~65% passed both. Based on this information, the district needs to improve it's math teaching the most. Here is the district summary:

![districtsummary](https://github.com/jrg12300/School_District_Analysis/blob/main/districtsummary.png)
  
  
  The school breakdown summary shows all of the analytics broken up by the individual high schools. One higher level analysis that I did was to see if there was a correlation between Per Student Budget and test performance. To do this, I split up the summary by school type (more on this later), and plotted "Per Student Budget" vs "% Overall Passing." The results are shown below, and there does not appear to be a strong relationship between the two facotrs (despite the fact that it logically would seem that more funds = better scores).

![CharterSchools](https://github.com/jrg12300/School_District_Analysis/blob/main/CharterSchools.png)

![DistrictSchools](https://github.com/jrg12300/School_District_Analysis/blob/main/DistrictSchools.png)
 
  For Thomas High School, the 9th grade's test scores were removed. However, this did not change the averages very much, as the 9th grade did not perform better or worse than the other THS grades. The tables below shows this.
  
  Math & Reading Scores by Grade:
  
  ![MATH](https://github.com/jrg12300/School_District_Analysis/blob/main/MathScoreByGrade.png)
  
  ![READING](https://github.com/jrg12300/School_District_Analysis/blob/main/ReadingScoreByGrade.png)
  
  Scores by School Spending (Were not significantly changed by removing THS 9th Grade):
  
  ![SPENDING](https://github.com/jrg12300/School_District_Analysis/blob/main/GradesbySpending.png)
  
  Scores by School Size (Were not significantly changed by removing THS 9th Grade):
  
  ![SIZE](https://github.com/jrg12300/School_District_Analysis/blob/main/ScoresbySize(THSleftin).png)
  
  Scores by School Type (Were not significantly changed by removing THS 9th Grade):
  
  ![TYPE](https://github.com/jrg12300/School_District_Analysis/blob/main/SCORESBYTYPE.png)

Summary:

  From the analysis, the THS 9th graders performed very similarly to the other students in their school and school type (charter). When the numbers are taken to 1 decimal place, the summaries for spending, size, and type were unafected. The analysis did not change due to school size, because the school size was not changed when THS was taken out. 
  
  


Summary:
