<div align="center">

# 🏨 **HostelHub**

### _Social Hostel Booking & Experience Feed_

[![Language](https://img.shields.io/badge/Language-Web-blueviolet)]()
[![Platform](https://img.shields.io/badge/Platform-Web-green?logo=html5)]()
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)]()
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)]()

💻 _Final Project (TFG) – ILERNA | Development of Multiplatform Applications (DAM)_  
👨‍💻 **Author:** Israel Quiroz de Zaldo

</div>

---

## 🧠 **Overview**

**HostelHub** is a web/mobile application designed to **connect travelers** and enhance their experience by combining **hostel bookings, social interaction, and a personal experience feed**. The platform allows users to search and book hostels, view locations on maps, and explore posts from other travelers such as including photos, place descriptions, and ratings.

Users can voluntarily share their stay at hostels, creating a **community environment**, and participate in group experiences or organized activities. The main innovation of the project lies in integrating a **social feed within a booking platform**, where users can post travel recommendations and receive additional information through automated systems, such as AI, without overloading content creators.

---

## 🎯 **Main Objectives**

- ✅ Facilitate hostel bookings with real-time availability.
- ✅ Provide a social feed for sharing travel experiences.
- ✅ Implement AI-assisted responses for user queries.
- ✅ Ensure a modular and scalable architecture.

---

## ⚙️ **Key Features**

| Feature                        | Description                                                             |
| ------------------------------ | ----------------------------------------------------------------------- |
| 🏨 **Hostel Search & Booking** | Search and reserve hostels with interactive maps.                       |
| 📍 **Location Map**            | Visualize hostels’ locations and explore nearby areas.                  |
| 📝 **Experience Feed**         | Post travel experiences with optional photos, description, and ratings. |
| 🌐 **Community Sharing**       | Share voluntary stays and join group experiences.                       |
| 🤖 **AI Assistant**            | Ask questions related to posts and get automated answers.               |

---

## 🧩 **Architecture**

### 🏛️ System Architecture Overview

HostelHub is built using a **modular, scalable, and service-oriented architecture** that supports hostel bookings, social features, and AI-assisted interactions.  
The system is divided into three main layers:

#### **1. Frontend (Client Application)**

The frontend is a responsive web application developed with a **mobile-first** approach.  
It communicates with the backend through RESTful API endpoints.

**Responsibilities:**

- User authentication
- Hostel browsing & filters
- Hostel detail view (gallery, map, services)
- Booking interactions
- Interactive map visualization
- Social feed of user posts
- Post creation (photo optional)
- AI-powered question modal
- User profile & statistics
- Other-user profile view

#### **2. Backend (API Layer)**

The backend exposes a REST API and handles all critical application logic.

**Responsibilities:**

- User registration & JWT authentication
- Hostel search, filters, and availability
- Booking management
- Feed retrieval, ratings, and post creation
- AI Assistant endpoint (OpenAI integration)
- Request validation & business rules
- Database communication
- Security (password hashing, session handling)

#### **3. Database Layer**

A document-oriented database stores dynamic and flexible structures such as users, hostels, posts, and bookings.

**Main collections:**

- `users` — profiles, preferences, optional traveler info
- `hostels` — name, address, photos, amenities, location
- `posts` — text, optional image, rating, location, creator
- `bookings` — dates, guests, hostel reference
- `chats` _(future feature)_ — group messages per hostel/event

Sensitive data (passwords, tokens) is securely encrypted.

#### **4. External Services**

HostelHub integrates multiple third-party services for enhanced functionality:

- **Mapbox API** → map rendering & geolocation
- **OpenAI API** → AI-generated answers for user questions
- **Cloud Storage (Cloudinary / Firebase Storage)** → image hosting (optional)

---

## 🛠️ **Technologies Used**

### **Frontend**

- **React** — Component-based UI
- **TypeScript** — Type safety & clean architecture
- **Vite** — Fast bundling & dev server
- **TailwindCSS** — Utility-first styling
- **React Router** — Client-side routing
- **React Query (TanStack Query)** — API state management
- **Framer Motion** _(optional)_ — Animations

### **Backend**

- **Node.js** — Runtime
- **Express.js** — REST API framework
- **TypeScript** — Typed backend logic
- **JWT** — Authentication & session handling
- **bcrypt** — Password hashing
- **Zod / Joi** — Input validation
- **Helmet + CORS** — Security middleware

### **Database**

- **MongoDB Atlas** — Cloud NoSQL database
- **Mongoose** — ODM for schemas & models

### **External Integrations**

- **Mapbox API** — Maps & location data
- **OpenAI API** — AI Assistant responses
- **Cloudinary / Firebase Storage** — Optional image hosting

### **Deployment & DevOps**

- **Vercel / Netlify** — Frontend hosting with CI/CD
- **Render / Railway / Fly.io** — Backend hosting
- **MongoDB Atlas** — Cloud database
- **GitHub** — Version control & project management
- **Postman / Insomnia** — API testing

---

## ...

## 🗂️ **Project Structure**

## ...

## 🚧 **Project Status**

> 🛠️ _Currently under development – academic version (TFG)_
>
> > Core modules (hostel booking, experience feed) are implemented; AI-assisted responses are planned for integration.

---

## ⚖️ **Legal Notice**

© 2025 **Israel Quiroz de Zaldo**  
**All rights reserved.**

This project is part of a **Final Project (TFG)** for the **Multiplatform Application Development (DAM)** program at **ILERNA**.  
The code, design, and documentation associated with this project **may not be distributed, copied, or used commercially** without the explicit permission of the author.

---

## 📫 **Contact**

📧 **Email:** [isra_quirozz@hotmail.com]  
🌐 **GitHub:** [https://github.com/IsraQuirozZ](https://github.com/IsraQuirozZ)
📍 **Location:** Madrid, Spain

---

<div align="center">
  
🧠 *Developed with dedication and curiosity by Israel Quiroz de Zaldo*  
💡 *StaffSync — connecting teams through technology.*

</div>
