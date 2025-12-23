# Development Guide - Whisper Chat Application

## Overview

Whisper is a fun application designed to facilitate random chat with people safely. This guide provides instructions for developers interested in contributing to the project.

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager
- Git for version control
- Basic understanding of JavaScript and Express.js

### Installation

```bash
# Clone the repository
git clone https://github.com/rishabh8870/Whisper.git

# Navigate to project directory
cd Whisper

# Install dependencies
npm install

# Start development server
npm start
```

## Project Structure

```
Whisper/
├── client/          # Frontend React application
├── server/          # Backend Express.js server
├── docs/            # Documentation files
├── .github/         # GitHub workflows and actions
├── package.json     # Project dependencies
└── README.md        # Project README
```

## Development Workflow

1. **Create Feature Branch**: `git checkout -b feature/your-feature-name`
2. **Make Changes**: Implement your feature or fix
3. **Write Tests**: Add tests for new functionality
4. **Commit Changes**: `git commit -m "feat: add your feature"`
5. **Push Changes**: `git push origin feature/your-feature-name`
6. **Create Pull Request**: Submit PR for review

## Code Style Guide

### JavaScript Standards

- Use ES6+ syntax
- Follow Airbnb style guide
- Use meaningful variable names
- Add comments for complex logic
- Maintain consistent indentation (2 spaces)

### Git Commit Messages

Follow conventional commit format:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation
- `style:` for code style changes
- `refactor:` for code refactoring
- `test:` for adding tests
- `chore:` for maintenance tasks

## Testing

```bash
# Run all tests
npm test

# Run tests with coverage
npm run test:coverage

# Run tests in watch mode
npm run test:watch
```

## Deployment

The application is deployed using continuous integration/continuous deployment (CI/CD) pipelines.

### Staging Environment
- Automatically deployed when changes are merged to develop branch

### Production Environment
- Manually triggered deployments from the main branch

## Contributing Guidelines

1. Fork the repository
2. Create a feature branch
3. Make meaningful commits
4. Ensure all tests pass
5. Submit a pull request with detailed description

## Resources

- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://reactjs.org/)
- [Git Best Practices](https://git-scm.com/docs)
- [Conventional Commits](https://www.conventionalcommits.org/)

## Support

For questions or issues, please:
- Check existing issues on GitHub
- Create a new issue with detailed information
- Contact the development team

---

Last Updated: December 23, 2025
Maintainer: @rishabh8870
