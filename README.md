# HobbyHub

HobbyHub is a full-stack web application aimed at connecting individuals through their shared interests and passions. This platform empowers users to discover, share, and engage with a vibrant community based on various hobbies.

<p>
  <a href="https://ibb.co/ksR36SRT"><img src="https://i.ibb.co/jPcVZrcY/ss1.png" alt="ss1" border="0"></a>
  <a href="https://ibb.co/9mtsNHS8"><img src="https://i.ibb.co/mr86G5gD/ss2.png" alt="ss2" border="0"></a>
  <a href="https://ibb.co/Y7pZpBHL"><img src="https://i.ibb.co/99stsHQr/ss3.png" alt="ss3" border="0"></a>
</p>

## Technologies Used

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

## Main Features

* **User Authentication:** Secure sign-up and login functionalities for users.
* **User Profiles:** Create and manage personal profiles showcasing hobbies, interests, and posts.
* **Post Creation & Management:** Users can create, view, edit, and delete posts related to their hobbies, including text and images.
* **Hobby Categories:** Browse and filter content by various hobby categories.
* **Community Interaction:** Engage with other users through comments on posts and discover new connections.
* **Responsive Design:** Optimized for a seamless user experience across desktops, tablets, and mobile devices.

## Dependencies

This project relies on several key dependencies for both its frontend and backend operations.

**Frontend (React):**
* `react`: The core React library for building user interfaces.
* `react-router-dom`: For declarative routing in your React application.
* `axios`: A promise-based HTTP client for making API requests.
* `react-icons` (or similar): For easy inclusion of popular icon libraries.
* `tailwindcss` or `bootstrap` (or similar): For styling and responsive layout.
* *(Add any other significant frontend libraries you used from your `package.json` here)*

**Backend (Node.js/Express.js):**
* `express`: Fast, unopinionated, minimalist web framework for Node.js.
* `mongoose`: MongoDB object modeling tool for Node.js, providing a straightforward schema-based solution.
* `cors`: Node.js package for providing a Connect/Express middleware that can be used to enable CORS with various options.
* `dotenv`: Loads environment variables from a `.env` file into `process.env`.
* `bcryptjs`: For hashing passwords securely.
* `jsonwebtoken`: For implementing JSON Web Tokens for secure authentication.
* *(Add any other significant backend libraries you used from your `package.json` here)*

## How to Run Locally

To get a local copy of this project up and running on your machine, follow these simple steps:

### Prerequisites

Before you begin, ensure you have the following installed:
* **Node.js** (LTS version recommended)
* **npm** (Node Package Manager) or **Yarn**
* **MongoDB** (running locally or a cloud instance like MongoDB Atlas)
* **Git**

### Backend Setup

1.  **Clone the backend repository:**
    ```bash
    git clone [https://github.com/Amirun-Nahar/HobbyHub-Backend.git](https://github.com/Amirun-Nahar/HobbyHub-Backend.git)
    ```
2.  **Navigate into the backend directory:**
    ```bash
    cd HobbyHub-Backend
    ```
3.  **Install backend dependencies:**
    ```bash
    npm install
    # or yarn install
    ```
4.  **Create a `.env` file in the `HobbyHub-Backend` directory** and add your environment variables.
    ```
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
    *Replace `your_mongodb_connection_string` with your actual MongoDB URI.*
5.  **Start the backend server:**
    ```bash
    npm start
    # or node server.js (if your main file is named server.js)
    ```
    The backend server should now be running on `http://localhost:5000` (or your specified port).

### Frontend Setup

1.  **Clone the frontend repository:**
    ```bash
    git clone [https://github.com/Amirun-Nahar/HobbyHub-Frontend.git](https://github.com/Amirun-Nahar/HobbyHub-Frontend.git)
    ```
    *(If your frontend is in the same repository, navigate to its subfolder, e.g., `cd client`)*
2.  **Navigate into the frontend directory:**
    ```bash
    cd HobbyHub-Frontend
    # or cd client (if it's a subfolder in a monorepo)
    ```
3.  **Install frontend dependencies:**
    ```bash
    npm install
    # or yarn install
    ```
4.  **Create a `.env` file in the
