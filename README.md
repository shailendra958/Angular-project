# My App - Angular Todo Application

A modern Angular application featuring a Todo component with SSR (Server-Side Rendering) support. Built with Angular 21 and includes components, directives, and utilities for managing tasks.

## 🚀 Features

- **Angular 21**: Modern TypeScript-based framework
- **Server-Side Rendering (SSR)**: Full SSR support with Express integration
- **Todo Component**: Fully functional todo management system
- **Custom Directives**: Includes debounce-click and tooltip directives
- **Unit Testing**: Tests configured with Vitest
- **HTTP Server**: Static server for public directory

## 📦 Prerequisites

- Node.js v18+
- npm v11.6.2 or higher

## 🛠️ Installation

```bash
git clone https://github.com/shailendra958/my-app.git
cd my-app
npm install
```

## 🏃 Getting Started

### Development Server

To start a local development server, run:

```bash
npm start
```

Once the server is running, navigate to `http://localhost:4200/`. The application will automatically reload when you modify source files.

### Build

To build the project:

```bash
npm run build
```

Artifacts are stored in the `dist/` directory.

### Testing

To execute unit tests with Vitest:

```bash
npm test
```

### Static Server

```bash
npm run serve:public
```

Serves the public directory on `http://localhost:8000/`.

### SSR Server

```bash
npm run serve:ssr:my-app
```

## 📝 Available Scripts

| Script | Purpose |
|--------|---------|
| `npm start` | Development server |
| `npm run build` | Production build |
| `npm run watch` | Build in watch mode |
| `npm test` | Run tests |
| `npm run serve:public` | Static file server |
| `npm run serve:ssr:my-app` | SSR server |

## 📚 Code Scaffolding

Generate new components:

```bash
ng generate component component-name
```

For more options:

```bash
ng generate --help
```

## Building

To build the project:

```bash
ng build
```

This compiles your project and stores build artifacts in the `dist/` directory.

## Running unit tests

To execute unit tests with the Vitest test runner:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## 📖 Documentation

- [Angular Documentation](https://angular.dev/)
- [Angular CLI Documentation](https://angular.dev/tools/cli)
- [TypeScript Documentation](https://www.typescriptlang.org/)

## 📄 License

MIT License

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 21.0.4.
