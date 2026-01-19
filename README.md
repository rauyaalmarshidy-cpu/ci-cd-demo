# CI/CD Demo Project

This project demonstrates a simple CI/CD pipeline using GitHub Actions.

## What this project does

- Uses Git for version control
- Uses GitHub Actions for Continuous Integration (CI)
- Runs a shell script automatically on every push to the `dev` branch

## How the CI works

1. Code is pushed to the `dev` branch
2. GitHub Actions is triggered
3. A Linux runner starts
4. The `app.sh` script is executed
5. Logs are available in the GitHub Actions tab

## Technologies used

- Git
- GitHub
- GitHub Actions
- Bash
