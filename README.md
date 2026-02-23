# 🚀 Multi-Cloud Automated Resume

This project demonstrates a **Multi-Cloud CI/CD Pipeline**. The same code is automatically deployed to both **GitHub Pages** and **GitLab Pages** using their respective automation engines.

### 📊 Pipeline Status
| Provider | Status | Live Link |
| :--- | :--- | :--- |
| **GitHub Actions** | ![GitHub Actions](https://github.com/chetan48861/my-staic-web-resume/actions/workflows/devops-resume.yml/badge.svg) | [Visit GitHub Site](https://chetan48861.github.io/my-staic-web-resume/) |
| **GitLab CI/CD** | ![GitLab CI](https://gitlab.com/sharmachetan4886/my-staic-web-resume/badges/main/pipeline.svg) | [Visit GitLab Site](https://sharmachetan4886.gitlab.io/my-staic-web-resume/) |

### 🛠️ DevOps Tools Used
* **Git/Version Control**
* **GitHub Actions** (Workflow automation)
* **GitLab CI/CD** (Pipeline automation)
* **Linux (Ubuntu)** (Runner environments)

---
### 🏗️ How it Works
1. **Local Development:** Code is written in VS Code.
2. **GitHub Push:** Triggers `.github/workflows/devops-resume.yml`.
3. **GitLab Push:** Triggers `.gitlab-ci.yml`.
4. **Result:** A live, hosted resume on two separate cloud infrastructures.