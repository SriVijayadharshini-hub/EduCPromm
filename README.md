# EduCPromm - Student Wellbeing & Academic Monitoring

A comprehensive platform for supporting student wellbeing through data-driven insights and mood tracking.

## Project Overview

This application provides tools for:
- Student mood tracking and wellbeing monitoring
- Academic performance analysis
- Smart journaling and note summarization
- Study planning and organization
- Teacher-student communication

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

```sh
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd studybuddy-moodflow-main

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production

```sh
# Build the application
npm run build

# Preview the build
npm run preview
```

## Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS + shadcn/ui
- **Build Tool**: Vite
- **State Management**: React Query
- **Routing**: React Router DOM
- **Forms**: React Hook Form + Zod
- **Charts**: Recharts
- **Icons**: Lucide React

## Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page components
├── contexts/           # React contexts
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── components/ui/      # shadcn/ui components
```

## Development

The application runs on `http://localhost:5173` by default when using `npm run dev`.

## Deployment

This project can be deployed to any static hosting service like:
- Vercel
- Netlify
- GitHub Pages
- AWS S3 + CloudFront

Simply run `npm run build` and deploy the contents of the `dist` folder.
