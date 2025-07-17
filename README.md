# Pathly Website Redesign (MERN Stack)

 **Pathly** website redesign, is a real client project built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The project includes continuous integration and continuous deployment (CI/CD) pipelines, comprehensive testing, and scheduled deployment for October 2025.

---

## Table of Contents

- [About Pathly](#about-pathly)  
- [Project Overview](#project-overview)  
- [Technology Stack](#technology-stack)  
- [Features](#features)  
- [Setup and Installation](#setup-and-installation)  
- [Testing](#testing)  
- [CI/CD Pipeline](#cicd-pipeline)  
- [Deployment](#deployment)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)



## About Pathly

Pathly Inc is a mission-driven nonprofit advancing STEM education access for underrepresented youth across Australia.

Currently in its implementation phase, Pathly is dedicated to delivering an exceptional user experience through a modern, responsive web platform.



## Project Overview

This repository hosts the complete redesign of the Pathly website, aiming to:

- Improve UI/UX with a modern React frontend  
- Build a robust backend API using Node.js and Express  
- Manage data storage and queries with MongoDB  
- Implement user authentication and authorization  
- Automate testing to ensure code quality  
- Set up CI/CD pipelines for seamless integration and deployment  
- Deploy to production in October 2025  

---

## Technology Stack

- **Frontend:** React.js, Tailwind CSS, HTML5  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Testing:**  Cypress testing
- **CI/CD:** GitHub Actions  
- **Deployment:** Vercel/ Render 

---

## Features

- Responsive design for desktop and mobile  
- User registration and login  
- Secure authentication (JWT or OAuth)  
- Interactive dashboards and user profiles  
- Real-time notifications (if applicable)  
- RESTful API with secure endpoints  
- Automated unit and integration tests  

---

## Setup and Installation

1. **Clone the repository**

   ```
   git clone https://github.com/your-username/pathly-redesign.git
   cd pathly-redesign

2.**Install dependencies**

Backend:
```
cd backend
npm install
```

Frontend:

```
cd ../frontend
npm install
```

3.Configure environment variables

Create .env files in /backend and /frontend directories with required keys such as:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=my_jwt_secret
REACT_APP_API_URL=http://localhost:5000/api
```

4.Run locally

Backend:
```
cd backend
npm run dev
```
Frontend:
```
cd ../frontend
npm start
```

5.Open http://localhost:3000 to view the app.

## Testing

Run unit and integration tests using:

Backend:
```
cd backend
npm test
```
Frontend:
```
cd frontend
npm test
```

## CI/CD Pipeline

Automated testing runs on every push and pull request via [GitHub Actions / your CI tool].

Successful builds trigger deployment pipelines.

Code quality checks and linting are enforced.

## Deployment

Scheduled production deployment planned for October 2025.

Deployed on Vercel, accessible at [URL coming soon].

Rollback and monitoring configured.

## Contributing
This is a client project. Contributions are managed by the project team. For questions or collaboration, please contact the project lead. 

## License

This project is proprietary and confidential to Pathly. Unauthorized use or distribution is prohibited.

## Contact
Project Lead:  Sababa T 
Email: 20028086@students.koi.edu.au 
