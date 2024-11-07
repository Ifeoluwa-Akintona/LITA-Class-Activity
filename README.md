# LITA-Class Activity

# HR DATA PROJECT
This Power BI project uses the HR data to analyze information about employees such as their Job satisfaction, the attrition rate, monthly income of each employee, their marital status, gender amongst many other. The report is designed to help stakeholders make data-driven decisions based on historical employee data.

## Project Overview

### Objectives
- Provide insights into total number of employee by department, educational field, and gender.
- Identify the attrition rate across all departments.
- Provide insights into the monthly income of employee by gender, marital status and department. 
  
### Key Metrics
- Attrition Count: Total number of employees that have left the organization.
- Attrition Rate: The total percentage of employees that have left the organization.
- Employee Count: Total number of employees in the company.

### Dataset

#### Columns
| Column Name |	Description                                           |
|-----------------------|---------------------------------------------|
| Attrition             |	Availability of the employee in the company |
| Business Travel       | Travel status of each employee              |
| CF Age-Band	          | Age range of each employee                  |
| CF-Attrition Label    |	Current and Previous Employee               |
| Department            |	Department of each employee                 |
| Education Field       |	Area of specialization of each employee     |
| Emp-no                |	Unique identification of each employee      |
| Gender                | Sex of each employee                        |
| Job Role              |	Roles of each employee                      |
| Marital Status	      | Marital status of each employee             |
| Education             |	Degree of each employee                     | 
| Job Satisfaction Rate	| Level of satisfaction for each employee     |


### Key Measures

- Attrition Rate = SUM('HR Data'[Attrition Count])/ SUM('HR Data'[Employee Count])
    

### Data Transformations
- Job satisfaction rate: A conditional column was used to get each employee's satisfaction rate. 
- Attrition Sort: Created a conditional column to sort the attrition and this was used to get the attrition count.
- Age Sort: Added a conditional column in Power BI to get the age sort and this was used to sort the age band

### Visualizations

1. Total Attrition By Department
   
   Type: Donut Chart
   
   Purpose: Shows the total attrition of employees by department
   
   <img width="323" alt="TAD" src="https://github.com/user-attachments/assets/1c56806c-23ca-441d-8db7-aa5491540ca9">

  

   
   
2. Attrition Rate By Educational Field
   
   Type: Column Chart
   
   Purpose: Shows the attrition rate for each educational field.

   Fields:

   X-axis: Educational Field

   Y-axis: Attrition Rate
   
   <img width="330" alt="ARE" src="https://github.com/user-attachments/assets/1794940d-71f3-4e88-89bc-b0fc35f5a088">


   

3. Total Attrition By Gender
   
   Type: Pie Chart
   
   Purpose: Shows the total number of attrition by gender.
   
   <img width="323" alt="TAG" src="https://github.com/user-attachments/assets/fb23f0b6-870b-4652-85d2-dfffe736b09d">

   
   

4. Total Current Employee By Gender
   
   Type: Column Chart
   
   Purpose: Shows the total number of current employees by gender.

   Fields:
   
   X-axis: CF-Age Band
   
   Y-axis: CF-Current Employee
   
   <img width="437" alt="TCE" src="https://github.com/user-attachments/assets/4cdaf582-0f84-475c-8ef5-f41fadb24354">

   


5. Job Role/Satisfaction By Their Attrition Count.
   
   Type: Table
   
   Purpose: Shows the job satisfaction rate and job role of each employee that have left the organization.

   <img width="447" alt="Job Role" src="https://github.com/user-attachments/assets/ad4a07f9-c880-4e38-9121-5759209f2608">


   
6. Total Employee By Their Marital Status and Gender
   
   Type: Table.
   
   Purpose: Shows the total number of employees by their marital status and gender. 
   
   <img width="437" alt="TEM" src="https://github.com/user-attachments/assets/eea7165d-6840-4bb8-944e-08dc49c93829">

   

7. Educational Field Satisfaction By Their Attrition Count.
   
   Type: Table. 
   
   Purpose: Shows the educational field satisfaction of employees that have left the organization.
   
   <img width="455" alt="EFS" src="https://github.com/user-attachments/assets/02193fb1-aa93-4c56-ba77-ea76550cb14b">



8. Attrition By Age Group and Gender. 
   
   i) Title: Under 25

      Type: Donut Chart
   
      Purpose: Shows the total number of employees under the age of 25 by gender that have left the organization. 

      <img width="293" alt="Under 25" src="https://github.com/user-attachments/assets/baceefcd-d45a-4701-9594-6a72cd93942e">


   ii) Title: Age 25-34

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 25-34 by gender that have left the organization.

      <img width="290" alt="Age 25-34" src="https://github.com/user-attachments/assets/919f15e2-2a69-48c6-840c-d6a73ed29b4a">

   

   iii) Title: Age 35-44

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 35-44 by gender that have left the organization.
   
   <img width="287" alt="Age 35-44" src="https://github.com/user-attachments/assets/88bc3dfd-2078-4403-a77e-ced3e0b50316">




   iv) Title: Age 45-54

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 45-54 by gender that have left the organization.

      <img width="434" alt="Age 45-54" src="https://github.com/user-attachments/assets/eeb7e636-db68-45b2-a874-8ca6b134a7a2">



   v) Title: Over 55

       Type: Donut Chart
   
       Purpose: Shows the total number of employees over the age of 55 by gender that have left the organization.

     <img width="445" alt="Over 55" src="https://github.com/user-attachments/assets/3e720d33-c1cf-461b-abe6-2e0383dfa2b4">



9. Attrition By Age Group and Marital Status. 
   
   i) Title: Under 25

      Type: Donut Chart
   
      Purpose: Shows the total number of employees under the age of 25 by marital status that have left the organization. 

  <img width="288" alt="M Under 25" src="https://github.com/user-attachments/assets/33c1e599-66b3-4197-9498-e0fb6f79f606">



   ii) Title: Age 25-34

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 25-34 by marital status that have left the organization.

  <img width="285" alt="M Age 25-34" src="https://github.com/user-attachments/assets/e4f31dbb-ad65-4265-93ce-83daed6af5e4">

   

   iii) Title: Age 35-44

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 35-44 by marital status that have left the organization.

  <img width="293" alt="M age 35-44" src="https://github.com/user-attachments/assets/51480127-6003-4a35-8aa6-b102e0592c59">



   iv) Title: Age 45-54

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 45-54 by marital status that have left the organization.

  <img width="452" alt="M Age 45-54" src="https://github.com/user-attachments/assets/be443801-02e6-47b2-865d-d29ec028d228">



   v) Title: Over 55

       Type: Donut Chart
   
       Purpose: Shows the total number of employees over the age of 55 by marital status that have left the organization.

  <img width="440" alt="M over 55" src="https://github.com/user-attachments/assets/489e5291-3adf-4dd1-ac62-b681453feca5">


10. Total Monthly Income By Job Role

     Type: Bar Chart
   
   Purpose: Shows the total monthly income of employees by their job role.

   Fields:
   
   X-axis: Monthly Income
   
   Y-axis: Job Role

   <img width="314" alt="TMIJB" src="https://github.com/user-attachments/assets/0d4d4579-a32a-4cf3-9d93-5fa7b6ac7b12">


   
11. Total Monthly Income By Department

     Type: Column Chart
   
     Purpose: Shows the total monthly income of employees by their department.

     Fields:
   
     X-axis: Department
   
     Y-axis: Monthly Income

    <img width="315" alt="TMID" src="https://github.com/user-attachments/assets/55a4cc77-56b2-4f34-aaeb-aacb036eac98">


12. Total Monthly Income By Education

     Type: Bar Chart
   
     Purpose: Shows the total monthly income of employees by their education.

     Fields:
   
     X-axis: Monthly Income
   
     Y-axis: Education

    <img width="323" alt="TMIE" src="https://github.com/user-attachments/assets/e053ae98-c377-4bbf-8ab4-23938b96c327">


13. Total Monthly Income By Marital Status

     Type: Pie Chart
   
     Purpose: Shows the total monthly income of employees by their marital status.

   
    <img width="314" alt="TMIM" src="https://github.com/user-attachments/assets/273f7555-a180-4d9c-a40f-536be3b07e4a">



14. Total Monthly Income By Gender

    Type: Donut Chart
   
    Purpose: Shows the total monthly income of employees by their gender.

    <img width="316" alt="TMIG" src="https://github.com/user-attachments/assets/8a755969-7279-466f-a234-56714d2e652d">


15. Total Monthly Income By CF-Age Band

     Type: Column Chart
   
     Purpose: Shows the total monthly income of employees by their age band.

     Fields:
   
     X-axis: CF-Age Band
   
     Y-axis: Monthly Income.

    <img width="323" alt="TMIC" src="https://github.com/user-attachments/assets/067c625e-cb43-4304-a080-6b116a13ebd4">


    
### Overall Visualizations. 
1) The Overview Page;
   
   <img width="575" alt="Overview" src="https://github.com/user-attachments/assets/097a5627-ecf6-4760-a43b-f781f87e39f6">


2) Employee Rating;
   
   <img width="572" alt="Employee Rating" src="https://github.com/user-attachments/assets/e12c5c80-478d-423c-8027-2eecf21baae0">


3) Gender Attrition Page
   
   <img width="572" alt="Gender Attrition Data" src="https://github.com/user-attachments/assets/b773b0b0-fd07-4a6f-b94d-1e27e11bceb2">


4) Marital Status Attrition Page
   
   <img width="574" alt="Marital Status AD" src="https://github.com/user-attachments/assets/80cf3c5f-b989-4547-a548-d20099052046">


6) Employee Compensation
   
   <img width="572" alt="Employee compensation" src="https://github.com/user-attachments/assets/57a0dc7b-5a7e-4399-8492-e02906953741">




### Insights and Conclusion
- Attrition Rate:
  i) The analysis provides insights showing that in every department, the 'R&D' had the highest number of employees that have left the organization with a total percentage of 65.37% while the'HR' department had the lowest number of employees that have left the organization with a total percentage of 4.29%.
  
  ii) The analysis provides insights showing that in every education field, 'Human Resources' had the highest number of employees that have left the organization with a total percentage of 26% while 'Other' education field had the lowest number of employees that have left the organization with a total percentage of 13%.

  iii) The analysis provides insights showing that according to gender, the 'Male Gender' had the highest number of employees that have left the organization with a total percentage of 60% while the'Female Gender' department had the lowest number of employees that have left the organization with a total percentage of 40%.

  iv) The analysis provides insights showing that according to marital status, the 'Married people' had the highest number of employees that have left the organization with a total percentage of 45.78% while the 'Single People' had the lowest number of employees that have left the organization with a total percentage of 22.24%.

- Employee Compensation:
  i) The analysis identifies that according to job roles, the 'Sales Executive' earn the highest in the organization with a total income of $2,257,315 while the 'Human Resources' earn the lowest with a total income of $220,259

  ii) The analysis identifies that according to department, 'R&D' earns the highest in the organization with a total income of $6,036,284 while the 'Human Resources' earn the lowest with a total income of $419,234

  iii) The analysis identifies that according to education, 'Bachelor's Degree Holder' earns the highest in the organization with a total income of $3,727,875 (This is due to the larger percentage of the company's population being Bachelor Degree Holders, they cost the company more) while the 'Doctoral Degree Holders'  earn the lowest with a total income of $397,327 (They are few doctorate degree holder in the company). 

  iv) The analysis identifies that according to marital status, 'Married People' earn the highest in the organization with a total percentage of 47.83% while the 'Divorced People' earn the lowest with a total percentage of 23.21%

  v) The analysis identifies that according to gender, the 'Male gender' earns the highest in the organization with a total percentage of 58.87% while the 'Female gender' earn the lowest with a total percentage of 41.13%

  vi) The analysis identifies that according to age band, people within the age band of '35-44' earn the highest in the organization with a total income of $3,427,792 while people 'under 25' earn the lowest with a total income of $257,901

### Recommendations
- The 'R&D' department has the highest attrition rate, the company can improve compensation and benefits, provide incentives, create a town hall meeting quartely to understand their employee and what they can do to improve welfare for employees in this department. This would help reduce the attrition rate in that department.

- In regards to the male gender leaving the company more, feedback sections should be provided where employees can talk about their grievances and how their job satisfaction rating can be improved, this in turn can reduce the attrition rate in the company. 
