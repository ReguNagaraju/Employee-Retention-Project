# Employee-Retention-Project

Hiring and retaining employees are extremely complex tasks that require capital, time and skills.

“Small business owners spend 40% of their working hours on tasks that do not generate any income such as hiring”.

“Companies spend 15%-20% of the employee's salary to recruit a new candidate”.


“An average company loses anywhere between 1% and 2.5% of their total revenue on the time it takes to bring a new hire up to speed”.

Hiring a new employee costs an average of $7645 (0-500 corporation).

It takes 52 days on average to fill a position.

You work as a data scientist at a multinational corporation. 

The HR team collected extensive data on their employees and approached you to develop a model that could predict which employees are more likely to quit. 

Steps 
Import Libraries and Data Set 
Basic Data Checks 
Info ()
Describe()

Replace the 'Attrition' and 'overtime' column with integers
Check  any missing data
Create the histogram to check data 



Create the histogram to check data 
![image](https://user-images.githubusercontent.com/92477493/140933968-4fe8a2b7-a616-4a29-969a-c65f4fc04b38.png)
![image](https://user-images.githubusercontent.com/92477493/140935857-07fdd341-2447-440f-852a-c1e14212129a.png)

Drop 'EmployeeCount' , 'Standardhours' and 'Over18' since they do not change from one employee to the other.

How many employees left the company.

Percentage of employees who left the company 

Number of employees who did not leave the company (stayed)

Percentage of employees who did not leave the company (stayed) 

Count the number of employees who stayed and left 

Create Co relation matrix – Heat Map 
![image](https://user-images.githubusercontent.com/92477493/140936445-7b7815dd-6f27-4ba4-a60e-845d4f23786c.png)

Compare Age and Attrition 
![image](https://user-images.githubusercontent.com/92477493/140936942-0e15a389-0777-4dd0-9cef-5f38b6e406a0.png)

Count Plot - 'JobRole’ and  'Attrition’

sns.countplot(x = 'JobRole', hue = 'Attrition', data = df
![image](https://user-images.githubusercontent.com/92477493/140937170-fa520177-0098-4e61-a2fc-7d1a59e85817.png)

Count Plot – Marital Status and Attrition
![image](https://user-images.githubusercontent.com/92477493/140937612-ed4210aa-0662-4e61-8b43-5abd76a9c0dd.png)

KDE Plot
plt.figure(figsize=(12,7))
sns.kdeplot(left_df['DistanceFromHome'], label = 'Employees who left', shade = True, color = 'r')
sns.kdeplot(stayed_df['DistanceFromHome'], label = 'Employees who Stayed', shade = True, color = 'b')plt.xlabel('Distance From Home')
![image](https://user-images.githubusercontent.com/92477493/140945517-272794d1-10a8-4543-be4a-5cb8a64cc675.png)


![image](https://user-images.githubusercontent.com/92477493/140934728-4e548d6d-57c0-4540-a967-e2bcece17de3.png)

![image](https://user-images.githubusercontent.com/92477493/140934794-43eb5a3a-4291-4108-a257-9fbecf1fdf0f.png)

Boxplot -Gender vs. Monthly Income
![image](https://user-images.githubusercontent.com/92477493/140945788-22d3c56e-5130-484a-9907-0a53ce6c6276.png)


Boxplot –Monthly income Job Role
![image](https://user-images.githubusercontent.com/92477493/140946027-1343ba00-6a2e-40d8-8b67-0b5c38db5503.png)


![image](https://user-images.githubusercontent.com/92477493/220523357-0b9c9a94-c516-44a6-a7ca-a8cfd80b7fac.png)
