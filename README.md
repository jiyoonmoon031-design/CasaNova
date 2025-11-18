# 🏠 CasaNova: Financial-Based Personalized Housing Recommendation System

[cite_start]**_New Home, New Start._** [cite: 69, 186]

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Latest Release](https://img.shields.io/github/v/release/whtjddms0714-byte/CasaNova?color=success)](https://github.com/whtjddms0714-byte/CasaNova/releases/tag/v0.0.1)
[![Contributors](https://img.shields.io/github/contributors/whtjddms0714-byte/CasaNova)](https://github.com/whtjddms0714-byte/CasaNova/graphs/contributors)

## 🌟 Project Introduction (프로젝트 소개)

[cite_start]CasaNova is an open-source web application designed to help **young adults in their 20s** confirm a **realistic housing budget** based on their current assets and income[cite: 191, 217]. [cite_start]Unlike traditional real estate platforms, CasaNova integrates and analyzes complex factors—such as **DSR/DTI-emulating loan regulations** and mock youth-specific financial products [cite: 179, 218]—to support financially savvy and stable housing decisions.

[cite_start]This project is developed as a **fully open-source project**, free for anyone to use and contribute to[cite: 193].

---

## ✨ Core Features (주요 기능)

[cite_start]The heart of CasaNova lies in its two primary engines: **Financial Analysis** and **Preference Matching**[cite: 220].

| Feature | Status | Description |
| :--- | :--- | :--- |
| **💰 Financial Simulation Engine** | `Planned` | [cite_start]Applies DSR/DTI logic to calculate max loan amount and monthly repayment based on user input[cite: 195, 221]. |
| **📈 Budget Confirmation & Visualization** | `In Progress` | [cite_start]Confirms final budget as $$Asset + Max Loan$$ and visualizes the repayment burden rate using **Chart.js**[cite: 195, 225]. |
| **🎯 Lifestyle Matching Engine** | `Ready` | [cite_start]Calculates a matching score for residential preferences (transportation, amenities, etc.) using a weighted algorithm[cite: 195, 226]. |
| **🧭 Integrated Filtering** | `Planned` | [cite_start]Filters properties **only within the confirmed budget**, then presents the final recommendation list by matching score[cite: 195]. |

---

## 🛠️ Development Environment Setup

CasaNova is built using a dual Python/Node.js stack.

### [cite_start]1. Technical Stack [cite: 197]

* **Backend:** Python 3.10+ / **Django 5.x** / **MySQL**
* **Frontend:** **TypeScript** / **React** / **Tailwind CSS**
* **Tooling:** Git/GitHub, GitHub Actions, Chart.js

### 2. Prerequisite

The following tools must be installed on your system:
* [cite_start]**Git** [cite: 243]
* [cite_start]**Python** (3.10+ with pip) [cite: 197, 244]
* [cite_start]**Node.js** (with npm/yarn) [cite: 245]
* [cite_start]**MySQL client** [cite: 246]

### 3. Running the Development Server (서버 실행)

Clone the repository and follow the two-part setup process:

```bash
# 1. Clone the repository
git clone [https://github.com/whtjddms0714-byte/CasaNova.git](https://github.com/whtjddms0714-byte/CasaNova.git)
cd CasaNova

3-1. Backend Server Setup (Django API - Python-Based)
Since the core logic is in the Django backend, this is the primary setup.

Bash

# Install Python dependencies
pip install -r requirements.txt

# Setup the database
python manage.py makemigrations
python manage.py migrate

# Run the Django API server
python manage.py runserver
# API accessible at http://localhost:8000 (preliminary Django default port)

네, 아주 좋습니다! 과제 2의 핵심 요구사항인 "명확하고 스캔하기 쉬운 (Clear and Scannable)" README를 완성하는 것과, GitHub 저장소 설정에 필요한 설명 및 주제를 아래와 같이 정리해 드립니다.

CasaNova 프로젝트의 이중 스택(Python/Django & TypeScript/React)을 고려하여 설치 방법도 상세하게 반영했습니다.

1. ⚙️ GitHub 저장소 설정 정보
1.1. 짧은 설명 (Short Description)
저장소 상단에 표시되는 한 줄 설명입니다.

A personalized, open-source web platform integrating DSR/DTI-emulating financial analysis with real estate recommendations for young adults.

1.2. 주제 (Topics)
프로젝트를 검색하기 쉽게 만드는 태그입니다.

fintech, real-estate, django, python, react, typescript, housing, open-source

2. 📄 CasaNova: README.md 최종 초안
과제 1의 내용을 바탕으로 과제 2의 요구사항(Apache License, 커뮤니티 문서 링크, 명확한 설치 가이드)을 모두 충족하도록 업데이트되었습니다.

Markdown

# 🏠 CasaNova: Financial-Based Personalized Housing Recommendation System

[cite_start]**_New Home, New Start._** [cite: 69, 186]

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Latest Release](https://img.shields.io/github/v/release/whtjddms0714-byte/CasaNova?color=success)](https://github.com/whtjddms0714-byte/CasaNova/releases/tag/v0.0.1)
[![Contributors](https://img.shields.io/github/contributors/whtjddms0714-byte/CasaNova)](https://github.com/whtjddms0714-byte/CasaNova/graphs/contributors)

## 🌟 Project Introduction (프로젝트 소개)

[cite_start]CasaNova is an open-source web application designed to help **young adults in their 20s** confirm a **realistic housing budget** based on their current assets and income[cite: 191, 217]. [cite_start]Unlike traditional real estate platforms, CasaNova integrates and analyzes complex factors—such as **DSR/DTI-emulating loan regulations** and mock youth-specific financial products [cite: 179, 218]—to support financially savvy and stable housing decisions.

[cite_start]This project is developed as a **fully open-source project**, free for anyone to use and contribute to[cite: 193].

---

## ✨ Core Features (주요 기능)

[cite_start]The heart of CasaNova lies in its two primary engines: **Financial Analysis** and **Preference Matching**[cite: 220].

| Feature | Status | Description |
| :--- | :--- | :--- |
| **💰 Financial Simulation Engine** | `Planned` | [cite_start]Applies DSR/DTI logic to calculate max loan amount and monthly repayment based on user input[cite: 195, 221]. |
| **📈 Budget Confirmation & Visualization** | `In Progress` | [cite_start]Confirms final budget as $$Asset + Max Loan$$ and visualizes the repayment burden rate using **Chart.js**[cite: 195, 225]. |
| **🎯 Lifestyle Matching Engine** | `Ready` | [cite_start]Calculates a matching score for residential preferences (transportation, amenities, etc.) using a weighted algorithm[cite: 195, 226]. |
| **🧭 Integrated Filtering** | `Planned` | [cite_start]Filters properties **only within the confirmed budget**, then presents the final recommendation list by matching score[cite: 195]. |

---

## 🛠️ Development Environment Setup (개발 환경 설정)

CasaNova is built using a dual Python/Node.js stack.

### [cite_start]1. Technical Stack [cite: 197]

* **Backend:** Python 3.10+ / **Django 5.x** / **MySQL**
* **Frontend:** **TypeScript** / **React** / **Tailwind CSS**
* **Tooling:** Git/GitHub, GitHub Actions, Chart.js

### 2. Prerequisites (필수 요구 사항)

The following tools must be installed on your system:
* [cite_start]**Git** [cite: 243]
* [cite_start]**Python** (3.10+ with pip) [cite: 197, 244]
* [cite_start]**Node.js** (with npm/yarn) [cite: 245]
* [cite_start]**MySQL client** [cite: 246]

### 3. Running the Development Server (서버 실행)

Clone the repository and follow the two-part setup process:

```bash
# 1. Clone the repository
git clone [https://github.com/whtjddms0714-byte/CasaNova.git](https://github.com/whtjddms0714-byte/CasaNova.git)
cd CasaNova
3-1. Backend Server Setup (Django API - Python-Based)
Since the core logic is in the Django backend, this is the primary setup.


# Install Python dependencies
pip install -r requirements.txt

# Setup the database
python manage.py makemigrations
python manage.py migrate

# Run the Django API server
python manage.py runserver
# API accessible at http://localhost:8000 (preliminary Django default port)


3-2. Frontend Server Setup (React App)
The frontend is assumed to be in the frontend directory.

# Move into the frontend directory
cd frontend

# Install Node.js dependencies
npm install

# Start the React development server
npm start
# App accessible at http://localhost:3000 (preliminary React default port)

🤝 How to Contribute
We welcome contributions from everyone! All contributors must adhere to our standards to ensure a respectful and efficient workflow.

Code Standards and Rules:
Commits: Must use the imperative mood (e.g., Add user model, not Added user model).

Mandatory: Include a detailed body explaining the Why (motivation/approach) for non-trivial changes.

Branch Naming: Follow the pattern: [type]/[issue-number]-[short-description] (e.g., feat/12-loan-simulator).

Pull Requests (PRs):

Must link the related issue (e.g., Closes #12).

Require a minimum of 2 approvals from collaborators before merging.

Must include accompanying unit and integration tests.

Must pass all CI/CD (linting/testing) checks.

Code Style (Linting)
We enforce strict code formatting using the following tools:

Backend (Python): Use Black (formatter) and Flake8 (linter).

Frontend (TypeScript/React): Use ESLint (linter) and Prettier (formatter).

Please refer to the detailed guidelines:

Code Contribution Guidelines: Refer to the CONTRIBUTING.md file.

Expected Behavior: Refer to the CODE_OF_CONDUCT.md file.

⚖️ License (라이선스)
This project is licensed under the Apache License 2.0.


