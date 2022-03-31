# Practice Assessment Exam &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                   [50 Marks]

### 1. Create Schema on your system database using [1_build_schema.sql](1_build_schema.sql) and then do the following:
- Select the names of all the products in the store.
- Select the names and the prices of all the products in the store.
- Select the name of the products with a price less than or equal to $200.
- Select all the products with a price between $60 and $120.
- Select the name and price in cents (i.e., the price must be multiplied by 100).
- Compute the average price of all the products.
- Compute the average price of all products with manufacturer code equal to 2.
- Compute the number of products with a price larger than or equal to $180.
- Select the name and price of all products with a price larger than or equal to $180, and sort first by price (in descending order), and then by name (in ascending order).
- Select all the data from the products, including all the data for each product's manufacturer.
- Select the product name, price, and manufacturer name of all the products.
- Select the average price of each manufacturer's products, showing only the manufacturer's code.
- Select the average price of each manufacturer's products, showing the manufacturer's name.
- Select the names of manufacturer whose products have an average price larger than or equal to $150.
- Select the name and price of the cheapest product.
- Select the name of each manufacturer along with the name and price of its most expensive product.
- Add a new product: Loudspeakers, $70, manufacturer 2.
- Update the name of product 8 to "Laser Printer".
- Apply a 10% discount to all products.
- Apply a 10% discount to all products with a price larger than or equal to $120.

### 2. Create Schema on your system database using [2_build_schema.sql](2_build_schema.sql) and then do the following:
- Select the last name of all employees.
- Select the last name of all employees, without duplicates.
- Select all the data of employees whose last name is "Smith".
- Select all the data of employees whose last name is "Smith" or "Doe".
- Select all the data of employees that work in department 14.
- Select all the data of employees that work in department 37 or department 77.
- Select all the data of employees whose last name begins with an "S".
- Select the sum of all the departments' budgets.
- Select the number of employees in each department (you only need to show the department code and the number of employees).
- Select all the data of employees, including each employee's department's data.
- Select the name and last name of each employee, along with the name and budget of the employee's department.
- Select the name and last name of employees working for departments with a budget greater than $60,000.
- Select the departments with a budget larger than the average budget of all the departments.
- Select the names of departments with more than two employees.
- Select the name and last name of employees working for departments with second lowest budget.
- Add a new department called "Quality Assurance", with a budget of $40,000 and departmental code 11. And Add an employee called "Mary Moore" in that department, with SSN 847-21-9811.
- Reduce the budget of all departments by 10%.
- Reassign all employees from the Research department (code 77) to the IT department (code 14).
- Delete from the table all employees in the IT department (code 14).
- Delete from the table all employees who work in departments with a budget greater than or equal to $60,000.
- Delete from the table all employees.

### 3. Create Schema on your system database using [3_build_schema.sql](3_build_schema.sql) and then do the following:
- Select all warehouses.
- Select all boxes with a value larger than $150.
- Select all distinct contents in all the boxes.
- Select the average value of all the boxes.
- Select the warehouse code and the average value of the boxes in each warehouse.
- Same as previous exercise, but select only those warehouses where the average value of the boxes is greater than 150.
- Select the code of each box, along with the name of the city the box is located in.
- Select the warehouse codes, along with the number of boxes in each warehouse. 
    * Optionally, take into account that some warehouses are empty (i.e., the box count should show up as zero, instead of omitting the warehouse from the result).
- Select the codes of all warehouses that are saturated (a warehouse is saturated if the number of boxes in it is larger than the warehouse's capacity).
- Select the codes of all the boxes located in Chicago.
- Create a new warehouse in New York with a capacity for 3 boxes.
- Create a new box, with code "H5RT", containing "Papers" with a value of $200, and located in warehouse 2.
- Reduce the value of all boxes by 15%.
- Remove all boxes with a value lower than $100.
- Remove all boxes from saturated warehouses.
- Add Index for column "Warehouse" in table "boxes"
    * **NOTE: index should NOT be used on small tables in practice**
- Print all the existing indexes
    * **NOTE: index should NOT be used on small tables in practice**
- Remove (drop) the index you added just
    * **NOTE: index should NOT be used on small tables in practice**


### 4. Create Schema on your system database using [4_build_schema.sql](4_build_schema.sql) and then do the following:
- Select the title of all movies.
- Show all the distinct ratings in the database.
-  Show all unrated movies.
- Select all movie theaters that are not currently showing a movie.
- Select all data from all movie theaters 
    * and, additionally, the data from the movie that is being shown in the theater (if one is being shown).
- Select all data from all movies and, if that movie is being shown in a theater, show the data from the theater.
- Show the titles of movies not currently being shown in any theaters.
- Add the unrated movie "One, Two, Three".
- Set the rating of all unrated movies to "G".
- Remove movie theaters projecting movies rated "NC-17".


### 5. Create Schema on your system database using [5_build_schema.sql](5_build_schema.sql) and then do the following:
- Select the name of all the pieces. 
-  Select all the providers' data. 
- Obtain the average price of each piece (show only the piece code and the average price).
-  Obtain the names of all providers who supply piece 1.
- Select the name of pieces provided by provider with code "HAL".
- For each piece, find the most expensive offering of that piece and include the piece name, provider name, and price 
    * **Note that there could be two providers who supply the same piece at the most expensive price**
- Add an entry to the database to indicate that "Skellington Supplies" (code "TNBC") will provide sprockets (code "1") for 7 cents each.
- Increase all prices by one cent.
- Update the database to reflect that "Susan Calvin Corp." (code "RBT") will not supply bolts (code 4).
- Update the database to reflect that "Susan Calvin Corp." (code "RBT") will not supply any pieces 
    * **the provider should still remain in the database**

### 6. Create Schema on your system database using [6_build_schema.sql](6_build_schema.sql) and then do the following:
- List all the scientists' names, their projects' names, 
    * and the hours worked by that scientist on each project, 
    * in alphabetical order of project name, then scientist name.
- Select the project names which are not assigned yet

### 7. Create Schema on your system database referring to [7_schema_figure.png](7_schema_figure.png) and then do the following:
- Insert the data using [7_insert_data.sql](7_insert_data.sql)
- Who receieved a 1.5kg package?
    * The result is "Al Gore's Head".
- What is the total weight of all the packages that he sent?

### 8. Create Schema on your system database referring to [8_schema_figure.png](8_schema_figure.png) and then do the following:
- Insert the data using [8_insert_data.sql](8_insert_data.sql)
- Obtain the names of all physicians that have performed a medical procedure they have never been certified to perform.
- Same as the previous query, but include the following information in the results: Physician name, name of procedure, date when the procedure was carried out, name of the patient the procedure was carried out on.
- Obtain the names of all physicians that have performed a medical procedure that they are certified to perform, but such that the procedure was done at a date (Undergoes.Date) after the physician's certification expired (Trained_In.CertificationExpires).
- Same as the previous query, but include the following information in the results: Physician name, name of procedure, date when the procedure was carried out, name of the patient the procedure was carried out on, and date when the certification expired.
- Obtain the information for appointments where a patient met with a physician other than his/her primary care physician. Show the following information: Patient name, physician name, nurse name (if any), start and end time of appointment, examination room, and the name of the patient's primary care physician.
- The Patient field in Undergoes is redundant, since we can obtain it from the Stay table. There are no constraints in force to prevent inconsistencies between these two tables. More specifically, the Undergoes table may include a row where the patient ID does not match the one we would obtain from the Stay table through the Undergoes.Stay foreign key. Select all rows from Undergoes that exhibit this inconsistency.
- Obtain the names of all the nurses who have ever been on call for room 123.
- The hospital has several examination rooms where appointments take place. Obtain the number of appointments that have taken place in each examination room.
- Obtain the names of all patients (also include, for each patient, the name of the patient's primary care physician), such that all the following are true:
    * The patient has been prescribed some medication by his/her primary care physician.
    * The patient has undergone a procedure with a cost larger that $5,000
    * The patient has had at least two appointment where the nurse who prepped the appointment was a registered nurse.
    * The patient's primary care physician is not the head of any department.


### 9. Create a Database and import [cran_logs_2015-01-01.csv](cran_logs_2015-01-01.csv) file ***(you can take a refernce to import data from csv file from [this webpage](https://dev.mysql.com/doc/workbench/en/wb-admin-export-import-table.html)  )*** and then do the following:
- give the total number of recordings in this table
- the number of packages listed in this table?
- How many times the package "Rcpp" was downloaded?
- How many recordings are from China ("CN")?
- Give the package name and how many times they're downloaded. Order by the 2nd column descently.
- Give the package ranking (based on how many times it was downloaded) during 9AM to 11AM
- How many recordings are from China ("CN") or Japan("JP") or Singapore ("SG")?
- Print the countries whose downloaded are more than the downloads from China ("CN")
- Print the average length of the package name of all the UNIQUE packages
- Get the package whose downloading count ranks 2nd (print package name and it's download count).
- Print the name of the package whose download count is bigger than 1000.
- The field "r_os" is the operating system of the users.
    * 	Here we would like to know what main system we have (ignore version number), the relevant counts, and the proportion (in percentage).

### 10. Create powershell scripts for following tasks:
- Create a html page and open it through powershell script on your browser.
- search a filename through powershell script (for this you need to create that file in your system.)
- create a script that plays mp3 file in your system's media player on entering the path of file by user.