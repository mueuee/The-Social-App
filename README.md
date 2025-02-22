# Social App

Welcome to **Social App** – a full-stack social media platform designed to inspire connection and creativity. Built with modern technologies, this project offers a feature-rich experience where users can share moments, engage with content, and connect seamlessly. Whether you're here to explore, contribute, or simply experience a social network built with care, you're in the right place.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## Introduction

**Social App** reimagines social networking with a sleek, modern design and robust functionality. From secure authentication to real-time interactions, this platform combines the best of **Next.js**, **Prisma**, and **Clerk** to deliver a polished experience. Whether you're sharing thoughts, liking posts, or exploring profiles, every interaction feels intuitive and fluid.

This project isn’t just an app—it’s a learning journey into full-stack development, database optimization, and responsive design. Dive in to see how a social platform comes to life, one line of code at a time.

---

## Features

- **Secure Authentication:** Sign up/in with Google or email.
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

## Installation

Follow these steps to run Social App locally:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/social-app.git
    cd social-app
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**
    Create a `.env` file with the following content:
    ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
    CLERK_SECRET_KEY=your_clerk_secret
    DATABASE_URL=your_neon_db_url
    UPLOADTHING_SECRET=your_uploadthing_secret
    UPLOADTHING_APP_ID=your_uploadthing_app_id
    ```

4. **Database Setup:**
    ```bash
    npx prisma generate
    npx prisma db push
    ```

5. **Start the Development Server:**
    ```bash
    npm run dev
    ```

6. **Visit the App:**
    Open [http://localhost:3000](http://localhost:3000) in your browser to explore!

---

## Usage

- **Sign Up/In:** Use Google or email verification.
- **Create Posts:** Share text or images via the homepage.
- **Engage:** Like, comment, and follow users.
- **Customize Profile:** Update your bio, location, and profile picture.
- **Explore:** Discover suggested users and trending posts.
- **Notifications:** Check real-time alerts in the bell icon.

---

## Contributing

Your contributions help Social App grow! Here’s how to get involved:

1. **Fork the Repository:**
    Click the “Fork” button on GitHub.

2. **Create a Feature Branch:**
    ```bash
    git checkout -b feature/your-feature
    ```

3. **Commit Changes:**
    ```bash
    git commit -m "Add your meaningful message"
    ```

4. **Push to Your Branch:**
    ```bash
    git push origin feature/your-feature
    ```

5. **Open a Pull Request:**
    Provide a detailed description of your changes and their impact.

---

## License

Distributed under the MIT License.

---

## Acknowledgements

- **Clerk & Neon:** For seamless auth and database solutions.
- **Shadcn UI:** For beautiful, accessible components.
- **Next.js Community:** For endless inspiration.
- **You:** For exploring this project!
