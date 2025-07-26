# 📦 Python Docker Dev Environment Setup

A containerized Python development environment with database support, system tools, and proper environment isolation.

---

## ✅ Features

- ✔️ Python 3.11 running in a Docker container
- ✔️ Virtual environment setup with `venv` and `conda` (Miniconda)
- ✔️ PostgreSQL 15 and MongoDB 6.0 installed locally
- ✔️ Docker working with basic containerization concepts
- ✔️ VS Code with essential extensions (Black, Pylint, Prettier, ESLint, GitLens, etc.)
- ✔️ Git + GitHub configured for version control
- ✔️ Ubuntu WSL2 with Linux CLI familiarity
- ✔️ Formatting + Linting via CLI and VS Code integration
- ✔️ System monitoring tools: `htop`, Task Manager
- 📁 Project includes Dockerfile for running standalone Python apps

---

## 🐳 Docker Usage

```bash
# 1. Navigate to the project folder
cd dev-env-setup/python-docker-db

# 2. Build the Docker image
docker build -t python-test .

# 3. Run the container
docker run python-test
```
