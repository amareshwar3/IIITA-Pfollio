# Portfolio Management System
Portfolio Management System using MySQL, NodeJS, JavaScript, HTML & CSS

## Prerequisites
1. Install XAMPP web server
2. Any Editor (Preferably VS Code)
3. Any web browser with latest version

## Languages and Technologies used
1. HTML5/CSS3
2. JavaScript & EJS (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. NODEJS
6. MySQL (An RDBMS that uses SQL)

## Steps to run the project in your machine
1. Download and install XAMPP in your machine
2. Clone or download the repository
3. Start the Apache and Mysql in your XAMPP control panel.
4. Open your web browser and type 'localhost/phpmyadmin'
5. In phpmyadmin page, create a new database from the left panel and name it as 'portfolio'
6. Import the file 'portfolio.sql' inside your newly created database and click ok.
7. Now come to your downloaded folder and make a .env file
8. In env file, add DB,host,user,password,authemail,authepass,secret according to your database and email authentication pass (see 10.)
9. Format =>
	DB = portfolio
	host = localhost
	user = root
	password = phpmyadmi
	authemail = abcd@gmail.com
	authepass = aggdkgkdgka
	secret = MYSECRET
10.  [Use this video to setup authepass and authemail](https://www.youtube.com/watch?v=thAP7Fvrql4)

    
### Starting Apache And MySQL in XAMPP:
  The XAMPP Control Panel allows you to manually start and stop Apache and MySQL. To start Apache or MySQL manually, click the ‘Start’ button under ‘Actions’.
  
  
<p align="center"><img src="https://user-images.githubusercontent.com/36665975/59350977-fcc68900-8d3a-11e9-9450-e5c478497caa.png"></img></p>

## GETTING INTO THE PROJECT:
This system has a ‘Home’ page from where the admin,students and user can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project. Form validations are present with appropriate error/success messages. express-session takes the responsibility of maintaining sessions and nodemailer is used for sending mails. Bcryptjs takes the task of handing encryption and decryption of passwords.

![image](https://github.com/Risingstr6/IIITAPfollio/blob/main/ss/Screenshot%20(60).png)


## User Module:
Search a user by using full-email.


Provide feedback on how much they liked the site.




## Student Module:
Login Page



Sign Up Page

![image](https://github.com/Risingstr6/IIITAPfollio/blob/main/ss/Screenshot%20(62).png)

If someone has forgot his/her password, she will get temporary password through her email.

![image](https://github.com/Risingstr6/IIITAPfollio/blob/main/ss/Screenshot%20(63).png)
  &nbsp; 

After user has successfully logged in, he/she can edit his/her academic or non-academic details as shown below. He can also delete his profile and gets a option to logout of his profile.




### Admin Module:

 
  After succesfull login, admin can validate or reject edit requests of students based upon the documents provided by them
  

 On validation, respective student gets mail for validation of his request.
 On rejection, respective student gets mail for rejection of his request, with his details getting reset for that particular request.
 
  
  We also provide the admin with a dark mode and a logout button to logout.
  
  The admin also gets to see users feedback on what they think of the site
  


