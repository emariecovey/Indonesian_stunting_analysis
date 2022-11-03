# Indonesian_stunting_analysis

**This project was completed before I started my github account, which is why there are few commits and less organized code. 

### Overview of project
The purpose of this project was to evaluate Indonesian mothers' knowledge of stunting, and provide recommendations to prevent stunting. A dataset with survey data from mothers of children 2 and younger was used. 

### Evaluating stunting knowledge
First, a composite stunting knowledge variable was created. It was composed of the following survey questions: 

- Have you ever been informed about stunting/shorty?
- What is stunting/shorty?
- What causes stunting/shorty?
- What will stunting/shorty cause in a child under 2?
- What does it take to avoid stunting/shorty in a child under 2?

Each question had a correct answer, and answers were coded 0 and 1 for incorrect and correct answers. The five items were then summed to give a final knowledge score variable out of five. Factor analysis was used to ensure that the five variables were cohesive enough to compile. 

### Providing recommendations
Adjusted and unadjusted logistic regression models were created to determine other survey variables' association with the composite stunting knowledge variable. The adjusted regression models accounted for the following variables: mother’s age, education level, employment status, family wealth index. The variables tested in the models included:
- When/who/where they got information about stunting/shorty
- Integrated health post utilization 
- Media consumption
- Demographics 

### Results
Less than 5% of respondents knew what stunting was, and half of respondents thought that it was inherited, rather than caused by malnutrition. There was generally very little knowlege of this health condition, and the average composite stunting variable score was 1. 

Generally, increased knowledge and education have been associated with improved health and knowledge of health. Counterintuitively, the results showed that increased wealth led to less stunting knowledge. This could be due to imperfect survey data, or some other factor. Perhaps weathier indonesians have less need for info on stunting, since they have enough money for food and don't experience as much stunting in their children?

Survey results also indicated that many (91%) indonesian mothers had been to an Integrated Health Post, which is a small place where they can recieve health care. Community health workers could be trained to work with mothers and educate them on stunting and how to prevent it. Survey participants also reported that health data would be effectivly spread though TV and and posters. 