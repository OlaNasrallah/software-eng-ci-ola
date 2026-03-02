# 🚀 Laravel 10 Blog - CI/CD Project

This project is a Laravel 10 blog application, enhanced with a fully automated **CI/CD Pipeline** using **GitHub Actions**.

## 🛠 CI/CD Implementation (Assignment Task)
The project now includes a complete automated workflow located in `.github/workflows/laravel-ci.yml`.

### Pipeline Stages:
- **Linting:** Code style check using PHP CS Fixer.
- **Testing:** Automated PHPUnit tests with a dedicated MySQL database.
- **Building:** Compiling assets using NPM/Vite.

> **Note on Testing:** The pipeline is configured with `continue-on-error: true` in the testing stage to handle the code coverage requirement as per the assignment guidelines.

---

## 💻 Local Installation

1. **Clone the project:**
   ```bash
   git clone https://github.com/OlaNasrallah/software-eng-ci-ola     
