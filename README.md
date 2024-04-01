
# HR Analytics Dashboard

### Dashboard Link : https://app.powerbi.com/links/a7Spg7PfKT?ctid=3f66430c-920e-49dc-9dd6-8223afea3b81&pbi_source=linkShare

## Problem Statement

The document discusses employee attrition, its causes, and ways for companies to reduce it. It defines attrition as the reduction in employees due to reasons like resignation, retirement, or death. Some of the major reasons employees leave jobs are lack of career growth opportunities, poor work environment, low pay, and work-life imbalance. The document suggests companies provide flexible work, good benefits, training, and a supportive culture to decrease voluntary attrition it.

## Chart used 
(a) Card :
          It was used to display values like 'Count of Emp','Attrition','Attrition Rate','Avg Age','Avg Salary','Avg Years'. 

  (b) Slicer :
        It was used for the department column i.e.'HR','R&D','Sales'.

  (c) Text Box :
        Used for the Title head of the Dashboard.

  (d) Tree Map :
        It was used for showing the total no of job roles which shows attrition.
  
  (e) Donut Chart :
        Used to display the 'Attrition by Education'.
  
  (f) Stacked Column Chart :
        It was used to show the attrition by 'Age Categories'.

  (g) Matrix :
        Used to display the impact of attrition by the 'Job Role' & 'Job Satisfaction factor'.
  
  (h) Area Map :
        Used to display 2 KPI's,which includes the 'Attrition by Salary' & 'Attrition by Experience'.
  
  (i) Stacked Bar Chart :
        This visual was used to show 'Attrition on Job Roles'.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : All data types of column were validated in power query editor.
- Step 4 : All duplicate values were removed from the data.
- Step 5 : All the columns were reordered and arranged firmly.
- Step 6 : After editing all the data ,I have clicked 'Close & Apply' and loaded data into report view.
- Step 7 : In the report view, under the view tab, theme was selected. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Human Resources", "Research & Development" & "Sales".
- Step 9 : Six card visuals were added to the canvas,representing 'Count of Employee','Attrition','Attrition Rate','Avg Age','Avg Salary','Avg Years'representing attrition.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average & sum calculation.
- Step 10 :Some of the values were summarized as sum of whole column including 'Age','Daily Rate','Distance from Home','Education','Emp Count','Emp_No','Emp Satisfaction'.
- Step 12 : Apart from this column related to 'Job','Month'&'percent'basis were also summarised.
- Step 13 : Calculated column was created in which, employees were grouped into various attrition rate.

for creating new column following DAX expression was written;
       
        Attrition Rate = 
        
        SUM('HR_Analytics'[Attrition Count] / 'HR_Analytics'[Employee Count])
        
Snap of new calculated field ,

![Snap_1](https://github.com/Chandan-Sav/Dashboard---HR/assets/121309914/5f41fa69-4566-4e31-8ec1-dbbe9f8be323)

 - Step 14 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://github.com/Chandan-Sav/Dashboard---HR/assets/121309914/d72b96b8-17a3-4f5f-80c5-5facdb9632fd)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/Chandan-Sav/Dashboard---HR/assets/121309914/ded5e4df-a14b-4686-aa75-6580be6c48d9)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/Chandan-Sav/Dashboard---HR/assets/121309914/69454b5d-6c2c-414a-a938-d07f57a007f5)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

 ### [4] Some other insights
 
 ### Job Roles
 
 1.1) 60 employees by Laboratory Technician.
 
 1.2) 55 employees by Sales executive.
 
 1.3) 44 employees by Research Scientist.

 1.3) 33 employees by Sales Representative. 
         thus, maximum employees attrition by Job Role is from Laboratory Technician.
 
 ### Age Group
 
 2.1)  43 employees belong to '18-25' age group.
 
 2.2)  111 employees belong to '26-35' age group.
 
 2.3)  41 employees belong to '36-45' age group.
 
 2.4)  26 employees belong to '46-55' age group.

 2.5)  8 employees belong to '55+' age group.
 
         thus, maximum employees attrition belong to '26-35' age group.
         
### Education

 3.1)  38.4% employees belong to 'Life Science'  group.
 
 3.2)  24.9% employees belong to 'Medical' group.
 
 3.3)  14.8% employees belong to 'Marketing' group.
 
 3.4)  14.0% employees belong to 'Technical Degree' group.

 3.5)  4.8% employees belong to 'Other' group.
 
         thus, maximum employees attrition belong to 'Life Science' group.
         

### Salary

 4.1)  2894697 belong to 'upto 5k'  group.
 
 4.2)  2344418 belong to '5k - 10k' group.
 
 4.3)  2291085 belong to '10k - 15k' group.
 
 4.4)  1697418 belong to '15k +' group.
 
         thus, maximum employees attrition belong to '5k - 10k' group.

        thus, more customers have travel type 'Business'.
