<h1 align="center">Socialise: A Full-Stack Social Media Platform</h1>
<h3 align="center">A feature-rich social media application built with the MERN stack (MongoDB, Express, React, Node.js), allowing users to connect, share posts, and interact with each other.</h3>

---

- 🔭 This project is a complete, full-stack social media web application.
- 💬 Ask me about **MERN stack, JavaScript, Node.js, Express, React, MongoDB, and REST APIs**.
- 🌱 I’m currently expanding my knowledge in **real-time applications with WebSockets and deploying MERN applications at scale**.
- 📫 How to reach me: **abhayanilark@gmail.com**
- 🧠 Fun fact: I love building applications that connect people and foster communities!

---

### 💼 Project Details

<table>
  <tr>
    <td><b>🌐 Socialise: A Full-Stack Social Media Platform</b></td>
    <td>
      A complete social media application with a powerful Node.js backend and a dynamic React frontend.
      <br/>
      🔹 <b>Features:</b>
      <ul>
        <li><b>User Authentication:</b> Secure user signup and login with password hashing using `bcryptjs` and JWT for session management.</li>
        <li><b>User Profiles:</b> Customizable user profiles with a profile picture, bio, and a feed of their posts.</li>
        <li><b>Create & Share Posts:</b> Users can create posts with an image and a caption. Images are handled by Cloudinary.</li>
        <li><b>Follow & Unfollow Users:</b> A robust following system allows users to see a feed of posts from people they follow.</li>
        <li><b>Interactive Posts:</b> Users can like/unlike posts and leave comments.</li>
        <li><b>Suggested Users:</b> A feature to suggest other users to follow, enhancing user engagement.</li>
        <li><b>Email Notifications:</b> The application uses `nodemailer` for email functionalities like password resets or account verification.</li>
      </ul>
      🔗 <a href="https://github.com/AnilarK/socialise" target="_blank">GitHub Repository</a>
    </td>
  </tr>
</table>

---

### 🛠️ Technologies Used

- **Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT, BcryptJS, Cloudinary, Nodemailer
- **Frontend:** React, Vite, Chakra UI, React Router, React Icons, Framer Motion
- **Database:** MongoDB

---

### 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

#### Prerequisites

- Node.js and npm
- A MongoDB database instance (local or cloud-based)
- A Cloudinary account for image storage

#### Backend Setup

1.  **Navigate to the backend directory:**
    ```sh
    cd backend
    ```
2.  **Install NPM packages:**
    ```sh
    npm install
    ```
3.  **Create a `.env` file** in the `backend` directory and add the following environment variables:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```
4.  **Run the backend server:**
    ```sh
    npm start
    ```

#### Frontend Setup

1.  **Navigate to the frontend directory:**
    ```sh
    cd frontend
    ```
2.  **Install NPM packages:**
    ```sh
    npm install
    ```
3.  **Run the development server:**
    ```sh
    npm run dev
    ```
    The frontend will be accessible at `http://localhost:3000`.

---

### 📖 About This Project

Socialise is a full-featured social media platform designed to provide a seamless and interactive user experience. It allows users to create and customize their profiles, share their thoughts and experiences through posts with images and captions, and connect with other users by following them. The application is built with a modern MERN stack, ensuring a robust and scalable architecture. With features like post liking, commenting, and user suggestions, Socialise aims to be an engaging and dynamic social networking tool.
