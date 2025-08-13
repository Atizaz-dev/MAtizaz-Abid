# Portfolio Website Project

## Overview

This is a full-stack developer portfolio website built with React, TypeScript, and Express.js. The project showcases a professional portfolio for Atizaz, a Full Stack Python/Django Developer specializing in AI/ML, web scraping, and automation. The application features a modern, fully responsive design with smooth animations and an interactive user interface built using shadcn/ui components and Tailwind CSS.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development practices
- **Styling**: Tailwind CSS with shadcn/ui component library for consistent, professional UI components
- **Animations**: Framer Motion for smooth scroll animations and interactive elements
- **State Management**: TanStack React Query for server state management and API interactions
- **Routing**: Wouter for lightweight client-side routing
- **Forms**: React Hook Form with Zod validation for robust form handling

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules for modern JavaScript features
- **Build System**: Vite for fast development and optimized production builds
- **Development**: tsx for TypeScript execution in development mode

### Data Storage Solutions
- **Database**: PostgreSQL configured through Drizzle ORM
- **ORM**: Drizzle with PostgreSQL dialect for type-safe database operations
- **Connection**: Neon Database serverless for PostgreSQL hosting
- **Schema Management**: Shared schema definitions between client and server
- **Migrations**: Drizzle Kit for database schema migrations

### Development and Build Tools
- **Bundler**: Vite with React plugin for fast development and production builds
- **Type Checking**: TypeScript with strict mode enabled
- **Code Quality**: ESLint configuration through Vite
- **CSS Processing**: PostCSS with Tailwind CSS and Autoprefixer
- **Development Server**: Hot module replacement and runtime error overlay

### Component Architecture
- **UI Components**: shadcn/ui component system with Radix UI primitives
- **Styling System**: CSS variables for theming with dark mode support
- **Responsive Design**: Mobile-first approach with Tailwind's responsive utilities
- **Component Structure**: Modular components with TypeScript interfaces

## External Dependencies

### UI and Styling
- **@radix-ui/react-***: Complete set of accessible UI primitives for consistent component behavior
- **tailwindcss**: Utility-first CSS framework for rapid UI development
- **class-variance-authority**: Type-safe variant API for component styling
- **lucide-react**: Modern icon library for consistent iconography

### Animation and Interaction
- **framer-motion**: Production-ready motion library for React animations
- **embla-carousel-react**: Lightweight carousel component for image galleries

### Data Management
- **@tanstack/react-query**: Powerful data synchronization for React applications
- **react-hook-form**: Performant forms library with minimal re-renders
- **@hookform/resolvers**: Validation resolvers for React Hook Form
- **zod**: TypeScript-first schema validation for form data

### Database and Backend
- **drizzle-orm**: Lightweight TypeScript ORM for type-safe database operations
- **@neondatabase/serverless**: Serverless PostgreSQL driver for Neon Database
- **drizzle-zod**: Integration between Drizzle ORM and Zod for schema validation

### Development Tools
- **vite**: Fast build tool with hot module replacement
- **@vitejs/plugin-react**: Official Vite plugin for React support
- **tsx**: TypeScript execution engine for Node.js development
- **@replit/vite-plugin-runtime-error-modal**: Development error overlay for Replit environment