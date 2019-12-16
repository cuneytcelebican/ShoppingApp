**About the application**
* This application specifically developed for Carleton University - COMP2406 students with love between September 2018 ant March 2019.

**How to run**
To run this app you need a personal Paypal Account
You can create on at paypal.com
When you create the account you don't need to link a credit card or bank account at that
time. I just ignored that step when prompted and it created the account anyway. I received confirmation by email.

**Changing pay-pal account**
Visit app.js file then change client_id and client_secret with your 
pay-pal sandbox account. 

You can create a sandbox account from below link
https://developer.paypal.com/

**Setup the project**
Before starting application please run the populate-for-startup.js 
file inside the seed directory to populate the mongodb database.
You can basically run the file with below command (after locating in the terminal)
`node populate-for-startup.js`

Install the npm module depedencies in package.json by executing:
`npm install`

**Run the application**
In the application folder execute:
`npm start`

**Login information**
username : `admin@admin.com`
password : `admin`

**Please note**
Before starting application please make sure your mongo database runs.

**Features**
* Upload local/online photos for products
* Add, delete, or update product
* Add, delete, or update variant
* Add, delete, or update department
* Add, delete, or update category
* Add, or delete discount code
* Sends email on the sign-in
* Advance search bar (search for product and categories)
* Buy item
* Shopping cart
* Order history
* Distinguishes user and admin
* Filters