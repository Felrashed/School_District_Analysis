# **PyCity Schools: Auditing School District Performance for Academic Dishonesty** 

![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/exam_matrix_cheating.jpg) 

## **Resources**
- clean_students_complete.csv
- Python
- Anaconda / Condas
- Pandas
- NumPy
- Jupyter Notebook
- Excel

## **School District Performance Analysis: Overview and Purpose**
### **Initial Tasking**
The PyCity School Board has contracted our firm, PyCity Forensic Data Detectives LLC to conduct an analysis of schools in the district. The analysis is intended to yield results meant to inform budgetary decisions and strategic decisions at the board level based on metrics like budget, test scores for math and english, school type, etc.
### **Extended Analysis**
While conducting the analysis and presenting the results, the board raised issue with some of the results. Specifically, they believe that there is evidence of academic dishonesty at Thomas High School in the district. Specifically, they beliefve the grades for reading and math have been altered at the 9th grade level. They have asked us to nullify the data associated with the 9th grade students and re-run the district analysis to determine if the scores are credible or if they have been altered. 

## **Results**

**How is the District Summary Affected?**
- The summary data at the district-level was changed, but by negligible amounts.
    - Average Math Score: - 0.1%
    - Average Reading Score: No Change
    - % Passing Math: - 0.2%
    - % Passing Reading: - 0.3%
    - % Overall Passing: - 0.1%

**Initial District Summary**             | 
:-----------------------------------------------------------------------------------------:|
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/District_summary_og.PNG)  |

**Clean District Summary**             | 
:-----------------------------------------------------------------------------------------:|
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/District_summary_new.PNG)  |

**How is the School Summary Affected?**
- The School Summary data was unaffected by the changes made to THS, since the changes made were isolated to THS 9th grade students only. 

**How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to its peers?**
- Replacing the 9th grade students' scores did not affect Thomas High School's relative perfomance. THS was ranked 2nd overall in the initial analaysis and in the secondary. 

**How does replacing the ninth-grade scores affect the following?**
- Math and reading scores by grade?
    - Only the averages for the 9th graders at THS were impacted by the changes. They had no affect on the averages of other schools and grades. 
- Scores by school spending?
    - There were no changes in school spending averages. The changes made only affected scoring of THS grade 9 students. 
- Scores by school size?
    - There were no changes to the average score peformance by school size. 
- Scores by school type?
    - There were no changes to the average score performance by school type

**Examples Visualizing Similarities and Lack of Changes**

**Initial Scores by Spending Bin**             |  **Updated Scores by Spending Bin**
:-----------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------:
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/Spending_OG.PNG)  |  ![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/Spending_New.PNG)

**Initial Scores by School Type**             |  **Updated Scores by School Type**
:-----------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------:
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/Scores_by_type_OG.PNG)  |  ![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/Scores_by_type_new.PNG)

## **Summary of Findings**
The differences were small and lacking in significance. From a forensic analysis standpoint, it does not seem reasonable to assert any academic dishonesty because changes in the overall school metrics were within a reasonably tight margin from the average previously as well as having no significant impact on the district level standings as well. 

The differences for THS before and after were as follows: 
- **Average Math Score:** 83.418349 **-->** 83.350937	
- **Average Reading Score:** 83.848930 **-->** 83.896082	
- **% Passing Math:** 93.272171 **-->** 93.185690	
- **% Passing Reading:** 97.308869 **-->** 97.018739	
- **% Passing Overall:** 90.948012 **-->** 90.630324



**Initial Thomas High School Performance Metrics**             | 
:-----------------------------------------------------------------------------------------:|
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/THS_Metrics_OG.PNG)  |

**New Thomas High School Performance Metrics**             | 
:-----------------------------------------------------------------------------------------:|
![](https://github.com/Felrashed/School_District_Analysis/blob/main/Readme_files/THS_Metrics_new.PNG)  |