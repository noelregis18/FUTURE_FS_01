# Internship Projects Collection

This repository contains three distinct web application projects developed during an internship program. Each project demonstrates different aspects of modern web development using React, TypeScript, and various supporting technologies.

## Table of Contents

- [Portfolio Website](#portfolio-website)
- [Rebranding Project](#rebranding-project)
- [Weather Dashboard](#weather-dashboard)
- [Common Technologies](#common-technologies)
- [Setup Instructions](#setup-instructions)

## Portfolio Website

A personal portfolio website showcasing professional skills, projects, and contact information.

Live Link - https://noelregis-noel-regis-projects.vercel.app/

### Features

- Responsive design with modern UI
- Interactive sections: Hero, About, Skills, Projects, and Contact
- Theme switching capability
- Chat assistant for visitor interaction
- Smooth scrolling navigation

### Key Components

- Dynamic hero section with real-time date and time display
- Skills showcase with categorized technical abilities
- Projects gallery with detailed descriptions
- Contact form for professional inquiries

## Rebranding Project

A product showcase website for a technology company's rebranding initiative, highlighting their new product line and brand identity.

Live Link - https://rebranding-delta.vercel.app/

### Features

- Animated UI elements using Framer Motion
- Dark mode as default with theme switching
- Smooth scroll implementation for navigation
- Responsive design for all device sizes
- Product showcase with detailed information

### Key Components

- Animated hero section with brand tagline
- About section describing the rebranding initiative
- Products section showcasing the new product line
- Contact section for customer inquiries
- Supabase integration for backend functionality

## Weather Dashboard

An interactive weather application that provides current weather conditions and forecasts for locations worldwide.

Live Link - https://weather-dashboard18.vercel.app/

### Features

- Current weather conditions display
- Multi-day weather forecast
- Location-based weather detection
- City search functionality
- Favorite cities management
- Theme toggle between light and dark modes

### Key Components

- Weather data fetching and display
- City search with autocomplete
- Favorite cities management system
- Responsive design for all device sizes
- Supabase integration for user data storage

## Common Technologies

All three projects share a common technology stack:

- **React**: Frontend library for building user interfaces
- **TypeScript**: Static typing for JavaScript
- **Vite**: Next-generation frontend tooling
- **Tailwind CSS**: Utility-first CSS framework
- **Shadcn UI**: Component library built on Radix UI
- **React Router**: Navigation and routing
- **React Query**: Data fetching and state management
- **Lucide React**: Icon library

Additional technologies used in specific projects:

- **Framer Motion**: Animation library (Rebranding Project)
- **Supabase**: Backend-as-a-Service (Weather Dashboard, Rebranding Project)

## Setup Instructions

Each project follows the same setup process:

1. Navigate to the project directory:
   ```bash
   cd [Project Directory]
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. Preview the production build:
   ```bash
   npm run preview
   ```

## Project Structure

Each project follows a similar structure:

```
├── public/              # Static assets
├── src/                 # Source code
│   ├── components/      # UI components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utility functions and libraries
│   ├── pages/           # Page components
│   ├── App.tsx          # Main application component
│   └── main.tsx         # Application entry point
├── .gitignore           # Git ignore file
├── index.html           # HTML entry point
├── package.json         # Project dependencies and scripts
├── tailwind.config.ts   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

---

These projects demonstrate proficiency in modern web development practices, including responsive design, component-based architecture, state management, and integration with third-party services.
