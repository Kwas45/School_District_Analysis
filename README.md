# School District Analysis

## SCHOOL DISTRICT ANALYSIS OVERVIEW

The purpose of this project is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. This is due to evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. The initial data analysis was performed on a city school district standardized test for performance trends to inform discussions and decisons at the school and district level. This involved analyzing data on student funding and student standardized test scores to aggregate data and showcase trends in school performance. The tasks assinged are as follows:

* >*Effect on district summary.*
* >*Effect on school summary.*
* >*Effect on Thomas High School’s performance relative to the other schools when the ninth graders’ math and reading scores are replaced.*
* >*Effect on replacing the ninth-grade scores on the following; math and reading scores by grade, scores by school spending, scores by school size, scores by school type.*
               
                
### RESOURCES
Data Source [school_complete.csv](https://github.com/Kwas45/School_District_Analysis/tree/main/Resources)
            [students_complete.csv](https://github.com/Kwas45/School_District_Analysis/tree/main/Resources)
 

### SCHOOL DISTRICT ANALYSIS RESULTS

**1. District Summary**

There wasn't much change between the district summary on the Initial Anaylsis(IA) versus the summary on the alteration of Thomas High School(THS). As seen below, there were no changes to the total schools, total students, and total budget. The average math score, % passing math, % passing reading and % overall passing had decreases of 0.1, 0.2, 0.1, and 0.3 respectively. 

*IA District Summary*

![pycity](https://user-images.githubusercontent.com/102786356/167341870-cd2874ce-43e0-445f-a8d6-4d3910845c69.png)

*THS District Summary*

![ths nan](https://user-images.githubusercontent.com/102786356/167341904-ac3db7a7-504d-48ad-be09-7c3139b847ad.png)




**2. School Summary**

In the school summary the data for other schools experienced no change. Thomas High School didn't have much changes to their budget, student count, and average reading and math score. There was about a 25% decrease in % passing math, % passing reading, and % overall passing. 

*IA School Summary*

![ia school sum](https://user-images.githubusercontent.com/102786356/167344780-d7f8082b-be08-496f-94f3-908225a608bd.png)

*THS Summary*

![ths school sum](https://user-images.githubusercontent.com/102786356/167344836-cee3313b-7951-4e43-9195-e98b82225a16.png)


 

**3. Thomas High School Performance**

Although Thomas High School experienced a decrease in % overal passing, it wasn't the lowest percentage relative to other schools. With 65.08% it was at the 50th percentile. 

*THS Summary*

![ths school sum](https://user-images.githubusercontent.com/102786356/167344836-cee3313b-7951-4e43-9195-e98b82225a16.png)


**4. Effects Of Alteration**

Replacing the ninth-grade scores affected mostly Thomas High School ninth-graders. As seen below there were no changes to the math and reading scores of the other grades. Also, the overall passing for scores by school spending, school size, and school type had slight decrement due to the NaN values assigned to the scores of Thomas High School ninth-graders. 

*IA Math and Reading Scores*

![ia math grade](https://user-images.githubusercontent.com/102786356/167349146-407a9859-62bd-4e8a-a440-78d531bb83a5.png)
![ia reading gra](https://user-images.githubusercontent.com/102786356/167349114-47eb3695-aae5-4729-809f-10177c288577.png)

*THS Math and Reading Scores*

![ths grade](https://user-images.githubusercontent.com/102786356/167349298-2b591430-c4fa-4974-b1f3-c59aba2dcb2b.png)
![ths reading gra](https://user-images.githubusercontent.com/102786356/167349309-63816b7e-f81d-4b5b-b168-5a5cbb78fcff.png)


### SCHOOL DISTRICT ANALYSIS SUMMARY
Out of all the categories, average math score, average reading score, % passing math, % passing reading, and % overall passing all realized change due to the ninth-graders scores being replaced by Nans. The Nans were used to replace the grades and not student profiles hence total student count remained the same. 
