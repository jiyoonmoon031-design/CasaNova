# 🏠 CasaNova: Financial-Based Personalized Housing Recommendation System

**_New Home, New Start._** 

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Latest Release](https://img.shields.io/github/v/release/whtjddms0714-byte/CasaNova?color=success)](https://github.com/whtjddms0714-byte/CasaNova/releases/tag/v0.0.1)
[![Contributors](https://img.shields.io/github/contributors/whtjddms0714-byte/CasaNova)](https://github.com/whtjddms0714-byte/CasaNova/graphs/contributors)

## 🌟 Project Introduction (프로젝트 소개)

CasaNova is an open-source web application designed to help **young adults in their 20s** confirm a **realistic housing budget** based on their current assets and income.
Unlike traditional real estate platforms, CasaNova integrates and analyzes complex factors—such as **DSR/DTI-emulating loan regulations** and mock youth-specific financial products—to support financially savvy and stable housing decisions.

This project is developed as a **fully open-source project**, free for anyone to use and contribute to.

## ✨ Core Features (주요 기능)

The heart of CasaNova lies in its two primary engines: **Financial Analysis** and **Preference Matching**.

| Feature | Status | Description |
| :--- | :--- | :--- |
| **💰 Financial Simulation Engine** | `Planned` | Applies DSR/DTI logic to calculate max loan amount and monthly repayment based on user input. |
| **📈 Budget Confirmation & Visualization** | `In Progress` | Confirms final budget as $$Asset + Max Loan$$ and visualizes the repayment burden rate using **Chart.js**. |
| **🎯 Lifestyle Matching Engine** | `Ready` | Calculates a matching score for residential preferences (transportation, amenities, etc.) using a weighted algorithm. |
| **🧭 Integrated Filtering** | `Planned` | Filters properties **only within the confirmed budget**, then presents the final recommendation list by matching score. |

---

## 🛠️ Development Environment Setup

CasaNova is built using a dual Python/Node.js stack.

### 1. Technical Stack 

* **Backend:** Python 3.10+ / **Django 5.x** / **MySQL**
* **Frontend:** **TypeScript** / **React** / **Tailwind CSS**
* **Tooling:** Git/GitHub, GitHub Actions, Chart.js

### 2. Prerequisite

The following tools must be installed on your system:
* **Git** 
* **Python** (3.10+ with pip) 
* **Node.js** (with npm/yarn) 
* **MySQL client**

### 3. Running the Development Server (서버 실행)

Clone the repository and follow the two-part setup process:

```bash
# 1. Clone the repository
git clone https://github.com/whtjddms0714-byte/CasaNova.git
cd CasaNova
```


### 3-1. Backend Server Setup (Django API - Python-Based)

Since the core logic is in the Django backend, this is the primary setup.

```bash
# Install Python dependencies
pip install -r requirements.txt

# Setup the database
python manage.py makemigrations
python manage.py migrate

# Run the Django API server
python manage.py runserver
```

#API accessible at http://localhost:8000 (preliminary Django default port)

### 3-2. Frontend Server Setup (React App)
The frontend is assumed to be in the frontend directory.


```bash
# Move into the frontend directory
cd frontend

# Install Node.js dependencies
npm install

# Start the React development server
npm start
```


## 🤝 How to Contribute (기여 방법)

We welcome contributions from everyone! All contributors must adhere to our standards to ensure a respectful and efficient workflow.

### Code Standards and Rules:

* **Commits:** Must use the **imperative mood** (e.g., `Add user model`, not `Added user model`).
* **Mandatory:** Include a detailed body explaining the **Why** (motivation/approach) for non-trivial changes.
* **Branch Naming:** Follow the pattern: `[type]/[issue-number]-[short-description]` (e.g., `feat/12-loan-simulator`).

### Pull Requests (PRs):

* Must link the related issue (e.g., `Closes #12`).
* Require a **minimum of 2 approvals** from collaborators before merging.
* Must include **accompanying unit and integration tests**.
* Must pass all CI/CD (linting/testing) checks.

### Code Style (Linting)

We enforce strict code formatting using the following tools:
* **Backend (Python):** Use **Black** (formatter) and **Flake8** (linter).
* **Frontend (TypeScript/React):** Use **ESLint** (linter) and **Prettier** (formatter).

---

Please refer to the detailed guidelines:

* **Code Contribution Guidelines:** Refer to the **[CONTRIBUTING.md](CONTRIBUTING.md)** file.
* **Expected Behavior:** Refer to the **[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)** file.

## ⚖️ License (라이선스)

This project is licensed under the **Apache License 2.0**.
