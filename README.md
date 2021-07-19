# HW4_PyCitySchools

### Overview
The purpose of this analysis is to change reading and math scores for ninth graders at Thomas High School to NaN (Not a Number) due to the appearance that some scores were altered.  After that change the previous analysis will be repeated to determine how the results were affected. 

### Results

- #### How is the district summary affected?
    The district summary only had minor changes.  This is expected as the scores that changes are only one grade at one school.  Since there are 15 schools each with four grades throwing out such a small amount doesn't have a significant impact

- #### How is the school summary affected?
    The effect can be seen to a much greater degree in the results of the School Summary Analysis.  In the original analysis; the % Passing Math, % Passing Reading and % Overall passing were all over 90%.
    
    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/original_school_summary%20labeled.png)
    
    In the adjusted analysis those categories drop into the 60's.
     ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/adjusted_school_summary%20labeled.png)
     
    I'm using the unformated results to be able to see the small changes in the math and reading scores.

- #### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    In the origininal analysis, Thomas High School ranked second in % Overall Passing.  
    

    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Original%20top%20schools%20labeled.png)                 
    
    After dropping the ninth grade reading and writing scores they ranked 8th.
    
    [Rank after dropping Thomas High School ninth grade scores](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Altered%20Top%20Schools%20labeled.png)
    
- #### Math and reading scores by grade
    Once the math and reading scores for Thomas High School were removed they no longer had a score to display for the ninth grade.  Their overall score for ninth grade in math and reading are now NaN.
    

- #### Scores by school spending
    There was a reduction in the scores by school spending in the $630-644 category, the category that Thomas High School is a part of. Particularly in the % Passing Math, % Passing Reading and % Overall score.  The top table are the original results.  The bottom table shows the results after the changes. 
    
    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/original%20score%20by%20budget%20bins.png)

    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Altered%20score%20by%20budget%20bins.png)
    
    There are also variations in the other budget catecories.  This is casused by diferences in how the mean scores were calculated.  In the original analysis they are calculated as averages of the school summary averages.  In the second analysis, the averages are calculated using the complete data, they are calculated on a student by student basis.  I felt this was more accurate that using the averages of school averages. Using the student level data the results are an acurate weight average.  This is true of the scores by school size and the scores by school type as well.    

- #### Scores by school size
    A decrease in % Passing Math, % Passing Reading and % Overall score can also be seen in the scores by school size table.  Thomas High School is a medium sized school.  The decrease is about 5% in each category   
  ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Original%20schoolsize.png)
  
  ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Altered%20schoolsize.png)
  
- #### Scores by school type
    The categories % Passing Math, % Passing Reading and % Overall score also display a decrease for charter school, the type that Thomas High School is. The reduction is about 3 to 4%.                   
    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/original%20score%20by%20type.png)
    
    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/altered%20score%20by%20type.png)

  
### Summary
- #### Changes to School Summary table
    There was a large reduction in the Thomas High School results for % Passing Math, % Passing Reading and % Overall score.  This can expected because 1 of the 4 grades did not receive a score for reading and math.  There no ninth graders received a passing score in math or reading.

- #### Changes to Summary by School 
    For the opposite reason, the Summary of all schools had a small impact to the results.  The ninth graders at Thomas High School represent a much smaller percentage of the 37,000 + students in the analysis so there NaN for testing scores had a minimal impact.
    
- #### Changes to School Rank
    Without approximately 25% of the students receiving passing grades, the overall rank for Thomas High School dropped from 2nd to 8th.  
 
 - #### Changes to School Type
    The Charter Schools in this analysis perform very well.  There was a relatively small drop in testing performance for Charter Schools in the School Type results. This is largely because ninth graders at Thomas High School represent a small number of of all Charter School students among the 37,000+ students represented in the data. 
    
