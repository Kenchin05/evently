# Event Platform

A modern event management platform built with Next.js 14, featuring authentication, event creation, and management capabilities.

## Tech Stack

- **Framework:** Next.js 14
- **Styling:** Tailwind CSS
- **Authentication:** Clerk
- **File Storage:** UploadThing
- **Database:** (Not visible in current context)
- **Components:** Reusable UI components with shadcn/ui

## Project Structure

```bash
├── app/                    # Next.js app directory
│   ├── (auth)/            # Authentication related routes
│   ├── (root)/            # Main application routes
│   └── api/               # API routes
├── components/            # React components
│   ├── shared/           # Shared components
│   └── ui/               # UI components
├── lib/                   # Utility functions and libraries
│   ├── actions/          # Server actions
│   ├── database/         # Database configurations
│   └── utils.ts          # Helper functions
└── public/               # Static assets

# Event Platform

...existing code...

## Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/Kenchin05/evently.git
cd evently
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Variables**
Create a `.env.local` file in the root directory with the following variables:
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
MONGODB_URI=your_mongodb_connection_string
```

4. **Setup Database**
- Create a MongoDB database
- Add your connection string to `.env.local`
- Make sure your IP address is whitelisted in MongoDB Atlas

5. **Setup Clerk Authentication**
- Create a Clerk account at https://clerk.dev
- Create a new application
- Add your Clerk keys to `.env.local`

6. **Run the development server**
```bash
npm run dev
```

7. **Open your browser**
Navigate to [http://localhost:3000](http://localhost:3000)

## Available Scripts

- **Development server**
```bash
npm run dev
```

- **Build for production**
```bash
npm run build
```

- **Start production server**
```bash
npm start
```

- **Lint code**
```bash
npm run lint
```