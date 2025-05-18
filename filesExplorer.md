
# Project Files Explorer

This document provides an overview of all files in the project, organized by their directory structure. Each file is marked with an emoji indicating its complexity/importance based on imports:
- 🟢 (Green): Few imports, simple file
- 🟡 (Yellow): Moderate number of imports, medium complexity
- 🔴 (Red): Many imports, high complexity or critical functionality

## Root Directory Files

- `README.md` 🟢 - Main project documentation with setup instructions and overview
- `vite.config.ts` 🟡 - Vite configuration for the project with plugins and aliases
- `package.json` 🟢 - Project dependencies and scripts configuration
- `tsconfig.json` 🟢 - TypeScript configuration
- `tsconfig.app.json` 🟢 - TypeScript configuration specifically for the app
- `tsconfig.node.json` 🟢 - TypeScript configuration for Node.js environment
- `postcss.config.js` 🟢 - PostCSS configuration for processing CSS
- `tailwind.config.ts` 🟡 - Tailwind CSS configuration including themes and extensions
- `.gitignore` 🟢 - Git configuration for ignored files
- `components.json` 🟢 - Configuration for shadcn/ui components

## /src Directory

- `main.tsx` 🟢 - Application entry point that renders the root React component
- `App.tsx` 🔴 - Main application component with routing and providers setup
- `vite-env.d.ts` 🟢 - Type declarations for Vite environment
- `index.css` 🟢 - Global CSS styles including Tailwind directives and theme variables

### /src/components

#### /src/components/ui
- `accordion.tsx` 🟡 - Reusable accordion component from shadcn/ui
- `alert-dialog.tsx` 🟡 - Alert dialog component for important notifications
- `alert.tsx` 🟢 - Alert component for status messages
- `aspect-ratio.tsx` 🟢 - Component for maintaining aspect ratios
- `avatar.tsx` 🟢 - User avatar component
- `badge.tsx` 🟢 - Badge component for labels and status indicators
- `breadcrumb.tsx` 🟢 - Navigation breadcrumb component
- `button.tsx` 🟢 - Button component with various styles
- `calendar.tsx` 🟡 - Calendar date picker component
- `card.tsx` 🟢 - Card container component
- `carousel.tsx` 🔴 - Carousel/slider component with multiple features
- `chart.tsx` 🟡 - Data visualization chart component
- `checkbox.tsx` 🟢 - Checkbox input component
- `collapsible.tsx` 🟢 - Collapsible section component
- `command.tsx` 🟡 - Command palette interface component
- `context-menu.tsx` 🟡 - Right-click context menu component
- `dialog.tsx` 🟡 - Modal dialog component
- `drawer.tsx` 🟡 - Slide-in drawer component
- `dropdown-menu.tsx` 🟡 - Dropdown menu component
- `form.tsx` 🟡 - Form components with validation
- `hover-card.tsx` 🟢 - Card that appears on hover
- `input-otp.tsx` 🟡 - One-time password input component
- `input.tsx` 🟢 - Text input component
- `label.tsx` 🟢 - Form label component
- `menubar.tsx` 🟡 - Horizontal menu bar component
- `navigation-menu.tsx` 🟡 - Navigation menu component
- `pagination.tsx` 🟢 - Pagination component for lists
- `popover.tsx` 🟢 - Popover component for tooltips and menus
- `progress.tsx` 🟢 - Progress indicator component
- `radio-group.tsx` 🟢 - Radio button group component
- `resizable.tsx` 🟡 - Resizable panel component
- `scroll-area.tsx` 🟢 - Custom scrollable area component
- `select.tsx` 🟢 - Select dropdown component
- `separator.tsx` 🟢 - Visual separator/divider component
- `sheet.tsx` 🟡 - Side sheet/panel component
- `sidebar.tsx` 🟡 - Navigation sidebar component
- `skeleton.tsx` 🟢 - Loading skeleton component
- `slider.tsx` 🟢 - Range slider component
- `sonner.tsx` 🟢 - Toast notification component using Sonner
- `switch.tsx` 🟢 - Toggle switch component
- `table.tsx` 🟢 - Table component for data display
- `tabs.tsx` 🟢 - Tabbed interface component
- `textarea.tsx` 🟢 - Multi-line text input component
- `toast.tsx` 🟡 - Toast notification component
- `toaster.tsx` 🟢 - Toast notification container component
- `toggle-group.tsx` 🟢 - Group of toggle buttons component
- `toggle.tsx` 🟢 - Toggle button component
- `tooltip.tsx` 🟢 - Tooltip component for hints
- `use-toast.ts` 🟢 - Hook re-export for toast functionality

### /src/hooks
- `use-mobile.tsx` 🟢 - Hook for detecting mobile viewport
- `use-toast.ts` 🟡 - Hook for managing toast notifications

### /src/lib
- `utils.ts` 🟢 - Utility functions used throughout the application

### /src/pages
- `Index.tsx` 🟡 - Home page component
- `NotFound.tsx` 🟢 - 404 Not Found page component

## /public Directory
- `favicon.ico` 🟢 - Website favicon icon
- `placeholder.svg` 🟢 - Placeholder image for development
- `robots.txt` 🟢 - Instructions for search engine crawlers

## Folder Structure Assessment

The project follows a well-organized structure with clear separation of concerns. The UI components are properly grouped, and the application has a clean hierarchical organization. The use of shadcn/ui components provides consistency across the user interface.
