# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability, please report it by emailing the maintainers directly. Please do not create a public GitHub issue for security vulnerabilities.

### What to include in your report:

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Suggested fix (if available)

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days
- **Resolution**: Varies based on complexity

## Security Best Practices

### For Contributors

- Keep dependencies up to date
- Use `npm audit` to check for vulnerabilities
- Follow secure coding practices
- Validate all user inputs
- Use HTTPS in production

### For Users

- Regularly update to the latest version
- Review and audit dependencies
- Use environment variables for sensitive data
- Enable Content Security Policy (CSP)
- Implement proper authentication and authorization

## Security Features

- TypeScript for type safety
- ESLint for code quality
- Modern React patterns
- Vite's built-in security features

## Dependency Security

This project uses automated dependency scanning. Run `npm audit` regularly to check for known vulnerabilities in dependencies.