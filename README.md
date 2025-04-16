# Midterm Exam Data Analysis
This analysis uses a fictional data set of midterm exam scores to test different analyses of a data set.  It simulates the midterm exam scores given at three high schools in a larger network of schools.  The data set includes the following:
- Student exam scores for midterm exams in different subjects, given at at three high schools.  It includes the name of the high school and student's teacher.
- Average scores and standard deviations for the larger network of schools, of which these students are a subset.  

By comparing the school's exam results to the network data, these recommendations can be made:  
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