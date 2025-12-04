# React Projects Collection 🚀

This repository contains two React projects built with Vite, demonstrating different aspects of React development.

> **Note:** These projects showcase modern React development practices and patterns for building interactive web applications.

## Projects Overview

### 1. Netflix Clone
A Netflix-inspired streaming platform interface built with React.

**Location:** `Netflix Clone youtube/`

**Features:**
- Responsive navigation bar
- Dynamic banner component
- Content rows with poster displays
- Movie/show data management
- Netflix-style UI components

**Key Components:**
- `Banner` - Hero section with featured content
- `Navbar` - Top navigation bar
- `Row` - Horizontal scrolling content rows
- `Posters` - Individual movie/show poster cards
- `Content` - Main content container

**Tech Stack:**
- React
- Vite
- ESLint

---

### 2. React Crash Course
A comprehensive learning project covering fundamental React concepts and patterns.

**Location:** `React_Crash_Course/`

**Topics Covered:**
- **State Management** - Counter component with useState
- **API Integration** - Fetching and displaying external data
- **List Rendering** - Map operations and data iteration
- **Form Handling** - User input and form submission
- **Filtering** - Data filtering and search functionality
- **Side Effects** - useEffect hook demonstrations
- **Conditional Rendering** - Dynamic component rendering
- **Routing** - Multi-page navigation setup

**Components:**
- `Counter.jsx` - State management example
- `FetchDataFromAPI.jsx` - API data fetching
- `Map.jsx` - Array rendering patterns
- `HandleForm.jsx` - Form handling
- `Filter.jsx` - Search and filter functionality
- `UseEffect.jsx` - Side effects and lifecycle
- `Render.jsx` - Conditional rendering
- `Person.jsx` - Reusable component example
- `Mobile.jsx` - Mobile-specific component
- `Navbar.jsx` - Navigation component

**Pages:**
- `Home.jsx` - Landing page
- `About.jsx` - About page
- `Team.jsx` - Team page
- `Contact.jsx` - Contact page

**Tech Stack:**
- React
- Vite
- React Router (for navigation)
- ESLint

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

#### Netflix Clone
```bash
cd "Netflix Clone youtube"
npm install
npm run dev
```

#### React Crash Course
```bash
cd React_Crash_Course
npm install
npm run dev
```

## Development

Both projects use Vite as the build tool for fast development and optimized production builds.

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## Project Structure

Each project follows a standard Vite + React structure:
```
project/
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable components
│   ├── pages/       # Page components (Crash Course only)
│   ├── App.jsx      # Main app component
│   ├── main.jsx     # Application entry point
│   └── index.css    # Global styles
├── index.html       # HTML template
├── package.json     # Dependencies and scripts
├── vite.config.js   # Vite configuration
└── eslint.config.js # ESLint configuration
```

## Learning Resources

The React Crash Course project is ideal for:
- React beginners learning core concepts
- Understanding hooks (useState, useEffect)
- Practicing component composition
- Learning routing and navigation
- Working with APIs and external data

The Netflix Clone project demonstrates:
- Building real-world UI components
- Responsive design patterns
- Content organization and display
- Modern React application structure

## License

This is a personal learning repository.

## Author

Rahul

---

**Last Updated:** December 2025
