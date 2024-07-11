# UniCraves

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to UniCraves! This is a collaborative project designed to create a seamless and efficient food ordering platform tailored specifically for college students. Our goal is to provide a user-friendly interface for students to order food from various vendors around campus and beyond.

## Features
- User authentication (Sign up, Log in, Log out)
- Browse food menus from different vendors
- Place and track orders
- User profiles and order history
- Real-time notifications for order status
- Responsive design for mobile and desktop

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Real-time**: Socket.io
- **Deployment**: AWS

## Getting Started

### Prerequisites
Ensure you have the following installed on your local machine:
- Node.js (>= 14.x)
- MongoDB
- Git

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/username/unicraves.git
    cd unicraves
    ```

2. Install dependencies for both client and server:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. Create a `.env` file in the `server` directory and add the following:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. Start the development server:
    ```bash
    cd server
    npm run dev
    ```

5. Start the client:
    ```bash
    cd client
    npm start
    ```

## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Sign up for a new account or log in with existing credentials.
3. Start exploring menus and placing orders!

## Contributing
We welcome contributions from the community! Here's how you can get involved:

1. **Fork the repository**: Click the "Fork" button at the top right of this page.
2. **Clone your fork**: 
    ```bash
    git clone https://github.com/your-username/unicraves.git
    ```
3. **Create a feature branch**: 
    ```bash
    git checkout -b feature-name
    ```
4. **Commit your changes**: 
    ```bash
    git commit -m "Add some feature"
    ```
5. **Push to the branch**: 
    ```bash
    git push origin feature-name
    ```
6. **Create a Pull Request**: Go to the original repository and create a new pull request.

Please make sure your code adheres to our coding standards and includes appropriate tests.

## Contact
Feel free to reach out to the project maintainers:
- **Aryan Gupta** - [LinkedIn](https://linkedin.com/in/aryan-gupta-169542216)
- **GitHub** - [Aryan07982](https://github.com/Aryan07982)
- **Aritra Chatterjee** - [LinkedIn](https://linkedin.com/in/aritra-chatterjee-490458279)
- **GitHub** - [aritrachatterjee7](https://github.com/aritrachatterjee7)
- **Shubhra Jyoti Bhattacharjee** - [LinkedIn](https://linkedin.com/in/shubhra-jyoti-bhattacharjee-172356280)
- **GitHub** - [shubhra-9](https://github.com/shubhra-9)
- **Ankit Singh** - [LinkedIn](https://linkedin.com/in/ankit-singh-12b819239)
- **GitHub** - [thetribalgod](https://github.com/thetribalgod)

Happy coding! Let's build something amazing together!
