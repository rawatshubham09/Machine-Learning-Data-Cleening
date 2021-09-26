# Titanic Data cleaning
### I had Done some Analysing of this Data set and some observation has made:
<li>Majority of Women and Children Survived</li>
<li>Majority of servived male are of Class 1st</li>
<li>Class 3rd ave age is 24 so no. of young people died in that misshap are young and in there early 20-30's</li>

### First I Handled Missing Data and fill Null values in Age group. 
### For it I take Average Age from each Class and fill it to there respected place 
### Then I Convert String Varibles like (sex-> male,female) into Intiger
### This is achive by using Label Encoder fron SkLearn Lib and Dummy varible creater using Panda
### Age and Ticket Fare converted into 4 sub group and place value according to it.
## After Submitting the Pridicting and Uploding values of Test data, I had scored 75.54% Accruacy.
