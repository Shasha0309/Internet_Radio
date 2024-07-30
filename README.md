# InternetRadio

[![Version 1.0](https://img.shields.io/badge/Version-v1.0.0-blue)]()
[![Live demo](https://img.shields.io/badge/Live-Demo-blue)]
<br>

# Overview

Welcome to my **Project** – it is a Cross-platform Real-time Audio Streaming designed to emulate the functionality and user experience. With a sleek and intuitive interface, users can browse through the platform to broadcast live audio, listen to live streams, and interact with each other through real-time commenting and chat functionality,the platform utilizes WebRTC and WebSockets to enable real-time audio streaming and communication. Leveraging users to create profiles, log in, and manage their accounts, ensuring a personalized experience and secure access to the platform. 

<br>

# Tech Stacks

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,redux,bootstrap,git,github,vscode" />
  </a>
</p>

# Features

This project includes the following features:
<ul>
    <li><strong>Authentication</strong> To access the platform, users can authenticate through either their Email or Phone Number.</li>
    <li><strong>Dynamic filter & Search Options:</strong> Update according to the customer's interest in real-time.</li>
    <li><strong>Customer Review's:</strong> Every product showcase their customer reviews.</li>
    <li><strong>Cart Management:</strong> Add, reduce, or delete products in Cart with ease.</li>
</ul>

<br>
- Authentication - Email/Phone No.
- Create Profile - Upload avatar
- Create Rooms
- Join Rooms
- Real-Time Audio sharing

# Setup Project

### How to run the Project
### Install without docker

Follow the following steps to get development environment running without Docker.

* Clone repository from GitHub
  
  ```
  
  git clone https://github.com/sidharth1017/InternetRadio.git
  
  ```

* Go to frontend folder

  ```
  
  cd .\frontend\
  
  ```

* Install node modules

   ```
   
   npm install

   ```

* Now, go to backend folder in another terminal
  
  ```
  
  cd .\backend\
  
  ```

* Similarly install node modules here too

  ```
   
   npm install
  
  ```

### Starting servers

* Frontend server

  You have to create .env file to run the server
  
  ```
  
    REACT_APP_API_URL=http://localhost:5500
    REACT_APP_SOCKET_SERVER_URL=http://localhost:5500
    NODE_ENV=development
  
  ```
  Go to terminal where you installed frontend node modules

  ```

  npm start

  ```

  Note - Server will start on port 5500

* Backend server
  
  You have to create .env file to run the server
  ```
  
    HASH_SECRET = 
    SMS_SID = 
    SMS_AUTH_TOKEN = 
    SMS_FROM_NUMBER = 
    DB_URL = 
    JWT_ACCESS_TOKEN_SECRET = 
    JWT_REFRESH_TOKEN_SECRET = 
    EMAIL = 
    PASSWORD =
    BASE_URL = http://localhost:5500
    FRONT_URL = http://localhost:3000
    NODE_ENV = development
  
  ```
  
  Now, go to the terminal where you installed backend node modules
  
    ```

      npm run dev

    ```

### Install and run with docker

Follow the following steps to get development environment running using Docker.
  ```
    docker-compose -f .\docker-compose.dev.yml up -d --build
  ```

---
