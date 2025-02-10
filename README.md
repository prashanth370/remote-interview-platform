#                                ✨ Video Calling Interview Platform ✨
A feature-rich **Remote Interview Platform** built with **Next.js & TypeScript** that enables seamless **video calls, screen sharing, and screen recording**. This platform is powered by **Stream**, **Convex**, and **Clerk**, ensuring smooth real-time communication and secure authentication.

## Login Page
![image](https://github.com/user-attachments/assets/ea81e98c-ed54-4b17-9c04-91bdaf90f574)

## Dashboard Page
![image](https://github.com/user-attachments/assets/15b395a3-1da7-464e-b0a2-883e3bdd14a8)


🚀 Overview

The Remote Interview Platform is a modern web application built using Next.js and TypeScript. It provides a seamless virtual interview experience with real-time video calls, screen sharing, and screen recording functionalities. This project leverages Stream, Convex, and Clerk for authentication, real-time data handling, and media services.

## 📌 Features

**🎥Video Calls**  – Conduct real-time interviews with video conferencing.

**🖥️ Screen Sharing** – Share your screen for better collaboration.

**🎬 Screen Recording** – Record interview sessions for future reference.

**🔒 Authentication & Authorization** – Secure user authentication using Clerk.

**💻 Server & Client Components** – Optimized performance with Next.js architecture.

**🛣️ Dynamic & Static Routing** – Efficient routing for enhanced UX.

**🎨 Styling with Tailwind & Shadcn** – Beautiful, modern UI design.

**✨ Server Actions** – Handle backend logic seamlessly.

## 🛠️ Tech Stack

**Frontend**: Next.js, TypeScript, Tailwind CSS, Shadcn

**Backend**: Convex (database & real-time state management)

**Authentication**: Clerk, convex

**Video & Media Services**: Stream

**Deployment**: Vercel (recommended)

## 📂 Project Structure

**remote-interview-platform/**
**├── components/          # Reusable UI components**
**├── hooks/               # Custom React hooks**
**├── lib/                 # Utility functions & configurations**
**├── pages/               # Next.js page routes**
**├── public/              # Static assets**
**├── styles/              # Global styles**
**├── app/                 # Next.js App Router (server components)**
**├── convex/              # Convex database schemas**
**├── .env.example         # Example environment variables**
**├── README.md            # Project documentation**
**└── package.json         # Dependencies and scripts**

### 🏗️ Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/prashanth370/remote-interview-platform.git
cd remote-interview-platform

2️⃣ Install Dependencies

npm install

3️⃣ Configure Environment Variables

Create a .env file in the root directory and add the required keys:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=

4️⃣ Run the Development Server

npm run dev

The app will be available at http://localhost:3000.

🚀 Deployment

This project is optimized for deployment on Vercel. To deploy:

Push your code to GitHub.

Link the repository to Vercel.

Add environment variables in Vercel settings.

Deploy with a single click!

🤝 Contributing

Contributions are welcome! Follow these steps:

Fork the repository.

Create a feature branch (git checkout -b feature-branch).

Commit changes (git commit -m 'Add new feature').

Push to GitHub (git push origin feature-branch).

Open a pull request.

📄 License

This project is licensed under the MIT License.

🚀 Built with ❤️ by Banoth Prashanth


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

