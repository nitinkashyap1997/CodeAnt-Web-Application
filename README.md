# CodeAnt-Web-Application

# CodeAnt - AI-Powered Code Review Platform

CodeAnt is a modern web application that helps developers manage repositories, perform AI-powered code reviews, and maintain cloud security standards.

## Features

- **User Authentication**: Secure login system
- **Repository Management**: View and manage your code repositories
- **AI Code Review**: Automated code analysis and suggestions (coming soon)
- **Cloud Security**: Monitor and maintain security standards (coming soon)
- **Interactive Guide**: Documentation and best practices (coming soon)

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

### Installation



1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

```bash
npm run build
```

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── auth/          # Authentication components
│   ├── layout/        # Layout components
│   ├── repository/    # Repository-related components
│   └── ui/            # Basic UI components
├── pages/             # Page components
├── types/             # TypeScript type definitions
└── utils/             # Utility functions
```

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- React Router
- Lucide Icons

## Usage Guide

1. **Login**
   - Access the application through the login page
   - Enter your email and password
   - Click "Sign in" to access the dashboard

2. **Repository Management**
   - View all repositories on the main dashboard
   - Click "New Repository" to create a new repository
   - Each repository shows:
     - Name
     - Description
     - Programming language
     - Star count
     - Last update date

3. **Navigation**
   - Use the sidebar to access different sections:
     - Repositories
     - AI Code Review
     - Cloud Security
     - How to use
     - Settings

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request
