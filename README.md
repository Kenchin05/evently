# Event Platform

A modern event management platform built with Next.js 14, enabling seamless event creation and management with robust authentication.

## 🚀 Features

- User authentication and authorization
- Event creation and management
- File upload capabilities
- Responsive design
- Server-side rendering
- Modern UI components

## 🛠️ Tech Stack

- **Framework:** Next.js 14
- **Styling:** Tailwind CSS
- **Authentication:** Clerk
- **File Storage:** UploadThing
- **Database:** MongoDB
- **UI Components:** shadcn/ui

## 📁 Project Structure

```bash
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication related routes
│   ├── (root)/            # Main application routes
│   └── api/               # API routes
├── components/            # React components
│   ├── shared/           # Shared components
│   └── ui/               # UI components
├── lib/                   # Utility functions
│   ├── actions/          # Server actions
│   ├── database/         # Database configs
│   └── utils.ts          # Helper functions
└── public/               # Static assets
```

## 🚀 Quick Start

1. **Clone and Install**
```bash
git clone https://github.com/Kenchin05/evently.git
cd evently
npm install
```

2. **Set Environment Variables**
Create `.env.local`:
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
MONGODB_URI=your_mongodb_connection_string
```

3. **Setup Services**

- **MongoDB Database:**
  - Create database in MongoDB Atlas
  - Add connection string to `.env.local`
  - Whitelist your IP address

- **Clerk Authentication:**
  - Create account at [Clerk](https://clerk.dev)
  - Set up new application
  - Add Clerk keys to `.env.local`

4. **Launch Application**
```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000)

## 📋 Available Scripts

```bash
# Development
npm run dev

# Production Build
npm run build

# Production Start
npm start

# Code Linting
npm run lint
```