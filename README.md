
# Lovable React Web Application

**URL**: [https://lovable.dev/projects/b9740b0a-a304-4c01-814a-7c8a9f46c51f](https://lovable.dev/projects/b9740b0a-a304-4c01-814a-7c8a9f46c51f)

## Overview

This project is a modern web application built with React, TypeScript, and Tailwind CSS. It uses the shadcn/ui component library for consistent UI elements and Vite as the build tool for fast development and optimized production builds.

## Getting Started

### Prerequisites

- Node.js (v18.x or higher recommended) - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
- npm (included with Node.js)

### Installation

1. Clone the repository:
   ```sh
   git clone <YOUR_GIT_URL>
   ```

2. Navigate to the project directory:
   ```sh
   cd <YOUR_PROJECT_NAME>
   ```

3. Install dependencies:
   ```sh
   npm install
   ```

4. Start the development server:
   ```sh
   npm run dev
   ```

5. Open your browser and visit:
   ```
   http://localhost:8080
   ```

## Technology Stack

- **Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui (built on Radix UI primitives)
- **Build Tool**: Vite
- **Routing**: React Router Dom
- **State Management**: React Query
- **Icons**: Lucide React
- **Toast Notifications**: Sonner
- **Data Visualization**: Recharts

## Project Structure

The project follows a feature-based structure:

- `/src/components/ui`: Reusable UI components from shadcn/ui
- `/src/hooks`: Custom React hooks
- `/src/lib`: Utility functions and shared logic
- `/src/pages`: Page components corresponding to routes

See `filesExplorer.md` for a detailed breakdown of all files in the project.

## Development

### Available Scripts

See `scripts.md` for a comprehensive list of all available npm scripts and their usage.

### Code Style

This project uses:
- ESLint for code linting
- TypeScript for static type-checking
- Prettier (via SWC) for consistent code formatting

### Adding New Components

1. For shadcn/ui components, use the installation command:
   ```sh
   npx shadcn-ui@latest add [component-name]
   ```

2. For custom components, create them in the appropriate feature directory

## Deployment

The application can be deployed through Lovable's built-in deployment system:

1. Open [Lovable](https://lovable.dev/projects/b9740b0a-a304-4c01-814a-7c8a9f46c51f)
2. Navigate to Share → Publish

## Custom Domains

To connect a custom domain:
1. Navigate to Project → Settings → Domains in Lovable
2. Click "Connect Domain"
3. Follow the instructions to configure your DNS settings

## Contributing

### Branching Strategy

1. Create a feature branch from `main`:
   ```sh
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit:
   ```sh
   git add .
   git commit -m "feat: description of your changes"
   ```

3. Push your branch and create a pull request:
   ```sh
   git push -u origin feature/your-feature-name
   ```

### Pull Request Guidelines

- Keep changes focused on a single concern
- Include clear descriptions of the changes
- Ensure all tests pass
- Follow the established code style

## License

This project is licensed under the terms specified in the project repository.
