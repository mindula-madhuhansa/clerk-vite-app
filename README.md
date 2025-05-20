# Clerk React Authentication

A modern React application built with TypeScript and Vite that integrates Clerk for authentication and user management.

## Overview

This project demonstrates how to implement Clerk authentication in a React application. Clerk provides a complete user management solution including login, signup, user profiles, and more, with minimal setup required.

## Features

- 🚀 Built with React 18, TypeScript, and Vite
- 🔒 Secure authentication with Clerk
- 🎨 Modern UI components
- ⚡ Fast development and build times with Vite
- 📱 Responsive design for all devices

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/clerk-react.git
cd clerk-react
```

2. Install dependencies:

```bash
npm install
# or
yarn
```

3. Create a `.env` file in the root directory and add your Clerk API keys:

```
VITE_CLERK_PUBLISHABLE_KEY=your_publishable_key
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

## Project Structure

```
clerk-react/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.tsx
│   ├── main.tsx
│   └── ...
├── .env
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Configuration

This project uses Vite for development and building. The configuration can be modified in `vite.config.ts`.

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## Learn More

- [Clerk Documentation](https://clerk.dev/docs)
- [React Documentation](https://reactjs.org/)
- [Vite Documentation](https://vitejs.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
