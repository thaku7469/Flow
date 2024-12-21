# Flow

Flow is a sleek and modern GitHub clone built using the MERN stack (MongoDB, Express, React, Node.js). It leverages the GitHub API to deliver a fully functional experience that mirrors the core features of GitHub. Flow combines intuitive user interfaces with robust functionality to showcase the power of full-stack development.

## Features

### 1. **Popular Repositories by Language**

- Explore popular repositories based on the programming language of your choice.
- Intuitive filters to help you find top projects quickly.

### 2. **Repository Viewing**

- View repository details including the description, stars, forks.
- Seamlessly navigate through repositories.

### 3. **Repository Liking**

- Like repositories to save them for future reference.
- Track your favorite projects with a personalized list.

### 4. **GitHub Account Integration**

- Fully functional login/logout feature using your GitHub account.
- Secure authentication with OAuth ensures your data is protected.

### 5. **Modern Design**

- A sleek and responsive UI designed for both desktop and mobile devices.
- Modern animations and design principles for an intuitive user experience.

## Technology Stack

- **Frontend**: React.js with styled-components for dynamic and responsive UI.
- **Backend**: Node.js with Express.js for robust and scalable API handling.
- **Database**: MongoDB Atlas for secure and efficient data storage.
- **Authentication**: GitHub OAuth for seamless user login and account management.
- **API Integration**: GitHub API for fetching repository and user data.

## Setup Instructions

### Prerequisites

- Node.js and npm installed.
- A GitHub account.
- MongoDB Atlas cluster.
- GitHub OAuth app credentials (client ID and client secret).

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/thaku7469/Flow.git
   cd flow
   ```

2. Install dependencies:

   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. Create a `.env` file in the root directory and add the following:

   ```env
   MONGO_URI=<Your MongoDB Atlas connection string>
   GITHUB_API_KEY=<Your GitHub api key>
   GITHUB_CLIENT_ID=<Your GitHub OAuth client ID>
   GITHUB_CLIENT_SECRET=<Your GitHub OAuth client secret>
   CLIENT_BASE_URL=<http://localhost:[port], during development mode>
   ```

4. Start the development servers:

   ```bash
   npm run build
   npm start
   ```

5. Open your browser and navigate to `http://localhost:5173`.

## Deployment

Flow is deployed and hosted for seamless access. Visit the live site at:
[https://flow-avt3.onrender.com](https://flow-avt3.onrender.com)

## Why Flow?

Flow is more than just a GitHub clone—it's a showcase of advanced development skills, from API integration to authentication and responsive design. This project demonstrates:

- Proficiency in full-stack development.
- Ability to design and implement user-focused features.
- Effective use of external APIs.
- Creating visually appealing and functional web applications.

## Future Enhancements

- Adding a "Follow Repository Updates" feature to track changes in real-time.
- Implementing user-to-user interaction via comments and stars.
- Expanding analytics for repositories.
- Localization support for non-English users.

---

### Author

Developed with passion by [Uday Thakur](https://github.com/thaku7469). Connect with me on [LinkedIn](www.linkedin.com/in/udaythakurindia) or check out my [portfolio](https://yourportfolio.com/).
