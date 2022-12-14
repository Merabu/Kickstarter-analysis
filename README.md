# Kickstarting with Excel
## Overview of Project
   The project is aimed at organizing and analyzing data to understand the data and discover helpful conclusions.
The purpose of this analysis is to help understand the correlation/relationship between the type of campaign, launch date, and funding goals.
How different campaigns performed to their lunch date and funding goals. How does the lunch date or funding goal affect the performance of the campaign
### Purpose
  Using the kickster dataset, Louise wanted to know the how different campaigns performed during different time of the year and their funding goals. How did the variables affect the sucess and failure of the compaign.
## Analysis and Challenges

### Analysis of Outcomes Based on Lunch date
![Threater Outcomes by lunch date](https://user-images.githubusercontent.com/115379848/206587524-6d981f68-fa01-4aff-909b-ca8c9c7816e9.JPG)
To achieve the analysis shown in the screenshot above, I processed the raw data given to me in the "Kickstarter" dataset to achieve Louise's needs, how different      campaigns faired in relation to their lunch date for parent category theater. I used different formulas to create more colmns to help with the analysis: I added        filtered parent category, date created for date launched =DATE(1970,1,1)+(J2/86400), extracted the year and month with the formula =YEAR(O2) and =TEXT(R2*28,     "mmm") respectfully

### Analysis of Outcomes Based on Goals.
![Outcome based on goals](https://user-images.githubusercontent.com/115379848/206587070-0fb21957-419c-4d63-8fc5-a96f8e1d12c1.JPG)
In this analysis, I was provided with the goal ranges to group the data and expected to help Louise visualize campaign outcomes based on funding goals. Utilized the formula =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"successful",Kickstarter!$U:$U, "plays" for single goals and =COUNTIFS(Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D, "<=4999",Kickstarter!$F:$F,"successful",Kickstarter!$U:$U, "plays" for goal range.
I also created percentages for success, canceled, and failure.
In the range goal of 45000 to 49999, the percentage of failure is equal to the percentage of success is 0% as opposed to 100% failure.
### Challenges and Difficulties Encountered
Limited information for example in the outcome rang 45000 to 49999 100% failure percentage in the outcome. I would love to know more about what transpired during that goal range.
Creating more columns which were not straight forward to achieve.
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
In this analysis, we have our highest successful outcome in June after a gradual increase from January to May. There Is a dramatic decrease in the successful outcome in the month after June to December. There was a slight increase in the successful outcome in October.
From January to September there is a consistently failed outcome with a slight increase in October.
Bar chart for countries vs  total outcome or line graph showing
- What can you conclude about the Outcomes based on Goals?
As shown in the attached screen shoot, the analysis shows that as the goal range was increasing, the percentage of success kept decreasing until the goal hit 25000 to 29999, where we see a sharp increase in the percentage successful. There was a dramatic decrease in the percentage success in the range of 45000 to 4999 showing no success in this range.In the range goal of 45000 to 49999, the percentage of failure is equal to the percentage of success is 0% as opposed to 100% failure.
As the goal range increased from 1000 to 29999 the percentage failed consistently increases. It's important to note that there is 100% failure in the goal range of 45000 to 49999 and with a dramatic increase of 62% of failure in the goal outcome range of 40000 to 34999.
- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
Create a line graph showing how different regions/countries performed during different time of the year.
