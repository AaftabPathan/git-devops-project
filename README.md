# Git & GitHub Version Control Project (DevOps)

## 📌 Project Overview

This project demonstrates a complete **Git & GitHub version control workflow** followed in real-world DevOps environments. It covers repository initialization, branching strategy, feature development, pull requests, and merging changes into the production branch.

The goal of this project is to understand how source code is managed, reviewed, and deployed using Git and GitHub.

---

## 🎯 Project Objectives

* Learn Git version control from scratch
* Implement industry-standard branching strategy
* Work with feature branches and pull requests
* Practice merging and managing code history
* Simulate real DevOps collaboration workflow

---

## 🛠️ Tools & Technologies Used

* Git (Version Control)
* GitHub (Remote Repository)
* Linux / Windows
* VS Code / Terminal

---

## 📂 Branching Strategy

* **main** → Production-ready code
* **dev** → Development branch
* **feature/homepage** → Feature-specific branch

```
feature/*  →  dev  →  main
```

---

## 🔄 Project Workflow

1. Initialized local Git repository
2. Pushed code to GitHub remote repository
3. Created `dev` branch for development
4. Created `feature/homepage` branch for new feature
5. Committed changes to feature branch
6. Raised Pull Request on GitHub
7. Reviewed and merged PR into `main`
8. Synced local repository with remote

---

## 🧪 Git Commands Used

```bash
git init
git status
git add .
git commit -m "message"
git branch
git checkout -b branch-name
git push origin branch-name
git pull origin main
git merge branch-name
git log --oneline
```

---

## 📸 Pull Request Proof

* Feature branch successfully merged into `main`
* Pull Request used for controlled code merge
* Feature branch deleted after successful merge

---

🔄 Continuous Integration (GitHub Actions)

This project uses GitHub Actions to implement Continuous Integration (CI) for automated validation of code changes.

CI Workflow Highlights

CI pipeline runs automatically on every push and pull request

Pipeline is triggered for both main and dev branches

Uses GitHub-hosted Ubuntu runner to execute jobs

Automatically checks out source code and validates project files

CI status is visible in the GitHub Actions tab and Pull Requests

CI Configuration File
.github/workflows/ci.yml

Why CI is Used in This Project

Ensures code stability before merging

Prevents broken code from reaching production branch

Automates verification without manual effort

Follows real-world DevOps CI best practices

## 📄 Sample Project File

**index.html**

```html
<h1>Welcome to Git DevOps Project</h1>
<h2>Homepage Feature Added</h2>
```

---

## 📌 Key Learnings

* Git branching and merging strategy
* Pull Request workflow in GitHub
* Difference between local and remote repositories
* Handling merge conflicts and sync issues
* Importance of clean commit history

---

## 💼 Resume Description

**Git & GitHub Version Control Project**

* Implemented complete Git workflow using feature branches and pull requests
* Managed source code using GitHub with real-world DevOps practices
* Performed branching, merging, rollback, and repository synchronization
* Tools: Git, GitHub, Linux

---

## 🚀 Future Enhancements

* Integrate Jenkins CI pipeline
* Dockerize the application
* Add automated testing

---

## 👤 Author

**Aaftab Pathan**
GitHub: [https://github.com/AaftabPathan](https://github.com/AaftabPathan)

---

⭐ If you like this project, feel free to star the repository!
