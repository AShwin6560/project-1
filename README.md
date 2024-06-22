
# Vechile rental & Booking System



**Your number one source for all type of Car Renting and Car Booking.**

Vechile rental & Booking System is a web-based system for renting and booking vehicles. People who has a vehcle in the home can earn some extra money by putting his/her vehicle on this website for rent. Also, people who need a vehicle for their picnic can book a vehicle as they need.

What is the main advantage of using this website for vehicle renters, rather than putting their vehicle in a car rental sale is that they can use their vehicle while renting on this website.


## Screenshots

### Home Screen :

![App Screenshot] Take urself plz

### Rent | Book :

![App Screenshot] Take urself plz

### Admin Panel :

![App Screenshot] Take urself plz
## Configure the project

- You should move the project folder into the "**htdocs**" folder if you are using Xampp Server.  

- Create a database (you can use any DBMS) called "**rental**". 

- Import the database file which is in the sql folder of the project to the "**rental**" database.

- Open the project on your browser by pasting following link on the url bar if you are yousing the default port 80.
 
```bash
  http://localhost/Rental/
```
- In order to rent or books vehicles you need to have an account on the web site. Either you van create a new account or you can use an existing account. Account credentials are as follows
  - To create a new account: 
 ```bash
     http://localhost/Rental/reg.php
```
- To use existing account:
  - Username, Email & password:
 ```bash
    Ashwin  

 ```bash
     msah22966@gmail.com
``` 
```bash
    12356789
```
- You can log into the admin panel by pasting the following url on the browser url bar.
```bash
  http://localhost/Rental/adminlogin.php
```
- Email and Password for a default admin account are as follows. Even you can create a new admin account too. But if you want to check the admin list, youu have to use the default admin account.
  - Email & password:
```bash
     mukesh@admin.com
``` 
```bash
     pass
```
## Deployment

After successfuly configuring the project, the home page of the website can be seen. To check the available vehicles for booking user should go to the "**SHOWROOM**" or "**Book A Vehicle**" page, by clicking those buttons on the home page. So the user doesn't want to create an account (register) or log into his account to check the available wehicles on the website.

### Register:

- In order to put a vehicle on the site for renting or book a vehicle, first of all user need to create an account if he/she hasn't. 

- Clicking the "**REGISTER**" button on the top header, user is able to create an account easily by providing the relevent required details. 

- The given **Username**, **Email address** & **Password** is requred to log into the created account. 

- After creating an account, user can log into his/her account using the provided account credential. 

- Then user is allowed to put an advertiesment on the website about his/her vehicle and/or make bookings as he/she want. 

### Rent A Vehicle:

- To post an advertiesment, user just needs to go to the "**Rent A Vehicle**" page by clicking the "**Rent A Vehicle**" button and submit an advertiesment by filling the all required information. 

- As soon as the details were submitted, the vehicle renting advertiesment is posted on the website. 

- User can check it in the "**Showroom**" page or it is alo displayed on the "**Rented Vehicles**" area of the user profilr page as below.

- If someone booked a vehicle rented by this user, he/she is informed by a notification as below and also an admin also can contact the renter. Also the notifications are displayed after an admin confirms that booking and after returning the vehicle.



- All the income and profit information are displayed as follows on the income tab.



### Book A Vehicle:

- Even though it is not required to log into the accout for searcing a vehicle, when booking the choosed vehicle, user must first log into his account in order to make the booking. 

- By clicking the "**BOOK**" button at the bottom of the vehicle description page, user should first fill the required informatin which are the "**Picking Date**", "**Returning date**", etc.

- Then the choosed vehicle can be booked by again clicking the "**BOOK**" button and the details of the booking is displayed on the user profile page under the "**Booked Vehicles**" area as below.



- The blue color "**Your Booking is Pending**" message is apeared because the booking is still not approved by the admin. It means the booking is in the pending status. 

- An admin should confirm or delete the booking within a few hours of time.

- After confirming the booking by admins, it is displayed as "**Your Booking has been Confirmed**" with an orange background on the profile page, and also a notification will be arived.


- Then the user can collect the vehicle for his/her picnic.

- After the picnic, user should return the vehicle on or before the returning date. Then the admin confirm the return of the vehicle and the orange color message turns into green on the user profie page.




### Admins

- Admins can check the Rented & Booked vehicles on the "**Rented Vehicles**" & "**Booked Vehicles**" tabs respectively.

- Clicking the "**View**" button on each row, admin can view the details of the corresponding Booking or Rental and take relevent actions.


- To confirm a booking, admin should click the "**Confirm**" button and the background becomes orange.

- To confirm a returning, admin should click the "**Return**" button and the background becomes green.






## Security

- Even admint are not visible the user passwords of the accounts in the database
- Confidential credentials have been hashed and inserted to the database.
- Every action is take place under an admin's supervison.
- Admin's approvement is required to confirm a booking made by a customer.
- Customers can delete a bokking made by him or her self before an admin approves it. 


