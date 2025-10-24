
Data source

This is a dataset on the HR records of a company. The dataset includes information on the ages,salaries,genders,employee_ids, hire dates,departments and job titles of the workers.

Cleaning steps taken

Firstly,i got the file from my downloads into PowerBI and clicked to transform the data.
In the transform tab in the power query editor, I chose the use the first row as headers. Next I checked column quality and column distribution options in the view tab and unchecked the show whitespace option.
For the job title column,I right clicked the header and chose capitalize each word. Then I replaced 'Nan' with a dash.
For the deprtment column,I right clicked the header and chose capitalize each word. Then I replaced the 'It' and 'Hr' with 'IT' and 'HR' respectively.
For the HireDate column,I changed the data type to date.
For the employee_id column,I chose uppercase under the transform tab.
For the Gender column, I chose capitalize each word.
For the Salary column,I changed the data type to whole numbers.I then chose the absolute value option under the transform tab.I found the median which was 69.5 and then replaced the null values with the median,rounding it down.
For the Age column,I chose the absolute value function under the transform tab.

Challenges I faced in cleaning the Dataset

Firstly,  I had a challenge with the age colum since some of the values were negative and even after using the the absolute value option ,some ages were too high or too low
Secondly,I had a challenge dealing with blank spaces in the hiredate column and the employee_id column since it was obvious that they followed patterns which could be used to fill the spaces.
Also,with the salary column after applying the absolute value option some values appeared too small.
