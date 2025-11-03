# Thrift-Store-Vintasy

## Overview
Thrift-Store-Vintasy is a full-stack web application built using Node.js, Express, and MongoDB. It serves as an online thrift marketplace where users can both buy and sell pre-loved items. Sellers can upload product listings directly to their profiles, which function as personalized online stores. The project was developed as part of the Database and Web Technologies course to demonstrate CRUD operations, authentication, and dynamic rendering using EJS templates.

## Features
- User authentication and profile management  
- Product upload and listing management  
- Individual seller profiles that act as stores  
- Product browsing, searching, and filtering for buyers  
- Image upload for listed items  
- Responsive frontend using Bootstrap  
- MongoDB database integration for storing user and product data  

## Tech Stack
- **Frontend:** EJS (Embedded JavaScript), HTML, CSS, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ORM)  
- **Tools:** Postman, Nodemon, Cloudinary (optional for image hosting)  

## Architecture
The project follows the Model-View-Controller (MVC) pattern:

- **Model:** Defines MongoDB schemas for users and products  
- **View:** EJS templates for dynamic UI rendering  
- **Controller:** Handles business logic, routes, and server responses  

## Folder Structure
```
Thrift-Store-Vintasy/
│
├── models/
│   ├── userModel.js
│   └── productModel.js
│
├── routes/
│   ├── userRoutes.js
│   └── productRoutes.js
│
├── views/
│   ├── home.ejs
│   ├── profile.ejs
│   ├── productDetails.ejs
│   └── upload.ejs
│
├── public/
│   ├── css/
│   ├── images/
│   └── js/
│
├── app.js
├── package.json
└── README.md
```

## Database Schema Overview
- **User:** name, email, password (hashed), profile info, productsUploaded[]  
- **Product:** title, description, price, category, imageURL, sellerId  

## Future Enhancements
- Integrate payment gateway (Stripe or PayPal)  
- Add product reviews and ratings  
- Implement chat or message system between buyers and sellers  
- Improve UI using React for modern interactivity  

## Team Members
- Momna Shafqaat  
- Momna Ahmed  
- Kiran Shehzadi  
- Hira Batool  

## Course Information
- **Course:** Database and Web Technologies  
- **Institution:** COMSATS University Lahore  
- **Semester:** 4th Semester  
- **Year:** 2024
