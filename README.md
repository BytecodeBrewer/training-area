# GitHub Governance Lab

A practical self-study project focused on GitHub security, automation, dependency management, and collaborative repository governance.

The repository uses a small FastAPI and MongoDB application as a realistic codebase for configuring and testing GitHub workflows, CodeQL, Dependabot, CODEOWNERS, security policies, and contribution processes.

## What I implemented

- GitHub Actions workflows
- CodeQL code scanning
- Dependabot dependency updates
- CODEOWNERS configuration
- Security policies
- Contribution guidelines
- Code of Conduct setup
- Pull request and review workflows
- Repository organization and collaboration practices

## Practice application

The repository contains a small FastAPI application backed by MongoDB and a lightweight frontend.

The application provides a realistic codebase for experimenting with repository security, automation, dependency management, and collaborative development workflows.

## Technology stack

- Python
- FastAPI
- MongoDB
- JavaScript
- HTML
- CSS
- GitHub Actions
- CodeQL
- Dependabot

## Project structure

```text
.
├── src/
│   ├── app.py
│   ├── backend/
│   │   ├── database.py
│   │   └── routers/
│   └── static/
├── .github/
│   └── workflows/
├── CODEOWNERS
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── requirements.txt
└── README.md
```

## Running the sample application

### Requirements

- Python 3.8 or newer
- MongoDB
- Git

### Installation

```bash
git clone https://github.com/BytecodeBrewer/github-governance-lab.git
cd github-governance-lab
pip install -r requirements.txt
```

### Start the application

```bash
python -m uvicorn src.app:app --reload
```

The application is then available at:

- Frontend: `http://localhost:8000`
- API documentation: `http://localhost:8000/docs`
- Alternative API documentation: `http://localhost:8000/redoc`

## Repository features

### CodeQL

CodeQL is configured to scan the Python and JavaScript code for security issues through GitHub Actions.

### Dependabot

Dependabot is configured to create automated pull requests for dependency updates.

### Repository governance

The repository includes:

- `CODEOWNERS`
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`

These files define ownership, contribution expectations, conduct rules, and security reporting processes for the repository.
