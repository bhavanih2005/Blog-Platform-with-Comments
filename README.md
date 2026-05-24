# Blog Platform with Comments

A full-stack blogging platform that allows users to create, edit, and manage blog posts while interacting through comments. The application includes user authentication, RESTful APIs, database integration, and responsive design for a seamless blogging experience.

---

## Features

- User Registration & Login
- Authentication & Authorization
- Create, Edit, and Delete Blog Posts
- Comment System for User Interaction
- RESTful Backend APIs
- Database Integration
- Responsive Design for Mobile & Desktop

---

## Tech Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
Choose any one:
- MongoDB
- MySQL
- PostgreSQL

### Authentication
- JWT (JSON Web Token)
- bcrypt.js

---

## Project Structure

```bash
blog-platform/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
└── package.json
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/blog-platform.git
```

### Navigate to Project Directory

```bash
cd blog-platform
```

---

## Backend Setup

```bash
cd server
npm install
```

### Create `.env` File

```env
PORT=5000
DB_URI=your_database_connection
JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm start
```

---

## Frontend Setup

```bash
cd client
npm install
npm start
```

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register User |
| POST | `/api/auth/login` | Login User |

### Blog Posts

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/posts` | Get All Posts |
| POST | `/api/posts` | Create New Post |
| PUT | `/api/posts/:id` | Update Post |
| DELETE | `/api/posts/:id` | Delete Post |

### Comments

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/comments` | Add Comment |
| GET | `/api/comments/:postId` | Get Post Comments |
| DELETE | `/api/comments/:id` | Delete Comment |

---

## Core Functionalities

- User Signup & Login
- Create Blog Posts
- Edit & Delete Posts
- Add & Manage Comments
- View All Blogs
- User Interaction System

---

## Responsive Design

The application is optimized for:

- Desktop Devices
- Tablets
- Mobile Phones

---

## Learning Outcomes

Through this project, you will learn:

- Full-Stack Web Development
- RESTful API Development
- Authentication & Authorization
- Database Management
- Frontend-Backend Integration
- Dynamic Content Handling
- User Interaction Features
- Content Management Systems

---

## Future Enhancements

- Rich Text Editor
- Blog Categories & Tags
- User Profiles
- Like & Share Features
- Search & Filter Blogs
- Email Notifications
- Admin Dashboard

---

## Author

Bhavani H

---

## License

This project is licensed under the MIT License.
