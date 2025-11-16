# GitHub Actions CI/CD with Security Scanning

This project demonstrates automated security scanning in a CI/CD pipeline using GitHub Actions.

## Project Structure

```
.
├── src/
│   └── calculator.py       # Simple calculator module
├── tests/
│   └── test_calculator.py  # Unit tests
├── .github/
│   └── workflows/
│       └── security-ci.yml # GitHub Actions workflow
└── requirements.txt        # Python dependencies
```

## Security Tools Used

- **Safety**: Scans Python dependencies for known security vulnerabilities (CVEs)
- **Bandit**: Analyzes Python code for common security issues

## Workflow

The CI pipeline automatically:
1. Runs on every push and pull request
2. Sets up Python environment
3. Installs dependencies and security tools
4. Runs unit tests
5. Performs dependency vulnerability scanning
6. Performs code security analysis

## Assignment Purpose

This assignment demonstrates how to integrate security checks into the development workflow, catching vulnerabilities before they reach production.
