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