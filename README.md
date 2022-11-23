# Random

We merged the datasets based on Employee Code. First we merged the “DIM_Employee” file and “Collect_activity_userid” and named the sheet Merge1. We used an inner join and matched on the columns EmpID in the “DIM_Employee” file and the EMPLOYEE_CODE in the “Collect_activity_userid” file.

![Screenshot (477)](https://user-images.githubusercontent.com/58046234/203458286-e7a0f7ef-0778-4c1f-9569-2695cc107f10.png)
![Screenshot (478)](https://user-images.githubusercontent.com/58046234/203458301-90e0ddb4-d799-4a24-8035-3a81d7f01db8.png)

Then we merged the Merge1 sheet with the “Cas_active_users” file and named the sheet Merge2. We used an inner join and matched on the columns EmpID in the “Merge1” file and the EMPLOYEE_CODE in the “Cas_active_users” file.

![Screenshot (480)](https://user-images.githubusercontent.com/58046234/203458337-f5a0c48a-d808-44ea-8e26-ffe056ca18f2.png)
![Screenshot (482)](https://user-images.githubusercontent.com/58046234/203458342-1ff8496e-93f0-43fc-9596-f7c9ab779437.png)

Then we merged the Merge2 sheet with the “LMS” file and named the sheet Merge3 which happened to be our final overall dataset. We used an inner join and matched on the columns EmpID in the “Merge2” file and the EMPLOYEE_CODE in the “LMS” file.

![Screenshot (483)](https://user-images.githubusercontent.com/58046234/203458359-b0efecaf-4b22-4914-bfd4-5c696288e8d7.png)
![Screenshot (484)](https://user-images.githubusercontent.com/58046234/203458363-c8d37f23-4f1e-42a9-bfbb-69b995a4a455.png)

Refer to the Activity4.xlsx file to see each individual merge. 
