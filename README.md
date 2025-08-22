<p align="center">
  <a href="https://github.com/Brajesh31/Udemy_Clone">
    <img src="https://raw.githubusercontent.com/Brajesh31/asset/main/udemy-clone-banner.png" alt="Udemy Clone Banner">
  </a>
</p>

<div align="center">

# 🎓 Udemy Clone 👨‍🏫

**A feature-rich, full-stack web application replicating the core functionalities of the popular online learning platform, Udemy.**

</div>

<p align="center">
  <a href="[LINK_TO_YOUR_LIVE_DEMO]">
    <img src="https://img.shields.io/badge/Live-View_Demo-brightgreen?style=for-the-badge&logo=vercel" alt="Live Demo">
  </a>
  &nbsp;
  <img src="https://img.shields.io/github/stars/Brajesh31/Udemy_Clone?style=for-the-badge&color=gold" alt="Stars">
  &nbsp;
  <img src="https://img.shields.io/github/license/Brajesh31/Udemy_Clone?style=for-the-badge&color=blue" alt="License">
</p>

---

## ## ✨ Project Overview

This project is a comprehensive clone of Udemy, built from the ground up using the MERN stack. It provides a platform for instructors to create, manage, and sell courses, and for students to browse, purchase, and consume educational content.

The application is designed to be scalable and robust, incorporating features like user authentication, payment gateway integration, video processing, and course review systems. It serves as a strong portfolio piece demonstrating proficiency in full-stack web development.



---
## ## ⭐ Core Features

### For Students 🎓
* **User Authentication**: Secure registration and login functionality.
* **Course Catalog**: Browse and search for courses by category or keyword.
* **Shopping Cart**: Add desired courses to a shopping cart.
* **Payment Gateway**: Securely purchase courses using Stripe.
* **Course Enrollment**: Access purchased courses from a personal dashboard.
* **Video Player**: Stream course lectures with a modern video player.
* **Progress Tracking**: Keep track of completed lessons.
* **Reviews and Ratings**: Leave feedback and ratings on completed courses.

### For Instructors 👨‍🏫
* **Instructor Dashboard**: A dedicated dashboard to manage courses and view sales data.
* **Course Creation**: An intuitive interface to create new courses, define curriculum, and set pricing.
* **Video Upload**: Upload and process video lectures using Cloudinary.
* **Course Management**: Edit and update existing course content.

---
## ## 🛠️ Technology Stack

This project is built with a modern, full-stack JavaScript ecosystem.

| Category         | Technology                                                                                                                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Frontend** | [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/) |
| **Backend** | [![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)         |
| **Database** | [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)                                                                                                                                         |
| **Authentication**| JSON Web Tokens (JWT)                                                                                                                                                                                                                                                    |
| **Payments** | [![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white)](https://stripe.com/)                                                                                                                                                 |
| **Video Hosting**| [![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)](https://cloudinary.com/)                                                                                                                                 |

---
## ## 🚀 Getting Started

To get a local copy up and running, follow these detailed steps.

### ### ✅ Prerequisites

* **Node.js** (v18.x or later)
* **npm** & **Git**
* **MongoDB**: Make sure you have a MongoDB server running locally or a connection string from MongoDB Atlas.

### ### ⚙️ Installation & Setup

1.  **Clone the repository**:
    ```sh
    git clone [https://github.com/Brajesh31/Udemy_Clone.git](https://github.com/Brajesh31/Udemy_Clone.git)
    ```
2.  **Navigate to the project directory**:
    ```sh
    cd Udemy_Clone
    ```
3.  **Backend Setup**:
    * Navigate to the backend directory: `cd server`
    * Install backend dependencies: `npm install`
    * Create a `.env` file in the `server` directory and add the environment variables listed below.
    * Start the backend server: `npm start`

4.  **Frontend Setup**:
    * Navigate to the frontend directory from the root folder: `cd client`
    * Install frontend dependencies: `npm install`
    * Create a `.env` file in the `client` directory for any client-side keys.
    * Start the frontend development server: `npm start`

### ### 🔑 Environment Variables

You need to create a `.env` file in the `server` directory and add the following variables:
