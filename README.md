# Coding Starters: Spring Boot & Flask Todo APIs

This repo contains **two very simple REST APIs**:
- A **Spring Boot Java project** (`springboot-todo`)
- A **Python Flask project** (`flask-todo`)

Both expose the same endpoints:
- `GET /todos` → returns all todos
- `POST /todos` → add a new todo

This is designed to help beginners learn **the basics of REST APIs** in two popular languages.


Git commands

Check if Git is installed:

git --version


Set your name and email (used for commits):

git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

📂 Clone a Repository

Download a project from GitHub:

git clone https://github.com/USERNAME/REPO_NAME.git
cd REPO_NAME

🔄 Update Project (pull latest changes)
git pull origin main

📝 Create a New Branch
git checkout -b my-feature


Switch between branches:

git checkout main


List all branches:

git branch

➕ Stage and Commit Changes

See which files changed:

git status


Add all changes:

git add .


Commit changes with a message:

git commit -m "Describe what I changed"

⬆️ Push Changes to GitHub
git push origin my-feature


(If first time pushing this branch:)

git push --set-upstream origin my-feature

🔀 Merge Branch into Main

Switch to main and update it:

git checkout main
git pull origin main


Merge your branch into main:

git merge my-feature


Push the updated main branch:

git push origin main

🗑️ Delete a Branch

Delete locally:

git branch -d my-feature


Delete on GitHub:

git push origin --delete my-feature

# 1. Clone repo
git clone https://github.com/USERNAME/REPO_NAME.git
cd REPO_NAME

# 2. Create new branch
git checkout -b add-todo-feature

# 3. Make changes, then stage and commit
git add .
git commit -m "Added new todo feature"

# 4. Push branch to GitHub
git push origin add-todo-feature

# 5. Switch to main, update, and merge
git checkout main
git pull origin main
git merge add-todo-feature
git push origin main
