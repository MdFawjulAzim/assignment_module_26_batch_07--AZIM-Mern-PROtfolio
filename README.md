# MERN Portfolio - Assignment Module 26 (Batch 07)

## Project Overview

This is a MERN (MongoDB, Express.js, React, Node.js) stack portfolio project developed as part of **Assignment Module 26** for Batch 07. The project showcases personal information, projects, and skills using a full-stack web development approach.

## Features

- **User Authentication**: Sign-up and login functionality with JWT authentication.
- **Portfolio Showcase**: Display of projects with descriptions and images.
- **Contact Form**: A form to receive messages from visitors.
- **Responsive Design**: Mobile-friendly UI built with React.
- **Backend API**: Node.js and Express.js for handling requests and MongoDB for data storage.

## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ORM
- **Authentication**: JSON Web Token (JWT)
- **Deployment**: (Mention if deployed, e.g., Vercel, Heroku, Netlify)

## Installation & Setup

### Prerequisites

- Node.js installed
- MongoDB setup (local or cloud-based, e.g., MongoDB Atlas)

### Steps to Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/MdFawjulAzim/assignment_module_26_batch_07--AZIM-Mern-PROtfolio.git
   cd assignment_module_26_batch_07--AZIM-Mern-PROtfolio
   ```

2. **Install Dependencies**

   ```bash
   npm install
   cd client
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add necessary configurations:

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   PORT=5000
   ```

4. **Run the Backend**

   ```bash
   npm run server
   ```

5. **Run the Frontend**

   ```bash
   cd client
   npm start
   ```

6. **Access the Application**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Folder Structure

```
root
│── client/ (Frontend React App)
│── server/ (Backend API)
│── models/ (Mongoose Models)
│── routes/ (Express Routes)
│── controllers/ (Controller Logic)
│── .env (Environment Variables)
│── package.json
│── README.md
```

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is licensed under the MIT License.

Md Fawjul Azim
