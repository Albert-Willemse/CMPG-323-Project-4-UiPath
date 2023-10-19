# CMPG-323-Project-4-38205742
_Use UiPath to enter data from an existing dataset into an existing web application to conduct user testing. This project will introduce me to various testing techniques and teach me how to use RPA._


## Table of Contents
- [Project Goal](#project-goal)
- [Usage](#usage)
- [Main Workflow Steps](#main-workflow-steps)
- [Reference List](#reference-list)

## Project Goal

_The project's primary goal is to automate tasks related to data management and functional testing within a specific application, optimizing efficiency and reducing errors. This includes automating data retrieval, manipulation, and various operations on customer, order, product, and order details data while ensuring secure login and logout processes._

## Usage

1. Go to https://cmpg323-ecopowerlogistics.azurewebsites.net/
2. Register 
3. In UIPath Orchestrator add your email and password in Assests
   
   ![image](https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/14ca77ee-51b7-48f6-b8b3-4ebc91850653)

4. Update the "Get Credentials" in the Login workflow

   ![image](https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/4a8e3904-af10-45ef-a70e-c2197239c4b4)

   
5. Run the project
6. Let the robot run
7. Check the results in the Output folder
   

# Main Workflow Steps


| Step                           | Description                                   |
|--------------------------------|-----------------------------------------------|
| **1. ReadData**                    | Read data from Excel into DataTables         |
| **2. Login**                       | Log into the website                          |
| **3.1. CreateCustomers**             | Test the functionality to create customers    |
| **3.2. CreateOrders**                | Test the functionality to create orders       |
| **3.3. CreateProducts**              | Test the functionality to create products     |
| **3.4. CreateOrderDetails**          | Test the functionality to create order details|
| **4.1. Read_Edit_DeleteOrderDetails**| Test the functionality to read, edit, and delete order details|
| **4.2. Read_Edit_DeleteProducts**    | Test the functionality to read, edit, and delete products|
| **4.3. Read_Edit_DeleteOrders**      | Test the functionality to read, edit, and delete orders|
| **4.4. Read_Edit_DeleteCustomers**   | Test the functionality to read, edit, and delete customers|
| **5. Logout**                      | Log out of the website                        |
| **6. WriteData**                   | Write the Test Results to the Excel sheet     |


<img src="https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/c6922525-abd6-4a53-ad90-4dfdae64eb35" width="85%">


# Reference List
