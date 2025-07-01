# Python GitHub Actions Example

This repository demonstrates how to use GitHub Actions to run tests for a simple Python project.

## Structure

- `calculator.py`: Example Python code
- `test_calculator.py`: Pytest test cases for the code
- `.github/workflows/python-app.yml`: GitHub Actions workflow file

## How it works

Every push or pull request to the `main` branch will trigger the GitHub Actions workflow, which:
1. Checks out the code
2. Sets up Python
3. Installs dependencies
4. Runs tests using pytest
