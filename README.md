# Project - training_program_hireability

## Introduction


This machine learning project determines whether a student in a training program is hireable. 
The data set contains various features like Gender, Experience, Education, Number of months since job search etc.. 
By combining and analyzing features, and testing dependencies of variables on each other, and using a logistic regression model, the hireability is determined.

When a student will be hired: This is something that is work in progress.

### Collecting data


This training program, has details of students 
- whether a student is active/not active in the training program
- what is their primary track
- which is their batch id
- how many days they have been in the training program
- have they been hired/not hired yet
- what is the duration of their job search
- what is their biggest challenge in the job search
- how many years experience do they have
- what is their current US work auth status
- how many interviews have they attended
- how many jobs have they applied for
- what are their genders
- what are their races

All of this information was available in a single excel sheet. I did not extract any further data for this project.

### Exploratory data analysis


In this step, I verified the relationships between different variables. Since they were mostly categorical variables, I used contingency tables to determine relationships between variables. Those variables that had a close implication on whether a student was placed or not, were eventually selected to feed into the logistic regression model.


### Choosing the model


Since we were given supervised data - and since we are determining whether someone got placed/not placed, this is a classification problem. We use a Logistic Regression Model. After training the model, we got an accuracy of 62.7%. This is on the lower end, but since the data is not a factual data, I did not try to improve this further, by tweaking the inputs. 


### Future improvements


Here, I will use different models like Decision Tree/Random forest and see if the accuracy improves, and then choose the model with highest accuracy. Also, in order to understand when a student will get hired, I will use the Survival Analysis machine learning model.








