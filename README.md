# My InstaClone Backend

This is the backend for my version of an Instagram clone, built using Node.js, Express, and MongoDB. This project showcases my skills in web development, including authentication, file uploads, and RESTful API design.

## Features

- User Authentication (Register, Login, Logout)
- Create, View, Like, and Save Posts
- Follow/Unfollow Users
- View User Profiles and Feeds
- Upload and View Stories
- Search for Users

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running locally

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/my-instaclone-backend.git
    cd my-instaclone-backend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up MongoDB connection:
    - Ensure MongoDB is running on `mongodb://127.0.0.1:27017/instainsta`. Update the connection string in `models/user.js` if needed.

### Running the Application

To start the server:
```sh
npm start

