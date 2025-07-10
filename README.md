# Yelp-Camp
# 🌲 YelpCamp - Campground Review Platform

[![Node.js](https://img.shields.io/badge/Node.js-14.x%2B-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-blue)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4.x-green)](https://www.mongodb.com/)

YelpCamp is a full-stack web application where users can discover, review, and manage campgrounds. Built as part of a web development learning journey, this project demonstrates core backend and frontend concepts in a real-world application.

## ✨ Features

- **User Authentication**
  - Secure registration/login with Passport.js
  - Password hashing with bcrypt
  - Authorization middleware for protected routes

- **Campground Management**
  - Create, read, update, and delete campgrounds
  - Image upload and display
  - Location data with GeoJSON

- **Reviews System**
  - Add and manage reviews
  - Star rating system
  - User-specific review permissions

- **Responsive Design**
  - Mobile-friendly interface
  - Clean UI with Bootstrap 5
  - Dynamic content with EJS templates

## 🛠 Tech Stack

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose ODM)
- Passport.js (for authentication)

**Frontend:**
- EJS (Embedded JavaScript templates)
- Bootstrap 5
- Vanilla JavaScript

**Other Tools:**
- Mapbox (for geolocation features)
- Cloudinary (for image storage)
- Heroku (for deployment)

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas cluster)
- Cloudinary account (for image uploads)
- Mapbox account (for maps)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/swapnildatta/YelpCamp.git
   cd YelpCamp
