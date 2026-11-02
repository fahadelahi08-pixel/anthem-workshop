# 🎓 Git & GitHub Practice Workshop

### National Anthem Project — Workshop Edition

![Git](https://img.shields.io/badge/Git-Version_Control-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web_Framework-000000?logo=flask&logoColor=white)

## 📌 Project Overview

This project was developed as part of the **Git & GitHub Practice Workshop** to gain practical experience with version control and collaborative software development.

The National Anthem Project is a simple Flask-based web application that displays the Indian National Anthem. The workshop demonstrates how multiple developers can work on a shared repository using Git and GitHub.

## 🎯 Workshop Objectives

- Understand Git and GitHub fundamentals.
- Create and manage repositories.
- Perform Git push and pull operations.
- Clone repositories between developer workspaces.
- Create and manage feature branches.
- Merge branches into the main branch.
- Create and resolve merge conflicts.
- Undo changes and recover commits using Git reflog.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Git | Version control |
| GitHub | Remote repository hosting |
| Python | Application development |
| Flask | Web application framework |
| HTML | Webpage structure |
| macOS Terminal | Command-line operations |

## 📂 Project Structure

```text
anthem-workshop/
│
├── README.md
├── anthem.txt
├── developer.txt
├── app.py
│
└── templates/
    └── index.html
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/fahadelahi08-pixel/anthem-workshop.git
```

### 2. Navigate to the Project

```bash
cd anthem-workshop
```

### 3. Create a Python Virtual Environment

```bash
python3 -m venv venv
```

### 4. Activate the Environment

```bash
source venv/bin/activate
```

### 5. Install Flask

```bash
python -m pip install Flask
```

### 6. Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🔄 Git Workflow Practised

### 1. Initialize Repository

```bash
git init
```

### 2. Add Files

```bash
git add .
```

### 3. Commit Changes

```bash
git commit -m "Your commit message"
```

### 4. Push Changes

```bash
git push origin main
```

### 5. Pull Latest Changes

```bash
git pull origin main
```

### 6. Create a Feature Branch

```bash
git switch -c feature/new-feature
```

### 7. Merge a Branch

```bash
git switch main
git merge feature/new-feature
```

## 🌿 Workshop Activities

| Part | Activity |
|---|---|
| Part 0 | Git user configuration |
| Part 1 | Repository creation and cloning |
| Part 2 | Push and pull operations |
| Part 3 | Branching, merging and deletion |
| Part 4 | Merge conflict creation and resolution |
| Part 5 | Undo and recovery using reflog |

## 👨‍💻 Team Roles Practised

| Name | Role | Responsibility |
|---|---|---|
| Satish | Team Lead | Repository management, merging and conflict resolution |
| Rajesh | Developer | Application development and feature branches |
| Fahad | Tester | Testing and improving project content |

*Note: These roles were simulated using separate Git working directories on one Mac.*

## 🔀 Merge Conflict Resolution

During the workshop, two branches modified the same HTML heading with different titles.

- `conflict-english`
- `conflict-fahad`

A merge conflict was created intentionally and resolved manually by choosing the final heading.

The changes were committed and pushed successfully to the main branch.

## 📚 Key Learnings

- Managing source code using Git.
- Understanding local and remote repositories.
- Collaborating through branches.
- Tracking changes using Git commits.
- Resolving merge conflicts.
- Recovering committed changes using Git reflog.

## 🌐 GitHub Repository

**Repository:** [anthem-workshop](https://github.com/fahadelahi08-pixel/anthem-workshop)

**GitHub Username:** [@fahadelahi08-pixel](https://github.com/fahadelahi08-pixel)

## 👨‍🎓 Student Information

**Workshop:** Git & GitHub Practice Workshop  
**Project:** National Anthem Project  
**Platform:** MacBook Air M2  
**Repository Owner:** Fahad  
**GitHub Username:** fahadelahi08-pixel

---

<p align="center">
  <b>Developed as part of the Git & GitHub Practice Workshop.</b>
  <br>
  Learning. Building. Collaborating.
</p>
