# Social App

Welcome to **Social App** – a full-stack social media platform designed to inspire connection and creativity. Built with modern technologies, this project offers a feature-rich experience where users can share moments, engage with content, and connect seamlessly. Whether you're here to explore, contribute, or simply experience a social network built with care, you're in the right place.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation, Database Setup & Usage](#installation-database-setup--usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Introduction

Social App reimagines social networking with a sleek, modern design and robust functionality. From secure authentication to real-time interactions, this platform combines the best of Next.js, Prisma, and Clerk to deliver a polished experience. Whether you're sharing thoughts, liking posts, or exploring profiles, every interaction feels intuitive and fluid.

This project isn’t just an app—it’s a learning journey into full-stack development, database optimization, and responsive design. Dive in to see how a social platform comes to life, one line of code at a time.

---

## Features

- **Secure Authentication:** Sign up/in with Google or email (6-digit OTP verification).
- **Rich Posts:** Create text-based content with image uploads.
- **Engagement:** Like, comment, and receive real-time notifications.
- **Dynamic Profiles:** Customize profiles with bios, locations, and websites.
- **Notifications:** Instant alerts for follows, likes, and comments.
- **Dark/Light Mode:** Smooth theme switching for eye comfort.
- **Responsive Design:** Flawless experience on all devices.
- **Social Features:** Follow users, explore suggestions, and delete posts.

---

## Technologies Used

- **Frontend:** Next.js 14, Tailwind CSS, Shadcn UI
- **Authentication:** Clerk
- **Database:** PostgreSQL (Neon Serverless), Prisma ORM
- **Storage:** UploadThing (Image Uploads)
- **Deployment:** Vercel
- **Utilities:** React Hot Toast, date-fns, Lucide Icons

---

## Installation, Database Setup & Usage

Run all the following commands in your terminal:

```bash
# Clone the Repository
git clone https://github.com/your-username/social-app.git
cd social-app

# Install Dependencies
npm install

# Set up Environment Variables
# Create a .env file in the root directory with the following content:
# NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
# CLERK_SECRET_KEY=your_clerk_secret
# DATABASE_URL=your_neon_db_url
# UPLOADTHING_SECRET=your_uploadthing_secret
# UPLOADTHING_APP_ID=your_uploadthing_app_id

# Generate Prisma Client and Push Database Schema
npx prisma generate
npx prisma db push

# Start the Development Server
npm run dev



