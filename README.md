# CSC350_FALL2022_Group_E
Laundry Project
Thank you so much for using our website.


NOTES: To be able to create,delete and modify the users you need to log in the system as the admin, ID: Admin and the password: 321
![Notes for project](https://user-images.githubusercontent.com/80984930/206946864-d653cb65-1fd1-4476-924f-c5323f939dce.jpg)
To use the website you need to: 

1.Run "Laundry Project\CreateDatabase\CreateDatabase.sql" on mysql client to create database and tables, User ADMIN ID:Admin and Password:321 is created by default when you run the code.

2.Put the project code "Laundry Project\Laundry" into your webpage server, like xampp


3.Change to your mysql connection info in below file
  Laundry Project\Laundry\dbConnect.php
  line3   ---   $conn = mysqli_connect("localhost", "root", "root"); 
  
4.Start your webpage server, and open web browser, go to http://localhost/Laundry_Project/laundry/index.html
