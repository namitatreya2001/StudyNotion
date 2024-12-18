# StudyNotion - Ed-Tech Platform

**StudyNotion** is a modern ed-tech platform built using the MERN stack (MongoDB, Express.js, ReactJS, Node.js) to provide a seamless learning experience for students and instructors globally. The platform allows users to create, consume, and rate educational content while providing instructors with tools to manage their courses.

## Features

### For Students
- Course List, Wishlist, Cart Checkout, Course Content, User Details
- Rating and reviewing courses
- Personalized learning experience

### For Instructors
- Course creation, management, and insights
- Dashboard with detailed course metrics
- Profile management

### For Admin (Future Scope)
- Platform-wide metrics
- Instructor and user management

## Tech Stack
- **Front-end**: ReactJS, Redux, TailwindCSS
- **Back-end**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, Bcrypt
- **Cloud Storage**: Cloudinary (media management)
- **Payment Integration**: Razorpay

## Architecture
- **Monolithic Architecture**: Single codebase for both front-end and back-end.
- **API**: RESTful API with CRUD operations for courses, authentication, and more.
- **Hosting**: 
  - Front-end: [Vercel](https://vercel.com)
  - Back-end: [Render](https://render.com) 
  - Database: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
  
## API Endpoints
- **POST** `/api/auth/signup` - User registration
- **POST** `/api/auth/login` - Login & JWT generation
- **GET** `/api/courses` - List all courses
- **POST** `/api/courses` - Create a new course
- **PUT** `/api/courses/:id` - Update course details
- **DELETE** `/api/courses/:id` - Delete course

## Future Enhancements
- **Gamification**: Badges, Points, Leaderboards
- **Personalized Learning Paths**
- **Social Learning Features**: Peer feedback, group discussions
- **Mobile App Development**
- **Machine Learning-powered Recommendations**
- **VR/AR Integrations**

## Deployment
- **Front-end**: Vercel
- **Back-end**: Render 
- **Database**: MongoDB Atlas
- **Media**: Cloudinary

##Live Project Link-https://studynotionfrontend-c25lgpcrt-namit-atreyas-projects.vercel.app/
