# GitHub Actions Demo

## 📌 Description
This project showcases how to set up automated workflows using GitHub Actions, including testing and linting.

## 📂 Overview
### 1️⃣ Pull Request Workflow
When a pull request is created or updated, the following workflows are triggered:
- ✅ Linting: Checks code style using Super-Linter.
- ✅ Testing: Runs `pytest` to ensure all tests pass.

### 2️⃣ Branch Protection
Direct pushes to main are restricted. All changes must go through a pull request to ensure code quality.
