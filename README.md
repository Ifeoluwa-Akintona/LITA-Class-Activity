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

       <img width="290" alt="Age 25-34" src="https://github.com/user-attachments/assets/7fa51d65-3087-456b-9c5f-027fcf722219">
   

   iii) Title: Age 35-44

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 35-44 by gender that have left the organization.

       <img width="287" alt="Age 35-44" src="https://github.com/user-attachments/assets/a898c5ee-89f9-4997-98f8-4c0156cead6d">


   iv) Title: Age 45-54

       Type: Donut Chart
   
       Purpose: Shows the total number of employees within the age of 45-54 by gender that have left the organization.

       <img width="434" alt="Age 45-54" src="https://github.com/user-attachments/assets/2f65689a-fdc1-48ff-8719-c85da62bef0e">


   v) Title: Over 55

       Type: Donut Chart
   
       Purpose: Shows the total number of employees over the age of 55 by gender that have left the organization.

       <img width="445" alt="Over 55" src="https://github.com/user-attachments/assets/ede65faa-063d-44e7-b646-2e81db51522d">


9. Attrition By Age Group and Marital Status. 
   
   i) Title: Under 25

      Type: Donut Chart
   
      Purpose: Shows the total number of employees under the age of 25 by marital status that have left the organization. 

      <img width="288" alt="M Under 25" src="https://github.com/user-attachments/assets/e0e1f1a6-15d7-4130-a158-86ec2b023ab7">



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


10) 



### Overall Visualizations. 
1) The Landing Page;
   
   <img width="620" alt="Landing Page" src="https://github.com/user-attachments/assets/3dff9268-ad93-4a39-b18a-c56f0f44ec8d">


2) The Sales Overview;
   
   <img width="614" alt="Sales Overview" src="https://github.com/user-attachments/assets/ad6124a7-11b9-457d-8ed8-49d7b241da73">


3) The Product Performance (Filtered to top 3)
   
   <img width="614" alt="Product Performance" src="https://github.com/user-attachments/assets/ec69ba69-0229-4ace-942a-77127fa0742c">


4) The Product Performance (Filtered to bottom 3)
   
   <img width="617" alt="PP" src="https://github.com/user-attachments/assets/a1704296-6349-4e94-b15e-9213c838c2dc">


5) The Regional Performance (Filtered to year 2023)
   
   <img width="617" alt="2023 RP" src="https://github.com/user-attachments/assets/d6e67ced-6a8d-47b3-842c-6b8cfb6ef232">


6) The Regional Performance (Filtered to year 2024)
   
   <img width="616" alt="2024 RP" src="https://github.com/user-attachments/assets/c741d8a9-c4de-4f0c-89d7-72d9d1a066ee">




### Insights and Conclusion
- Product Performance: The analysis provides insights showing that the product 'Shoes' generated the highest revenue with a percentage total of 29.2% while the product 'Socks' generated the lowest revenue with a percentage total of 8.6%.

- Sales Overview: The analysis identifies the high-performing months and products

- Regional Performance: Pinpoints regions with the highest sales potential. The analysis shows that in regards to quantity of product sold, the 'South Region' sold the highest number of products. In regards to revenue, in the year 2023; the 'South Region' generated the highest revenue with a percentage total of 43.5% while the 'West Region' generated the lowest revenue with a percentage total of 8%.
  
  In the year 2024, the 'South Region' still came on top and generated the highest revenue with a percentage total of 45% while the 'East Region' generated the lowest revenue with a percentage total of 9.2%.
