
# Available Scripts

This document provides details about all the npm scripts available in this project, their purpose, and usage examples.

## Core Development Scripts

### `npm run dev`

**Purpose**: Starts the development server with hot-reloading.

**Usage**:
```bash
npm run dev
```

This launches the Vite development server, enabling you to view your application at `http://localhost:8080`. The server supports hot module replacement, so changes to your code will automatically be reflected in the browser without requiring a full reload.

### `npm run build`

**Purpose**: Creates a production-ready build of your application.

**Usage**:
```bash
npm run build
```

This compiles and bundles all your source code into optimized files in the `dist` directory, ready for deployment. It includes minification, tree-shaking, and other optimizations.

### `npm run preview`

**Purpose**: Serves the production build locally for preview.

**Usage**:
```bash
npm run build
npm run preview
```

This allows you to test the production build locally before deploying. It serves the contents of the `dist` directory on a local web server.

## Code Quality Scripts

### `npm run lint`

**Purpose**: Runs ESLint to check for code style and potential issues.

**Usage**:
```bash
npm run lint
```

This analyzes your TypeScript and React code for potential problems and style inconsistencies.

### `npm run lint:fix`

**Purpose**: Automatically fixes ESLint issues when possible.

**Usage**:
```bash
npm run lint:fix
```

This attempts to automatically correct any fixable issues identified by ESLint.

### `npm run type-check`

**Purpose**: Runs the TypeScript compiler to check for type errors.

**Usage**:
```bash
npm run type-check
```

This verifies that your TypeScript code is type-safe without producing output files.

## Testing Scripts

### `npm run test`

**Purpose**: Runs unit tests using Vitest.

**Usage**:
```bash
npm run test
```

This executes all test files matching the pattern `*.test.ts` or `*.test.tsx`.

### `npm run test:watch`

**Purpose**: Runs tests in watch mode for development.

**Usage**:
```bash
npm run test:watch
```

This continuously runs tests as files change, which is useful during development.

### `npm run test:coverage`

**Purpose**: Runs tests and generates a code coverage report.

**Usage**:
```bash
npm run test:coverage
```

This creates a detailed report showing how much of your code is covered by tests.

## Utility Scripts

### `npm run clean`

**Purpose**: Removes build output and temporary files.

**Usage**:
```bash
npm run clean
```

This deletes the `dist` directory and other temporary files created during the build process.

### `npm run format`

**Purpose**: Formats code using Prettier.

**Usage**:
```bash
npm run format
```

This ensures consistent code formatting across the project.

## Deployment Scripts

### `npm run deploy`

**Purpose**: Builds and deploys the application.

**Usage**:
```bash
npm run deploy
```

This runs the build process and then deploys the application to the configured hosting platform. Note: This script's behavior depends on your specific deployment setup.

## Combined Scripts

### `npm run validate`

**Purpose**: Runs linting, type-checking, and tests in sequence.

**Usage**:
```bash
npm run validate
```

This is useful before pushing changes or creating a pull request to ensure your code meets all quality standards.

## Tips for Script Usage

1. **Development Workflow**:
   ```bash
   npm run dev
   ```
   Run this in one terminal and keep it open during development.

2. **Pre-commit Check**:
   ```bash
   npm run validate
   ```
   Run before committing to ensure code quality.

3. **Preparing for Deployment**:
   ```bash
   npm run build
   npm run preview
   ```
   Build and preview the production version locally.

4. **Fixing Code Style Issues**:
   ```bash
   npm run lint:fix
   npm run format
   ```
   Run these together to fix code style issues automatically.
