# CMPG-323-Project-4-UiPath
_Use UiPath to enter data from an existing dataset into an existing web application to conduct user testing. This project will introduce me to various testing techniques and teach me how to use RPA._


## Table of Contents
- [Project Goal](#project-goal)
- [Usage](#usage)
- [Main Workflow Steps](#main-workflow-steps)
- [Reference List](#reference-list)

## Project Goal

_The project's primary goal is to automate tasks related to data management and functional testing within a specific application, optimizing efficiency and reducing errors. This includes automating data retrieval, manipulation, and various operations on customer, order, product, and order details data while ensuring secure login and logout processes._

## Usage

1. Go to https://cmpg323-ecopowerlogistics.azurewebsites.net/ - (Site offline)
2. Register 
3. In UIPath Orchestrator add your email and password in Assests
   
   ![image](https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/14ca77ee-51b7-48f6-b8b3-4ebc91850653)

4. Update the "Get Credentials" in the Login workflow

   ![image](https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/4a8e3904-af10-45ef-a70e-c2197239c4b4)

   
5. Run the project
6. Let the robot run
7. Check the results in the Output folder
   

## Main Workflow Steps


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


<img src="https://github.com/Albert-Willemse/CMPG-323-Project-4-38205742/assets/112475881/c6922525-abd6-4a53-ad90-4dfdae64eb35" width="95%">


## Reference List

1. Avinash. 2019. _Headers are not displaying._ https://forum.uipath.com/t/headers-are-not-displaying/156519/1 Date of access: 2023/10/15.
2. chanda, D. 2022. _0 runtime available._ https://forum.uipath.com/t/0-runtime-available/475270 Date of access: 2023/10/17.
3. Cruz, M. 2022. _Uipath - how to publish process to orchestrator_ (tutorial) https://www.youtube.com/watch?v=TT3cgpWutD4 Date of access: 2023/10/18.
4. Hall, C. 2019. _Conditional if/then statements._ https://forum.uipath.com/t/conditional-if-then-statements/166477 Date of access: 2023/10/17.
5. Jensen, A. 2020. _How to use uipath and github together_ https://www.youtube.com/watch?v=OSanRxqtvSE Date of access: 2023/10/17.
6. Jensen, A. 2021. _Uipath try catch - full tutorial from start to finish_ https://www.youtube.com/watch?v=k4r64I7fjzI Date of access: 2023/10/15.
7. Jensen, A. 2023. _Uipath beginners course 2023 - how to get started_ https://www.youtube.com/watch?v=A8cLOfItmv8 Date of access: 2023/10/14.
8. jpreziuso. 2023. _Referencing project folders in config file._ https://forum.uipath.com/t/referencing-project-folders-in-config-file/525048 Date of access: 2023/10/15.
9. Lather, S. 2022. _Understanding and use case of global variables and constants._ https://forum.uipath.com/t/understanding-and-use-case-of-global-variables-and-constants/482631 Date of access: 2023/10/15.
10. Perez, A. 2021. _Expression [k (tab)]._ https://forum.uipath.com/t/expression-k-tab/337483 Date of access: 2023/10/15.
11. Rajput, S. 2022. _How to add specific columns from one data table to another._ https://forum.uipath.com/t/how-to-add-specific-columns-from-one-data-table-to-another/481644 Date of access: 2023/10/15.
12. Tila, D. 2021. _Uipath how to do store passwords_ https://www.youtube.com/watch?v=3lI-Ubgd0Ow&t=22s Date of access: 2023/10/14.
13. Uipath. 2017. _Uipath project organization._ https://www.uipath.com/learning/video-tutorials/project-organization Date of access: 2023/10/16.
14. Uipath. 2023a. _Workflow activities - copy file._ https://docs.uipath.com/activities/other/latest/workflow/copy-file Date of access: 2023/10/15.
15. Uipath. 2023b. _Studio user guide - project organization._ https://docs.uipath.com/studio/standalone/2023.10/user-guide/project-organization Date of access: 2023/10/16.


