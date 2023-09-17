# FindYourNextHike

The server side is built using Express and is connected to a MongoDB database through Mongoose. Authentication is managed using JWT, and payments are facilitated via Stripe.

## Prerequisites
Ensure you have the following installed on your machine:

Node.js (v14.x or newer)
MongoDB (v4.x or newer)
## Getting Started
### 1. Clone the repository:

```
git clone https://github.com/ShubhamAXS19/FindYourNextHike.git
```
### 2. Navigate to the project directory:
```
cd FindYourNextHike 
```

### 3. Install dependencies:

#### For the server:
```
cd server
npm install
```

### 4. Setting up environment variables:

For the server, inside the server directory, create a .env file with the following:

```
DATABASE_PASSWORD = 
USERNAME = 
CONNECTION_STR = 
NODE_ENV= development
PORT = 3000


JWT_SECRET = 
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=90

EMAIL_HOST = smtp.mailtrap.io
EMAIL_PORT = 
EMAIL_USERNAME = 
EMAIL_PASSWORD = 
EMAIL_FROM =

SENDGRID_USERNAME = apikey
SENDGRID_PASSWORD =

STRIPE_SECRET_KEY  = 
```

### 5. Running the project:

Server:
From the server directory:

```
npm run dev
```
Visit <br/>
```
http://localhost:3000
```

### 6. For Documentation
Visit <br/>

```
http://localhost:8080/docs
```

### 7. Features
1. User authentication using JWT & Passport. <br/>
2. Admin panel to manage tours. <br/>
4. Responsive UI using pug.<br/>


### 8. Project Structure
Server <br/>
| --> controllers <br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp; &nbsp;  | --> Auth.js <br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Booking.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Error.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Review.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Tour.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> User.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Views.js <br/>
| --> models<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Booking.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Review.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Tour.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> User.js<br/>
| --> routes <br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Booking.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> Review.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Tour.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp;  | --> User.js<br/>
|&nbsp;   &nbsp;   &nbsp;  &nbsp;  &nbsp; | --> Views.js <br/>
| --> package-lock.json<br/>


### 9.Images of App

1. Login <br/> 
<img width="1440" alt="Screenshot 2023-09-17 at 8 47 43 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/a263d545-04bc-4f8d-914e-e51a907b62ff">
2. SignUp <br/> 
<img width="1440" alt="Screenshot 2023-09-17 at 8 47 43 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/6499c673-94fd-4020-9ba5-97826a274b8b">
3. All Tours <br/>
<img width="1440" alt="Screenshot 2023-09-17 at 8 53 40 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/0bcc4292-bc42-469f-b28e-4ec07ca79df7">
4. Tour Detail<br/>
<img width="1440" alt="Screenshot 2023-09-17 at 8 54 12 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/21131357-246a-46ed-ba4c-0339a4a14da7">
<img width="1440" alt="Screenshot 2023-09-17 at 8 54 20 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/772830fe-5a83-44d3-ae43-95500e51ed0d">
<img width="1440" alt="Screenshot 2023-09-17 at 8 54 28 PM" src="https://github.com/ShubhamAXS19/FindYourNextHike/assets/80101565/d0f1f786-94f0-4321-875a-95560359e431">







