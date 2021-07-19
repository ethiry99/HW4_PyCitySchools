# HW4_PyCitySchools
Homework 4

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
    There was a reduction in the scores by school spending. Particularly in the % Passing Math, % Passing Reading and % Overall categories.  The top table are the original results.  The bottom table shows the results after the changes. 
    
    ![]()

    ![](https://github.com/ethiry99/HW4_PyCitySchools/blob/main/Resources/images/Altered%20score%20by%20budget%20bins.png)

- #### Scores by school size

- #### Scores by school type

  
### Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Deliverable 3 Requirements
Structure, Organization, and Formatting (7 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt).
Each section has a heading and subheading (3 pt).
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (18 points)
The written analysis has the following:

Overview of the school district analysis:

The purpose of this analysis is well defined (3 pt).
Results:

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
