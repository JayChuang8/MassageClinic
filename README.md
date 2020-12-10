# MassageClinic API

## System Requirements
*XAMPP installed and running  
*Running Apache and MySQL  
*Change Apache config httpd.conf line 252 & 253 to directory of where the project is.  
Ex) DocumentRoot "C:\Users\jaych\OneDrive\Desktop"  
<Directory "C:\Users\jaych\OneDrive\Desktop">  

## To create database on your local machine
1) Create a schema called 'massage_clinic'   
2) Run massage_clinic.sql in an SQL query.  

Go to massageClinic/config/Database.php and change lines 6-7  
    ```
    private $username = 'your database local connection username';  
    private $password = 'your password';  
    ```
    
## To run website on your computer
*type into any web browser 'http://localhost/massageClinic/frontend/home.php' and enter  

To try Postman on the database:  
*Import the 'API Requests.postman_collection.json' into Postman  
*All the commands are preloaded with inputs already for testing  
