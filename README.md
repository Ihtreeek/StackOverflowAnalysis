
# StackOverflow Survey Analysis

StackOverflow is a question and answer website for programmers.The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers.I am just curious to analyze and study patterns of programmers especially in data science domain.



## Data Description
I downloaded the data from the website:\
https://insights.stackoverflow.com/survey/ \
The dataset contains responses to an annual survey conducted by StackOverflow. There are three files in the dataset. \
.README.txt - Information about the dataset\
. survey_results_schema.csv - The list of questions, and shortcodes for each question \
.survey_results_public.csv - The full list of responses to the questions
## Data Cleaning
I ignored the rows where the age is higher than 100 years or lower than 10 years as invalid survey responses.\
Gender column  allowed for picking multiple options ,so i removed values containing more than one option to simplify the analysis.\
Converted YearsCode,Age1stCode,YearsCodePro columns into numeric columns.

## Questions to answer
1)How does programming experiennce change the way they feel after not getting the question which they already did?\
2)How frequently does person learn new language or framework?\
3)How do people learn more about company?\
4)How do you important is formal education,such as university degree in computer science to your career?\
5)How is the ratio of different genders in data science ?
## Hypothesis
1)I guess with experience people feel annoyed if they couldn't solve the problem.\
2)As programming industry quickly changes,i guess less experienced people learn more frameworks.\
3)Through career sites.\
4)In data science,people come from different backgrounds so i think formal career is less important.
5)I guess most working people are men and minority are women.

## Screenshots

![App Screenshot](https://drive.google.com/file/d/111hNrqOrnEdcvudjUn7ZbbAGxu3zollG/view?usp=share_link)


## Summary
I have drawn many inferences from the survey. Here's a summary of a few of them:

1)Based on the survey respondents' demographics, we can infer that the survey is somewhat representative of the overall programming community. However, it has fewer responses from programmers in non-English-speaking countries and women & non-binary genders.

2)The programming community is not as diverse as it can be. Although things are improving, we should make more efforts to support & encourage underrepresented communities, whether in terms of age, country, race, gender, or otherwise.

3)Woman in data science are 1% higher percentage compared to the women in all tech professionals.It shows there should be initiatives to be taken to promote diversity.

4)There is high ratio of people who think formal education is important in data science career compared to people in other careers.

5)Most people learn more about companies through the third party sites like glassdoor which isn't surprising.

6)Around 30% of people update the knowledge for every few months and then other 30 % of people learn for once a year.Its not surprising because to stay relevant field they need to update their knowledge regularly.

7)There wasnt any significance relationship with the experience and the feeling after not solving a problem which is solved earlier.So we can say that it mostly depends on the attitude more than experience.

8)Most common roles include developer.Data Scientist and Data analyst contribute around 4 percent .