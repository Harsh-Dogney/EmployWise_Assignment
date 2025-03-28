# 🚀 User Management Dashboard

![React](https://img.shields.io/badge/React-18.3.1-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-3178C6?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?logo=tailwind-css)
![Vite](https://img.shields.io/badge/Vite-5.4.2-646CFF?logo=vite)

A modern, responsive user management dashboard built with React, TypeScript, and Tailwind CSS. This application provides a beautiful interface for managing users with features like authentication, user listing, editing, and deletion.

![Dashboard Preview](https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?w=1200&auto=format&fit=crop&q=80)

## ✨ Features

- 🔐 **Secure Authentication**
  - JWT-based authentication
  - Protected routes
  - Persistent login state

- 👥 **User Management**
  - View all users in a responsive grid layout
  - Edit user information
  - Delete users
  - Pagination support

- 🎨 **Modern UI/UX**
  - Clean and intuitive interface
  - Responsive design for all devices
  - Dark/Light theme support
  - Beautiful transitions and animations
  - Toast notifications for feedback

- 🔍 **Advanced Features**
  - Real-time search functionality
  - Client-side filtering
  - Error handling
  - Loading states

## 🛠️ Technology Stack

- **Frontend Framework**: React 18.3.1
- **Language**: TypeScript 5.5.3
- **Styling**: Tailwind CSS 3.4.1
- **Build Tool**: Vite 5.4.2
- **HTTP Client**: Axios
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **Notifications**: React Hot Toast
- 
## 🔑 Authentication

The application uses the [ReqRes API](https://reqres.in/) for authentication. Use the following credentials to log in:

- **Email**: eve.holt@reqres.in
- **Password**: cityslicka

## 📱 Pages and Features

### Login Page
- Email and password authentication
- Form validation
- Error handling
- Theme toggle
- Persistent login state

### User List
- Responsive grid layout
- User cards with avatars
- Search functionality
- Pagination
- Delete confirmation
- Theme toggle
- Logout functionality

### Edit User
- Pre-filled form with user data
- Form validation
- Success/Error notifications
- Back navigation
- Theme persistence

## 🎨 Theme Support

The application supports both light and dark themes:

- 🌞 **Light Theme**: Clean, professional look with white background
- 🌙 **Dark Theme**: Eye-friendly dark mode with proper contrast

Theme preference is persisted in local storage and syncs with system preferences.

## 🔒 Security Features

- Protected routes using React Router
- JWT token storage in localStorage
- Automatic redirect to login for unauthorized access
- API error handling

## 📱 Responsive Design

The dashboard is fully responsive and works seamlessly across:
- 💻 Desktop computers
- 💪 Tablets
- 📱 Mobile devices
