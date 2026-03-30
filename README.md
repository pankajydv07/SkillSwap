# 🔁 Skill Swap – Exchange Skills, Empower Growth
# 🔁 SkillSwap – Exchange Skills, Empower Growth

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-5.x-green.svg)](https://www.mongodb.com/)

> A full-stack platform connecting people through skill exchange and mutual learning

---
 
 ## 🧠 Overview
 
**Skill Swap** is a full-stack web application that connects people through the power of shared skills and knowledge exchange. It's a modern platform where users can offer skills they have and request skills they want to learn, creating a collaborative community of mutual growth and learning.
**SkillSwap** is a full-stack web application that connects people through the power of shared skills and knowledge exchange. It's a modern platform where users can offer skills they have and request skills they want to learn, creating a collaborative community of mutual growth and learning.

Whether you're offering help or seeking it, every exchange builds trust and community. Grow, connect, and transform—one skill at a time, in a place made for mutual growth.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Installation & Setup](#-installation--setup)
- [Environment Variables](#-environment-variables)
- [Project Structure](#-project-structure)
- [Usage](#-usage)
- [Screenshots](#-screenshots)
- [API Documentation](#-api-documentation)
- [Contributing](#-contributing)
- [Troubleshooting](#-troubleshooting)
- [License](#-license)
- [Contact & Acknowledgments](#-contact--acknowledgments)

---

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern UI library with hooks and functional components
- **React Router** - Client-side routing for seamless navigation
- **Axios** - HTTP client for API requests
- **CSS3/Styled Components** - Modern styling approaches

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Fast, unopinionated web framework
- **MongoDB** - NoSQL database for flexible data storage
- **Mongoose** - Elegant MongoDB object modeling
- **JWT** - JSON Web Tokens for secure authentication
- **Bcrypt** - Password hashing for security

### Development Tools
- **Concurrently** - Run multiple npm commands simultaneously
- **Nodemon** - Auto-restart server during development
- **dotenv** - Environment variable management

---

## ✨ Features

### 🔐 Authentication & User Management
- **Secure Authentication**: JWT-based login/signup with email & password
- **User Profiles**: Comprehensive profile management with skills offered/wanted
- **Privacy Controls**: Public/private profile visibility settings
- **Protected Routes**: Secure access control throughout the application
- **Profile Customization**: Update personal information, availability, and location

### 🏠 Home & Landing Page
- **Dynamic Landing Page**: Engaging hero section with gradient designs
- **Feature Showcase**: Clear presentation of platform capabilities
- **Call-to-Actions**: Strategic CTAs for "Browse Skills", "Start Learning", etc.
- **Responsive Design**: Mobile-first approach with modern UI/UX
- **Platform Overview**: Clear introduction to skill exchange concept

### 🔍 Browse & Discovery
- **Advanced Search**: Search by skill name, category, or keywords
- **Smart Filters**: Filter by availability, experience level, and user type
- **User Cards**: Clean, informative user profile cards with key details
- **Skill Matching**: Intelligent matching between offered and wanted skills
- **Real-time Updates**: Live availability and status updates
- **Pagination**: Efficient browsing through large user databases

### 👤 User Dashboard & Profiles
- **Personal Dashboard**: Overview of user's skills, requests, and activity
- **Skill Management**: Add, edit, and organize skills offered and wanted
- **Skill Categories**: Organized skill categorization system
- **Availability Settings**: Configure when you're available for skill exchanges
- **Location Services**: Location-based skill matching and suggestions

### 🔄 Skill Swap Requests
- **Request Management**: Send, receive, and manage skill swap requests
- **Request Details**: Comprehensive request forms with messaging
- **Status Tracking**: Track request states (pending, accepted, rejected, completed)
- **Scheduled Sessions**: Date and time scheduling for skill exchanges
- **Request History**: Complete history of all swap requests and their outcomes
- **Feedback System**: Rate and review completed skill exchanges

### 📊 Admin Panel & Management
- **Admin Dashboard**: Comprehensive analytics and platform statistics
- **User Management**: Admin tools for user moderation and management
- **Content Moderation**: Review and manage reported content
- **System Analytics**: Track user engagement and platform growth
- **Role-based Access**: Different permission levels for users and admins

### 💬 Communication & Notifications
- **Real-time Messaging**: Chat functionality between swap partners
- **Notification System**: Email and in-app notifications for requests
- **Activity Feed**: Track recent activities and updates
- **Email Integration**: Automated emails for important updates

### 🛡️ Security & Privacy
- **Data Encryption**: Secure storage of sensitive information
- **Input Validation**: Protection against common vulnerabilities
- **CORS Protection**: Configured for secure cross-origin requests
- **Rate Limiting**: Protection against brute force attacks

---

## 🚀 Installation & Setup

### Prerequisites

Before you begin, ensure you have the following installed:
- **Node.js** (v14.0.0 or higher)
- **npm** (v6.0.0 or higher) or **yarn**
- **MongoDB** (local installation or MongoDB Atlas account)
- **Git**

### Step-by-Step Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pankajydv07/SkillSwap.git
   cd SkillSwap
   ```
Whether you're offering help or seeking it, every exchange builds trust and community. Grow, connect, and transform—one skill at a time, in a place made for mutual growth.
2. **Install root dependencies**
   ```bash
   npm install
   ```
 
3. **Install server dependencies**
   ```bash
   cd server
   npm install
   cd ..
   ```
 
DEMO Video:https://drive.google.com/file/d/1ZMJxYjxYjjFzmE9jhrMcXIvn_1tA-n-r/view?usp=sharing
4. **Install client dependencies**
   ```bash
   cd client
   npm install
   cd ..
   ```
 
you can view it here too
https://screenrec.com/share/j2eBKHxTR7
5. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```
 
## ✨ Features
6. **Seed the database (optional)**
   ```bash
   npm run seed
   ```
 
### 🔐 Authentication & User Management
- **Secure Authentication**: JWT-based login/signup with email & password
- **User Profiles**: Comprehensive profile management with skills offered/wanted
- **Privacy Controls**: Public/private profile visibility settings
- **Protected Routes**: Secure access control throughout the application
- **Profile Customization**: Update personal information, availability, and location
7. **Run the application**
   ```bash
   npm run dev
   ```
 
### 🏠 Home & Landing Page
- **Dynamic Landing Page**: Engaging hero section with gradient designs
- **Feature Showcase**: Clear presentation of platform capabilities
- **Call-to-Actions**: Strategic CTAs for "Browse Skills", "Start Learning", etc.
- **Responsive Design**: Mobile-first approach with modern UI/UX
- **Platform Overview**: Clear introduction to skill exchange concept
   This will start both the server and client concurrently:
   - Server runs on `http://localhost:5000` (or your configured PORT)
   - Client runs on `http://localhost:3000`
 
### 🔍 Browse & Discovery
- **Advanced Search**: Search by skill name, category, or keywords
- **Smart Filters**: Filter by availability, experience level, and user type
- **User Cards**: Clean, informative user profile cards with key details
- **Skill Matching**: Intelligent matching between offered and wanted skills
- **Real-time Updates**: Live availability and status updates
- **Pagination**: Efficient browsing through large user databases
---
 
### 👤 User Dashboard & Profiles
- **Personal Dashboard**: Overview of user's skills, requests, and activity
- **Skill Management**: Add, edit, and organize skills offered and wanted
- **Skill Categories**: Organized skill categorization system
- **Availability Settings**: Configure when you're available for skill exchanges
- **Location Services**: Location-based skill matching and suggestions
## 🔐 Environment Variables
 
### 🔄 Skill Swap Requests
- **Request Management**: Send, receive, and manage skill swap requests
- **Request Details**: Comprehensive request forms with messaging
- **Status Tracking**: Track request states (pending, accepted, rejected, completed)
- **Scheduled Sessions**: Date and time scheduling for skill exchanges
- **Request History**: Complete history of all swap requests and their outcomes
- **Feedback System**: Rate and review completed skill exchanges
Create a `.env` file in the root directory and add the following variables:
 
### 📊 Admin Panel & Management
- **Admin Dashboard**: Comprehensive analytics and platform statistics
- **User Management**: Admin tools for user moderation and management
-
```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Database
MONGO_URI=mongodb://localhost:27017/skillswap
# Or use MongoDB Atlas: mongodb+srv://<username>:<password>@cluster.mongodb.net/skillswap

# JWT Secret
JWT_SECRET=your_super_secret_jwt_key_here
JWT_EXPIRE=7d

# Email Configuration (Optional - for notifications)
EMAIL_SERVICE=gmail
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password

# Client URL (for CORS)
CLIENT_URL=http://localhost:3000
```

> ⚠️ **Important**: Never commit your `.env` file to version control. It's already included in `.gitignore`.

---

## 📁 Project Structure

```
SkillSwap/
├── 📁 client/                 # React Frontend
│   ├── 📁 public/             # Static assets
│   ├── 📁 src/
│   │   ├── 📁 components/     # Reusable UI components
│   │   ├── 📁 pages/          # Page components
│   │   ├── 📁 context/        # React context (Auth, etc.)
│   │   ├── 📁 hooks/          # Custom React hooks
│   │   ├── 📁 services/       # API service functions
│   │   ├── 📁 utils/          # Utility functions
│   │   ├── App.jsx            # Main App component
│   │   └── index.js           # Entry point
│   └── package.json
│
├── 📁 server/                 # Node.js/Express Backend
│   ├── 📁 config/             # Database configuration
│   ├── 📁 controllers/        # Route controllers
│   ├── 📁 middleware/         # Custom middleware (auth, error handling)
│   ├── 📁 models/             # Mongoose models
│   ├── 📁 routes/             # API routes
│   ├── 📁 utils/              # Utility functions
│   ├── 📁 seed/               # Database seeding files
│   ├── server.js              # Entry point
│   └── package.json
│
├── 📄 .env.example            # Environment variables template
├── 📄 .gitignore              # Git ignore rules
├── 📄 package.json            # Root package.json
└── 📄 README.md               # Project documentation
```

---

## 📖 Usage

### Getting Started

1. **Register an Account**
   - Visit `http://localhost:3000`
   - Click "Sign Up" and create your profile
   - Verify your email (if email service is configured)

2. **Complete Your Profile**
   - Add skills you can offer (e.g., "JavaScript", "Guitar", "Cooking")
   - Add skills you want to learn
   - Set your availability and location
   - Upload a profile picture

3. **Browse Skills**
   - Use the search bar to find specific skills
   - Apply filters to narrow down results
   - View user profiles to learn more about potential swap partners

4. **Request a Swap**
   - Click "Request Swap" on a user's profile
   - Select which skills you want to exchange
   - Propose dates and times
   - Add a personalized message

5. **Manage Requests**
   - View incoming requests in your dashboard
   - Accept, decline, or negotiate swap terms
   - Track the status of your sent requests

### Admin Features

1. Access the admin panel at `http://localhost:3000/admin`
2. View platform analytics and user statistics
3. Manage user accounts and moderate content
4. Monitor reported issues and resolve disputes

---

## 📸 Screenshots

### Demo Videos
🎥 **[Watch Full Demo](https://drive.google.com/file/d/1ZMJxYjxYjjFzmE9jhrMcXIvn_1tA-n-r/view?usp=sharing)**

🎥 **[Alternative Demo Link](https://screenrec.com/share/j2eBKHxTR7)**

### Key Features Preview

*Screenshots coming soon - add images to `/screenshots` folder and update links*

| Feature | Preview |
|---------|---------|
| Landing Page | ![Landing](screenshots/landing.png) |
| Browse Skills | ![Browse](screenshots/browse.png) |
| User Dashboard | ![Dashboard](screenshots/dashboard.png) |
| Swap Requests | ![Requests](screenshots/requests.png) |
| Admin Panel | ![Admin](screenshots/admin.png) |

---

## 📚 API Documentation

### Base URL
```
Development: http://localhost:5000/api
Production: https://your-domain.com/api
```

### Authentication Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/register` | Register new user |
| POST | `/auth/login` | Login user |
| GET | `/auth/me` | Get current user |
| PUT | `/auth/profile` | Update profile |

### User Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/users` | Get all users |
| GET | `/users/:id` | Get user by ID |
| GET | `/users/search` | Search users by skill |
| PUT | `/users/:id` | Update user |
| DELETE | `/users/:id` | Delete user |

### Skill Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/skills` | Get all skills |
| POST | `/skills` | Add new skill |
| PUT | `/skills/:id` | Update skill |
| DELETE | `/skills/:id` | Delete skill |

### Swap Request Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/requests` | Get user requests |
| POST | `/requests` | Create request |
| PUT | `/requests/:id` | Update request status |
| DELETE | `/requests/:id` | Cancel request |

> 📖 **Full API documentation** available at `/api/docs` when running in development mode.

---

## 🤝 Contributing

We welcome contributions! Please follow these guidelines:

### Getting Started
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Branch Naming Conventions
- `feature/description` - New features
- `bugfix/description` - Bug fixes
- `hotfix/description` - Critical fixes
- `docs/description` - Documentation updates
- `refactor/description` - Code refactoring

### Code Style Guidelines
- Follow ESLint configuration
- Use meaningful variable names
- Comment complex logic
- Write tests for new features
- Ensure all tests pass before submitting PR

### Pull Request Process
1. Update the README.md with details of changes if applicable
2. Ensure your code follows the existing code style
3. Include relevant test cases
4. Request review from maintainers
5. Address feedback promptly

---

## 🛠️ Troubleshooting

### Common Issues

#### CORS Errors
**Problem**: `Access-Control-Allow-Origin` errors in browser console
**Solution**: 
- Ensure `CLIENT_URL` in server `.env` matches your frontend URL
- Check that CORS middleware is properly configured in server

#### Database Connection Issues
**Problem**: `MongoNetworkError` or connection timeout
**Solution**:
- Verify MongoDB is running locally or check Atlas connection string
- Ensure IP whitelist includes your current IP (for Atlas)
- Check network connectivity

#### Port Already in Use
**Problem**: `EADDRINUSE: Port 5000/3000 already in use`
**Solution**:
```bash
# Find and kill process on port 5000 (macOS/Linux)

# Or change ports in .env file
PORT=5001
```

#### JWT Authentication Errors
**Problem**: `Invalid token` or `Unauthorized` errors
**Solution**:
- Ensure `JWT_SECRET` is set in server `.env`
- Clear browser localStorage and login again
- Check token expiration settings

#### npm install fails
**Problem**: Dependency installation errors
**Solution**:
```bash
# Clear npm cache
npm cache clean --force

# Delete node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

### Still Having Issues?
- Check [Issues](https://github.com/pankajydv07/SkillSwap/issues) for similar problems
- Create a new issue with detailed error logs
- Contact maintainers (see Contact section)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Pankaj Yadav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👥 Contact & Acknowledgments

### Author

**Pankaj Yadav**
- GitHub: [@pankajydv07](https://github.com/pankajydv07)
- LinkedIn: [Pankaj Yadav](https://linkedin.com/in/pankajydv07)
- Email: pankajydv07@gmail.com

### Acknowledgments

- [React](https://reactjs.org/) - Frontend library
- [Express](https://expressjs.com/) - Backend framework
- [MongoDB](https://www.mongodb.com/) - Database
- [Mongoose](https://mongoosejs.com/) - ODM library
- [JWT](https://jwt.io/) - Authentication
- [Node.js](https://nodejs.org/) - Runtime environment

### Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

---

<p align="center">Made with ❤️ by Pankaj Yadav</p>

<p align="center">
  <a href="https://github.com/pankajydv07/SkillSwap">GitHub</a> •
  <a href="#-installation--setup">Documentation</a> •
  <a href="#-contributing">Contribute</a>
</p>
