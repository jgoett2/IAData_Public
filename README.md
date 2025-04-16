# Midterm Exam Data Analysis
This analysis considers a fictional data set of midterm exam scores.  There are two sets of data, one that looks at exam stats at the network level (includes 18 high schools), and another that gives student exam scores at 3 of those high schools.

By comparing the 3 school's exam results to the network data, these recommendations can be made:  
- On **Curriculum**: 
    - The majority of students in **AP English Language**, **English III**, **AP US History**, and **Physics** score above the network averages on the respective exams.  These curriculums may be particularly strong, and examining them for key qualities may be beneficial.  
- On **Teacher Preparation**:  
    - Within the same course, there can be a wide variation in student performance by teacher.  Some teachers may be highly experienced, while others may arrive midyear and are still becoming familiar with the curriculum.  Learning from the highly experienced teachers and supporting newer teachers may help.  
- On **Student Preparation**:
    - After accounting the factors listed above, student preparation still has a large affect on outcome.  When taking the same class, students in the honors track generally score better than students in the general education track. 

## Student Results
After loading score results from the school and network levels, we compare student results by subject test. 
- Students in **AP English Language**, **English III**, **AP US History**, and **Physics** score **above** the network average in the respective subjects.  These curriculums and teachers may be particularly strong, and may merit follow up.

<img src="Images/SubjectAve.jpg">

# The Effect of a Teacher
We also see a large variation in scores by teacher in Physics, Honors US History, AP Chemistry, and AP US History.  Teacher experience and support may play a factor in determining these exam scores.

<img src="Images/TeacherBreakdown.jpg">

## Consider Student Preparation
Finally, we consider the roll of student preparation for a course.  In classes that all students take, those who otherwise take the an "Honors Track" courseload do better than those in the "General Track". 

<img src="Images/StudentPreparation.jpg">

## Conclusion
In summary, we see that student performance in classes can be dependent on **curriculum**, **teacher assignment**, and **student preparation**.  Student performance could potentially be improved by addressing each issue appropriately.