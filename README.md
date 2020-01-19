# Data Visualization 

### Introduction 

A personal project during freshman year to learn and use Python's Pandas, Matplotlib, and Seaborn Data Visualization libraries with various real-world datasets. For the source code to generate these visuals, please see the respective Jupyter Notebooks. 

___ 

**Parental Education and and Marriage Rates:**

Is there a relationship between the level of education and the percentage of couples being married when their child is born? 
[As newspaper articles have led us to expect](https://www.theatlantic.com/family/archive/2019/01/education-divide-marriage/579688/), 
the approximately 3.8 million births in the United States in 2018 clearly indicate that higher parental education is generally, though not perfectly, correlated with a higher rate of marriage. 

Due to space limitations, I use abbreviations for each level of education:

+ N/A: Less than 8th grade
+ HS-: HS Dropout
+ HS: HS Diploma  
+ AA-: Some College
+ AA: Associates Degree
+ BA: Bachelor's Degrees
+ MA: Master’s degree
+ Ph.D.: Doctorate or Professional Degree

**Dataset Compiled By:** National Center for Health Statistics

**Source**: https://www.kaggle.com/des137/us-births-2018

![percent_married](https://user-images.githubusercontent.com/58995473/72205845-c5ae8680-3487-11ea-98bb-d49710ad9bf3.png)

The clear exception to the general relationship between education level and rate of marriage is that when a mother's education decreases from some high school to less than 8th grade, her chance of being married when having a child actually increases. Could it be possible that this is because most mothers with less than an 8th grade education were born outside of the US? 

![mothers_born_abroad](https://user-images.githubusercontent.com/58995473/72669092-d61caf00-39fb-11ea-8cc2-5a99d5d18fdd.png)

This is indeed the case. Since mothers with less than an 8th grade are immigrants, they may have different attitudes toward marriage. 

___

**Weather and Traffic Accidents:**

During what type of weather are traffic accidents most common in the United States? We might typically assume most traffic accidents occur during bad weather, but this is not the case; an analysis of the approximately 2.5 million traffic accidents from 2016-2019 indicate that traffic accidents are actually most common during clear weather. 

**Dataset compiled by:** _Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019._

**Source:** https://www.kaggle.com/sobhanmoosavi/us-accidents

![weather_conditions](https://user-images.githubusercontent.com/58995473/72167510-87ec2800-33cb-11ea-81bb-52d64bf5f678.png)

___

**Top Ten Sources of Remittances from 2000-2016:**

From which countries do people send the most remittances? We see that the United States has for the entire period been the largest source of remittances, though its share has been steadily declining. Over time, remittances from other countries such as China and Saudi Arabia now make up a larger share. 

**Dataset compiled by:** _World Bank_ 

**Source:** https://www.kaggle.com/theworldbank/worldwide-economic-remittances

![remittances](https://user-images.githubusercontent.com/58995473/72208033-8fc8cc80-349e-11ea-82bc-c0d8f76de928.png)

___

**Developer Salaries, Languages, and Age in 2019:** 

What is the average age of a developer in 2019? Are we correct in assuming that programming is a young person's business? When we plot a histogram, we see that indeed there are far more young developers and that programmers in middle age and beyond are relatively rare. 

**Credit:** _Corey Schafer's YouTube series on matplotlib, Stack Overflow 2019 annual developer survey_

![developer_salaries](https://user-images.githubusercontent.com/58995473/71764091-84e0cb80-2ee3-11ea-9b55-86009127d5f8.png)

Considering that most programmers are relatively young, what is the relationship between developer salaries, programming languages, and age in 2019? According to the Stack Overflow developer survey, salaries generally grow with age, while Python programmers earn slightly more than the average developer. 

**Credit:** _Corey Schafer's YouTube series on matplotlib, Stack Overflow 2019 annual developer survey_

![developer_salaries](https://user-images.githubusercontent.com/58995473/71763714-519c3d80-2edf-11ea-9e1a-a0afadfe1fa9.png)
