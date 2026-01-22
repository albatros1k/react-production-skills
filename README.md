# React Production Skills

A comprehensive React application demonstrating production-ready practices, configurations, and architectural patterns. This project showcases modern frontend development techniques with TypeScript, Webpack, and various industry-standard tools.

## 🎯 Project Overview

This repository serves as a learning resource and reference implementation for building production-grade React applications. Each feature branch represents a specific production skill or architectural pattern, making it easy to understand and adopt individual concepts.

## 🚀 Features

### Core Setup
- **TypeScript Configuration** - Fully typed React application with strict TypeScript settings
- **Custom Webpack Configuration** - Modular webpack setup with separate configurations for:
  - Loaders (TypeScript, SCSS, CSS Modules)
  - Plugins (HTML, CSS extraction)
  - Dev Server with Hot Module Replacement
  - Resolvers for module resolution

### Architecture & Design Patterns
- **Feature-Sliced Design (FSD)** - Modern frontend architecture for scalable applications
- **Component Modularization** - Organized component structure with co-located styles
- **CSS Modules** - Scoped styling to prevent CSS conflicts

### Styling
- **SCSS/Sass Support** - Advanced styling with preprocessors
- **Theme Support** - Dark/Light theme implementation
- **Responsive Design** - Adaptive layouts and components
- **Style Linting** - Consistent CSS/SCSS code quality

### Routing & Navigation
- **React Router** - Client-side routing configuration
- **Router Configuration** - Centralized route management
- **Sidebar Navigation** - Adaptive sidebar component

### State Management
- **Redux Toolkit** - Modern Redux implementation with:
  - Slice-based state management
  - RTK Query for API calls
  - TypeScript integration

### UI Components
- **Portal & Modal System** - Reusable modal components with React Portals
- **Form Components** - Custom input components with validation
- **Login Form** - Authentication UI with custom inputs
- **Error Boundary** - Graceful error handling and fallback UI

### Internationalization (i18n)
- **i18next Integration** - Multi-language support
- **Backend Plugin** - Dynamic language loading
- **Lazy Loading** - Optimized translation bundle loading

### Backend Integration
- **JSON Server** - Mock REST API for development
- **Authorization** - Login/logout logic implementation
- **API Integration** - RESTful API communication patterns

### Testing
- **Jest Configuration** - Unit testing setup
- **React Testing Library** - Component testing with user-centric approach
- **Storybook** - Component documentation and visual testing
- **Loki** - Visual regression testing
- **CI/CD Pipeline** - GitHub Actions for automated testing

### Code Quality
- **ESLint** - JavaScript/TypeScript linting
- **StyleLint** - CSS/SCSS linting
- **Prettier Integration** - Code formatting
- **Bundle Analyzer** - Build optimization insights

### Developer Experience
- **React Refresh** - Fast hot reloading without losing state
- **Source Maps** - Easy debugging in development
- **Development Server** - Optimized dev server with live reload

## 📦 Installation

```bash
# Clone the repository
git clone <repository-url>
cd react-production-skills

# Install dependencies
npm install
```

## 🛠️ Available Scripts

```bash
# Start development server on port 3000
npm start

# Build for production
npm run build:prod

# Build for development
npm run build:dev

# Run tests
npm test
```

## 🌿 Branch Structure

The project uses a feature-branch workflow where each branch demonstrates a specific skill:

### Configuration Branches
- `configuration/webpack` - Custom Webpack setup
- `configuration/es_lint` - ESLint configuration
- `configuration/style-lint` - StyleLint setup
- `configuration/jest` - Jest testing configuration

### Architecture Branches
- `architecture/FSD` - Feature-Sliced Design implementation

### Feature Branches
- `feature/error-boundary` - Error boundary implementation
- `feature/internalization` - i18n setup
- `feature/json-server` - Mock API server
- `feature/login_form` - Authentication form
- `feature/portal-modal` - Modal system
- `feature/react-router` - Routing setup
- `feature/react-testing-library` - Component testing
- `feature/redux-toolkit` - State management
- `feature/router-config` - Route configuration
- `feature/sidebar` - Navigation sidebar

### Layout Branches
- `layout/app-layout` - Main application layout

### Styling Branches
- `styles/themes` - Theme system implementation

### Testing Branches
- `testing/ci-pipeline` - CI/CD with GitHub Actions
- `testing/loki` - Visual regression testing
- `testing/storybook` - Component documentation

### Development Branch
- `develop` - Integration branch for all features

## 🏗️ Project Structure

```
react-production-skills/
├── config/
│   └── build/
│       ├── buildDevServer.ts      # Webpack dev server config
│       ├── buildLoaders.ts        # Webpack loaders
│       ├── buildPlugins.ts        # Webpack plugins
│       ├── buildResolvers.ts      # Module resolution
│       ├── buildWebpackConfig.ts  # Main webpack config
│       └── types/
│           └── config.ts          # TypeScript types
├── public/
│   └── index.html                 # HTML template
├── src/
│   ├── components/                # React components
│   ├── App.tsx                    # Root component
│   ├── index.tsx                  # Entry point
│   ├── index.scss                 # Global styles
│   └── global.d.ts                # Global type declarations
├── package.json
├── tsconfig.json                  # TypeScript configuration
└── webpack.config.ts              # Webpack entry point
```

## 🔧 Technology Stack

### Core
- **React** 17.0.2
- **TypeScript** 4.5.5
- **Webpack** 5.69.1

### Development Tools
- **Webpack Dev Server** 4.7.4
- **ts-loader** - TypeScript compilation
- **sass-loader** - SCSS compilation
- **style-loader** & **css-loader** - CSS handling
- **mini-css-extract-plugin** - CSS extraction for production

### Build Tools
- **html-webpack-plugin** - HTML generation
- **ts-node** - TypeScript execution for configs

## 📚 Learning Path

To get the most out of this project, explore branches in this order:

1. **configuration/webpack** - Understand the build system
2. **architecture/FSD** - Learn the project structure
3. **styles/themes** - Implement theming
4. **feature/react-router** - Add navigation
5. **feature/sidebar** - Build UI components
6. **feature/redux-toolkit** - Manage state
7. **feature/portal-modal** - Advanced UI patterns
8. **feature/login_form** - Forms and validation
9. **feature/error-boundary** - Error handling
10. **testing/** branches - Test your application

## 🤝 Contributing

Each feature is isolated in its own branch. To understand or implement a specific feature:

1. Checkout the relevant feature branch
2. Review the commits in that branch
3. Study the code changes
4. Merge to your working branch if needed

## 📝 Notes

- The main branch of this project is `develop` (not main/master)
- Each feature branch can be studied independently
- The webpack configuration is modular and easy to extend
- TypeScript strict mode is enabled for better type safety
- All feature branches merge into `develop`

## 🔗 Related Concepts

- Feature-Sliced Design (FSD)
- Component-driven development
- State management patterns
- Testing strategies
- Build optimization
- Code splitting and lazy loading
- Internationalization
- CI/CD automation

## 📄 License

ISC

---

**Built with ❤️ as a production skills demonstration project**
