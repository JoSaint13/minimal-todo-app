# QuickTask

> A minimalist, intuitive todo app that helps users capture, organize, and complete tasks with maximum simplicity

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/username/quicktask)

## Overview

QuickTask is designed to solve the problem of complex task management tools that create more cognitive overhead than they solve. Our mission is to provide the fastest, most frictionless task capture experience for professionals, students, and productivity enthusiasts.

## Features

- ✨ Minimal, distraction-free task interface
- 🚀 Drag and drop task organization
- 💡 Priority and status tracking
- 🔒 Secure authentication with Clerk.dev

## Tech Stack

**Frontend:**
- React (Next.js)
- Zustand
- Tailwind CSS
- Framer Motion
- React DnD

**Backend:**
- tRPC
- Prisma ORM
- Node.js
- PostgreSQL

**Deployment:**
- Vercel
- GitHub Actions
- Sentry Monitoring

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/username/quicktask.git

# Install dependencies
cd quicktask
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── prisma/             # Database schema
├── public/             # Static assets
└── tests/              # Test files
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

## Deployment

### Vercel (Recommended)

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue on GitHub or email support@quicktask.com.

---

**Made with ❤️ for Productivity**