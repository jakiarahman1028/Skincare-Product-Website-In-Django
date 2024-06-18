# Skincare-Product-Website-In-Django
La’ Belle is a fashion and lifestyle  e-commerce site that offers a huge selection of apparel and accessories. Using Python, Django, HTML, CSS, JavaScript, and a SQLITE3 database,  this Django skincare products website will be created. This website will help an online retailer or business offer its clients an online ordering platform. There are two user interfaces on the system: one is for the administrator, and the other is for the client, which is the website. Through this project, registered customers can browse the wide range of products that are offered, buy what they want right away using the Bkash’s payment processor (Instant Pay), or place orders utilizing the Cash on Delivery (Pay Later) option. Orders placed with the Instant Pay and Pay Later options are easily seen by administrators and managers. 
# SYSTEM DESIGN
Here's an overview of the features for designing an online shopping system: 
## Features of admin side: 

### • Dashboard – 
From the admin dashboard, you will have access to all of the system’s core functions. For example, product summaries, orders etc.

### • Admin Access to Product Management Information System – 
The admin has access to the product management information system. He has the ability to add, update, and delete products.

### • Manage Orders – 
As one of the admin’s primary tasks, the admin can accept or reject orders from clients on a case-by-case basis. 

### • Customer Management – 
The admin has access to the customer’s account. The system administrator can add, edit, and update customers. 

### • Secure Login and Logout – One of the system’s security features is the secure login and logout system, which is enabled by default. 

## Features of customer side: 

### • Login Page – 
This page is where customers enter their website credentials to receive access 
to all of the site’s features. 
### • The Register Page – 
This is where new customers create their website login credentials. 
### • Homepage – 
This is the system’s default page when customers visit the website. This page 
displays the products available for purchase in the store, or you may search for specific 
items using the search box above the products. 
### • Contact Us – 
The frontend client can send an inquiry to the system’s administrator via the 
contact us page. 
### • Feedback – 
The frontend user can submit feedback to the system’s administrator using the 
feedback feature. 
### • Customers’ Profiles – 
Customers can register and edit their profiles in the frontend. In a 
nutshell, this system includes a customer management system. 
### • Product View Page – 
The page on which the customer adds the product to his or her cart 
as well as the page on which the product’s specific information is displayed. 
### • Cart List –
The page that lists the products that the consumer has chosen is called the Cart 
List Page. The customer can complete the order checkout process on this page. 
### • My Orders Page – 
This is the page where the customer’s orders are listed. 
### • Payments – 
This Django Skincare website Project accepts Bkash’s Payments as a payment 
mechanism. 
### • Order Tracking – 
This website allows customers to track their orders. 

# STEPS TO RUN THE SYSTEM

These are the step’s to run an Online Skincare Product Website Project in Django: 
### 1. pip install virtualenv 
Firstly, we need to install the virtualenv, Open a command prompt by going to the project 
folder directory and typing CMD. After opening the CMD type “ pip install virtualenv”. 
### 2. virtualenv env 
Then, after installing virtualenv we have to type “virtualenv env” and enter. 
### 3. cd env/Scripts 
Next, we must type. “cd env/Scripts” and press enter. 
### 4. Activate 
Next, we need to type “activate” then press enter. 
### 5. cd ../.. 
Then will type “cd ../..” and press enter. 
### 6. Install Django 
To install Django, “pip install django” command is need to be typed. 
### 7. python manage.py makemigrations 
After installation of  the requirements, we need to type this command “python manage.py 
makemigrations” to create a tables in the database. 
### 8. python manage.py migrate –run-syncdb 
The command “python manage.py migrate –run-syncdb” need to be typed after making 
migrations to migrate the tables in database. 
### 9. python manage.py createsuperuser 
After migration of database you need to create super user to login in the admin account, 
just you need is to type the command “python manage.py createsuperuser”. 
### 10. python manage.py runserver 
Lastly, after creating super user, the command “python manage.py runserver” need to be 
typed for testing and launching the project. 
### 11. http://127.0.0.1:8000/ 
Finally, to access the project dashboard, we have to copy this URL 
“http://127.0.0.1:8000/” into our browser.

# LIMITATION
1. There is only one direct payment system in the website.  
2. This website does not have features by which user can set price ranges for products and 
receive alerts once the price reaches the particular range. 
3. Customers cannot create wish lists which they can access later. 
4. Admin does not hold any product return and refund policy. 
5. The whole system can be susceptible to security breaches. 
