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
![image](https://user-images.githubusercontent.com/92477493/140934459-2fc74cf8-918e-4db6-bfb3-d8d02ecde27a.png)

![image](https://user-images.githubusercontent.com/92477493/140933968-4fe8a2b7-a616-4a29-969a-c65f4fc04b38.png)

Create Co relation matrix – Heat Map 
![image](https://user-images.githubusercontent.com/92477493/140934392-10720d7a-3ae2-489a-9d5f-24213ee98fd7.png)

![image](https://user-images.githubusercontent.com/92477493/140934064-06582cc7-6c34-4999-a63b-f3d9b8bc93e8.png)

Compare Age and Attrition 
![image](https://user-images.githubusercontent.com/92477493/140934353-a55e6494-29a5-490d-95ea-65727034de33.png)

![image](https://user-images.githubusercontent.com/92477493/140934125-03516097-5ffa-4391-8d43-ab0772748ba3.png)

Count Plot - 'JobRole’ and  'Attrition’

sns.countplot(x = 'JobRole', hue = 'Attrition', data = df
![image](https://user-images.githubusercontent.com/92477493/140934537-494af245-8a8c-4237-bc62-77846952b55e.png)


Count Plot – Marital Status and Attrition
![image](https://user-images.githubusercontent.com/92477493/140934587-9c03c9bc-ba82-4447-b660-9c33cf1985cd.png)

![image](https://user-images.githubusercontent.com/92477493/140934635-1f75cdb1-f8a2-4e86-91ee-4c81e8c2eff5.png)

KDE Plot
plt.figure(figsize=(12,7))
sns.kdeplot(left_df['DistanceFromHome'], label = 'Employees who left', shade = True, color = 'r')
sns.kdeplot(stayed_df['DistanceFromHome'], label = 'Employees who Stayed', shade = True, color = 'b')plt.xlabel('Distance From Home')

![image](https://user-images.githubusercontent.com/92477493/140934685-17a20a47-d68f-4518-8173-f79ea50b5d0d.png)

![image](https://user-images.githubusercontent.com/92477493/140934728-4e548d6d-57c0-4540-a967-e2bcece17de3.png)

![image](https://user-images.githubusercontent.com/92477493/140934794-43eb5a3a-4291-4108-a257-9fbecf1fdf0f.png)

Boxplot -Gender vs. Monthly Income
![image](https://user-images.githubusercontent.com/92477493/140934830-e0e9be2e-5989-4897-be46-d8591097b79b.png)


Boxplot –Monthly income Job Role
![image](https://user-images.githubusercontent.com/92477493/140934864-ab07d2d5-d6de-4dab-849b-415a3e20ff0b.png)
