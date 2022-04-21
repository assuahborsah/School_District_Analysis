# School_District_Analysis
Anaconda Prompt (pythonData) 
Overview of the school district analysis
There is an academic dishonesty in the reading and math grades of the ninth graders at Thomas High School. The grades appear to have been tampered with and the School Board have been tasked to go through the student_complete.csv file to find out the extent of the academic dishonesty.  They must uphold state-testing standards. 
The School Board have been asked to repeat the school district analysis by replacing the math and reading scores with NaNs while keeping the rest of the school data intact. The are required to compare the original analysis with the 9th grade scores and to generate a report of how the changes affect the overall analysis.
Resources
1.	Python version 3.7.6
2.	Jupyter Notebook 6.14
3.	Anaconda 3
4.	PythonData Environment
Results
•	How is the district summary affected?
cleaning_student_names file
[image](https://user-images.githubusercontent.com/96086671/164510114-7d2d992f-186f-4644-b9f5-b30be11fa0e4.png)

PyCitySchools_Challenge file
[image](https://user-images.githubusercontent.com/96086671/164510234-57f490f6-c14e-4162-894d-9346b4c02c79.png)

Comparing the two files above, the results for average math score, average reading score, %passing math, %passing reading, and %overall passing remained relatively unchanged. With approximations, the numbers will still round to the same whole numbers if they are round up to the nearest whole numbers.
[image](https://user-images.githubusercontent.com/96086671/164510482-740438bd-c312-48d8-86a0-643311719157.png)
[image](https://user-images.githubusercontent.com/96086671/164510652-395ca84f-69ed-4e0e-9730-ea8e0e01049c.png)
[image](https://user-images.githubusercontent.com/96086671/164510798-0e12554e-6783-40df-b219-6fe8b97a7bcd.png)

The difference noted is that in the original analysis, the original student_count was 39170 and after cleaning up the clean_student_data, the count dropped to 38709 showing a 461 difference in the ninth_grade_student_count. 
•	How is the school summary affected?
When comparing with the original data (cleaning_student_names file), Thomas High School overall passing was 90.9%, this dropped to 65% in the PyCitySchools_Challenge file making a difference of 25.9%. The passing math in the original data was 93% compared to 66.9% making a difference of 26.1% and passing reading in the original data was 97.3% as compared to 69.6% with a difference of 27.7%.
•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Comparing the original data (cleaning_student_names file) with the updated data (PyCitySchools_Challenge file). Thomas High School ranked 2nd in the district of 15 schools. After, replacing the ninth graders' math and reading score Thomas High School is no longer in the second position.
[image](https://user-images.githubusercontent.com/96086671/164511088-f23b42f7-0ee2-4b56-afec-66e207173edb.png)

How does replacing the ninth-grade scores affect the following:
•	Math and reading scores by grade
In the original data of Thomas High School 9th grade, the reading and math score of Rebecca Tanner and Joseph Anthony's grades were removed and replaced with null values (NaN's). 
[image](https://user-images.githubusercontent.com/96086671/164511212-d3c203da-5663-468e-af7d-76fa5e504082.png)

•	Scores by school spending
Thomas High School falls under the spending range (per student) of $630-$644
[image](https://user-images.githubusercontent.com/96086671/164511321-38c7e466-e5fd-49de-b3ad-c5855721acf3.png)

•	Scores by school size
Thomas High School’s scores falls under medium sized school category (1000-2000).
[image](https://user-images.githubusercontent.com/96086671/164511433-117b148c-24f7-4f76-a1a0-165f9b9720de.png)

•	Scores by school type
Thomas High School scores falls under the charter school type.
[image](https://user-images.githubusercontent.com/96086671/164511527-bb75ded7-d3fb-4fd8-a5bf-a024f502c2d7.png)

Summary
1.	The overall passing % for Thomas High School decreased dramatically from 90.9% to 65%.
2.	Thomas High School overall ranking dropped from second place.
3.	Math and reading scores for Thomas High School Updated School_District_Analysis  9th Grade have been replaced with Nan’s.

