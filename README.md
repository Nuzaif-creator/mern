# Mobile-Store-MERN-APP

An ecommerce website built using the MERN stack (MongoDB, Express, React, Node.js).

## How the App Works

The application follows a client-server architecture, with the frontend built using React and the backend powered by Node.js and Express. MongoDB serves as the database to store product information, user data, and order details.

The `App.js` file serves as the entry point to the frontend, defining all the necessary routes for the application. It provides routes for the home page, product details, categories, cart, search functionality, and various user and admin pages. The `PrivateRoute` and `AdminRoute` components are used to handle authenticated user and admin access, respectively.

The backend utilizes various dependencies, such as `express-formidable` for handling form data, `jsonwebtoken` for user authentication, `bcrypt` for password hashing, and `cors` to allow cross-origin requests. The database interactions are managed using `mongoose`, ensuring smooth communication with the MongoDB database.

