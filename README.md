# Description

I have created a SaaS WebApp where users can browse the different services and subscribe to multiple plans through the stripe payment gateway. In this project I have implemented the following things:
- SaaS plan with “Basic”, “Standard” and “Plus”
- List of the plans with details
- The services the user wishes to purchase can be stored/viewed in the cart.
- Checkout with Stripe integration with multiple subscription plans at once.
- User authentication through Login and SignUp pages.
- Checkout process where users enter their payment details.
- Super admin dashboard to manage the plans.
- Admin dashboard to manage the users.

# Getting started

## Clone the repository
```
git clone https://github.com/Brothin/Subscription-App.git
```
```
cd Subscription-App
```

## You need
• Node

• MongoDB or Mongo Atlas

• NPM

## Create your MongoDB account and database/cluster
• Create your own MongoDB account by visiting the MongoDB website and signing up for a new account.

• Create a new database or cluster by following the instructions provided in the MongoDB documentation. Remember to note down the "Connect to your application URI" for the database, as you will need it later. Also, make sure to change with your own password.

• Add your current IP address to the MongoDB database's IP whitelist to allow connections (this is needed whenever your ip changes).

## Create .env file
Create a .env file in the backend folder to store your credentials. This file will store environment variables for the project to run.
```
MONGO_URL = 'mongodb+srv://<username>:<password>@mongodburlhere'
PORT = PortNumber
```

## Installation
To install and run this project
Install dependencies using npm in frontend folder and run client side of application.
```
cd frontend
npm install
npm start
```
Install dependencies using npm in backend folder and run server side of application.
```
cd backend
npm install
npm start
```

```
Admin credentials:
id:admin@gmail.com
pw:admin123

Super Admin credentials:
id:superadmin@gmail.com
pw:superadmin
```

Tech Stack Used:
- React JS
- Material UI
- Node JS
- Express JS
- MongoDB
- Mongoose
- REST API
