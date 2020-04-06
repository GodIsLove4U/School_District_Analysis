# School_District_Analysis
The school and student data was analyzed and prepared to be presented to the school board after utilizing a cleane dataset with all of the students information for the 15 schools listed. 

Module 4: Created repo to analyze school data using Anaconda, Jupyter Notebook and Pandas. 

##Challenge
Recreate the district and school summary DataFrames.
  How is the district summary affected?
  The dataframes show the corrected summary data, removing the number of math and reading scores that were null. Originally, there wer 39,170 names and 15 schools, of which 1,635 records had to be updated. 
  
  How is the school summary affected?
  The 9th graders tests scores were updated with a NaN value to reflect the changes made to their previous grades. 
  
Recalculate the high- and low-performing schools.
  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
  Replacing the 9th graders scores affected the percentages for Thomas High School, putting them in the lower ranking school bin. 
  
Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
  How does replacing the ninth-grade scores affect the following?
    Math and Reading Scores by Grade
    Average math and reading scores were lowered for Thomas High School, causing them to have the lowest percentage of passing students in both math and reading. 
    Scores by School Spending
    Was affected by this change, reducing the number of bins from 4 to 3. 
    Scores by School Size
    Scores by School Type
    The school size and types remain the same. 
   
   Chart
    School	Student Count 	Avg Math Score 	Avg Reading Score 	% Passing Math 	% Passing Reading 	Overall Passing Rate 	Per Student Budget
Wilson High School 	2283	83.274201	83.989488	93.867718	96.539641	95.203679	[578.0]
Holden High School 	427	83.803279	83.814988	92.505855	96.252927	94.379391	[581.0]
Cabrera High School 	1858	83.061895	83.97578	94.133477	97.039828	95.586652	[582.0]
Wright High School 	1800	83.682222	83.955	93.333333	96.611111	94.972222	[583.0]
Shelton High School 	1761	83.359455	83.725724	93.867121	95.854628	94.860875	[600.0]
Pena High School 	962	83.839917	84.044699	94.594595	95.945946	95.27027	[609.0]
Griffin High School 	1468	83.351499	83.816757	93.392371	97.138965	95.265668	[625.0]
Bailey High School 	4976	77.048432	81.033963	66.680064	81.93328	74.306672	[628.0]
Rodriguez High School 	3999	76.842711	80.744686	66.366592	80.220055	73.293323	[637.0]
Thomas High School 	1635	83.350937	83.896082	66.911315	69.663609	68.287462	[638.0]
Figueroa High School 	2949	76.711767	81.15802	65.988471	80.739234	73.363852	[639.0]
Ford High School 	2739	77.102592	80.746258	68.309602	79.299014	73.804308	[644.0]
Johnson High School 	4761	77.072464	80.966394	66.057551	81.222432	73.639992	[650.0]
Hernandez High School 	4635	77.289752	80.934412	66.752967	80.862999	73.807983	[652.0]
Huang High School 	2917	76.629414	81.182722	65.683922	81.316421	73.500171	[655.0]

    
