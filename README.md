# ETAN FRONTEND v1.0.0

Angular 21 Enterprise Application

## Architecture

- Clean Architecture
- Standalone Components
- Signal-based State Management
- Zoneless Change Detection

## Project Structure

```
src/
├── app/
│   ├── core/           # Singleton services, guards, interceptors
│   ├── shared/         # Reusable components, directives, pipes
│   ├── features/       # Feature modules (Auth, Dashboard, Admin)
│   └── layouts/        # Layout components
├── assets/             # Static assets
├── environments/       # Environment configurations
└── styles/            # Global styles
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm start
```

Navigate to `http://localhost:4200/`

### Build

```bash
npm run build
```

### Testing

```bash
npm test
npm run test:coverage
```

### Linting

```bash
npm run lint
npm run lint:fix
```

### Code Quality

```bash
npm run sonar
```

## Technologies

- Angular 21
- Angular Material
- RxJS
- TypeScript 5.9
- Vitest
- SonarQube

## Features

- JWT Authentication
- Refresh Token Flow
- Role-based Access Control
- Permission-based Authorization
- Dynamic Menu System
- Internationalization (i18n)
- Secure Storage
- Error Handling
- Audit Logging

## License

Proprietary - MSC Peru 2025

