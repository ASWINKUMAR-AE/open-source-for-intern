# Open Source for Intern

This project is created to help students learn the basic open-source contribution process.

Students will learn how to:

* Fork a GitHub repository
* Clone the repository to their computer
* Create a new branch
* Make changes in the project
* Install requirements
* Add and commit changes
* Push changes to GitHub
* Create a Pull Request

---

## Repository Link

```bash
https://github.com/dravidpa7/open-source-for-intern.git
```

---

## What is Open Source?

Open source means the project code is publicly available.

Anyone can:

* Read the code
* Learn from the code
* Fix mistakes
* Add new features
* Improve the project

In this project, students will practice how to contribute to an open-source project step by step.

---

## Step 1: Fork the Repository

First, open the project repository in your browser:

```bash
https://github.com/dravidpa7/open-source-for-intern.git
```

Click the **Fork** button on the top-right side.

This will create a copy of the project in your own GitHub account.

Example:

```bash
Original Repo:
dravidpa7/open-source-for-intern

Your Forked Repo:
your-username/open-source-for-intern
```

---

## Step 2: Clone the Repository

After forking, clone your forked repository to your computer.

```bash
git clone https://github.com/your-username/open-source-for-intern.git
```

Replace `your-username` with your GitHub username.

Example:

```bash
git clone https://github.com/dhanush/open-source-for-intern.git
```

---

## Step 3: Go Inside the Project Folder

```bash
cd open-source-for-intern
```

Now you are inside the project folder.

---

## Step 4: Create a Virtual Environment

Create a Python virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

For Windows:

```bash
venv\Scripts\activate
```

For Mac/Linux:

```bash
source venv/bin/activate
```

---

## Step 5: Install Requirements

Install all required packages from `requirements.txt`.

```bash
pip install -r requirements.txt
```

This command will install the packages needed to run the project.

---

## Step 6: Create a New Branch

Before making changes, create a new branch.

```bash
git checkout -b your-branch-name
```

Example:

```bash
git checkout -b add-my-task
```

Why do we create a branch?

Because we should not directly work on the main branch.
A branch helps us safely make changes separately.

---

## Step 7: Make Your Changes

Now open the project in VS Code or any code editor.

Example command:

```bash
code .
```

Make your changes in the project.

Example changes students can make:

* Add a new function
* Fix spelling mistakes
* Improve comments
* Add a new Streamlit task
* Improve README content
* Fix small bugs

---

## Step 8: Check Your Changes

To see which files changed, run:

```bash
git status
```

This command shows the files you edited.

---

## Step 9: Add Your Changes

Add all changed files:

```bash
git add .
```

This prepares your changes for commit.

---

## Step 10: Commit Your Changes

Commit means saving your changes with a message.

```bash
git commit -m "Add my new task"
```

Example commit messages:

```bash
git commit -m "Add student grade task"
git commit -m "Fix spelling mistake in README"
git commit -m "Add new Streamlit function"
```

---

## Step 11: Push Your Branch to GitHub

Push your branch to your GitHub fork.

```bash
git push origin your-branch-name
```

Example:

```bash
git push origin add-my-task
```

---

## Step 12: Create a Pull Request

After pushing, go to your forked repository on GitHub.

You will see a button like:

```text
Compare & pull request
```

Click that button.

Then add a simple Pull Request title and description.

Example title:

```text
Add student grade task
```

Example description:

```text
I added a new beginner-friendly student grade task in the Streamlit app.
```

Then click:

```text
Create pull request
```

---

## Full Git Command Flow

```bash
# Clone your forked repo
git clone https://github.com/your-username/open-source-for-intern.git

# Go inside the project
cd open-source-for-intern

# Create virtual environment
python -m venv venv

# Activate virtual environment - Windows
venv\Scripts\activate

# Activate virtual environment - Mac/Linux
source venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Create new branch
git checkout -b add-my-task

# Check file changes
git status

# Add changes
git add .

# Commit changes
git commit -m "Add my new task"

# Push branch
git push origin add-my-task
```

---

## Important Git Commands

### Check current branch

```bash
git branch
```

### Check file changes

```bash
git status
```

### Create new branch

```bash
git checkout -b branch-name
```

### Add files

```bash
git add .
```

### Commit changes

```bash
git commit -m "your message"
```

### Push changes

```bash
git push origin branch-name
```

---

## Simple Example Contribution

Student wants to add a new task.

### Step 1: Create branch

```bash
git checkout -b add-even-odd-task
```

### Step 2: Edit the code

Add or improve the Even/Odd task in the project.

### Step 3: Add changes

```bash
git add .
```

### Step 4: Commit changes

```bash
git commit -m "Add even or odd task"
```

### Step 5: Push branch

```bash
git push origin add-even-odd-task
```

### Step 6: Create Pull Request

Go to GitHub and click **Compare & pull request**.

---

## Pull Request Rules for Students

Before creating a Pull Request:

* Make sure your code is working
* Do not edit unrelated files
* Use a clear branch name
* Use a clear commit message
* Explain what you changed in the Pull Request description

---

## Good Branch Name Examples

```bash
add-login-task
fix-readme-spelling
add-simple-interest-task
improve-streamlit-ui
```

---

## Good Commit Message Examples

```bash
Add login validation task
Fix typo in README
Improve Streamlit task comments
Add student marks calculator
```

---

## Common Problems and Fixes

### Problem 1: `git` is not recognized

Git is not installed or not added to PATH.

Fix: Install Git from the official Git website and restart your terminal.

---

### Problem 2: Permission denied while pushing

You may be pushing to the original repository instead of your fork.

Fix: Check your remote URL:

```bash
git remote -v
```

It should show your GitHub username.

---

### Problem 3: Forgot to create a branch

Create a branch before pushing:

```bash
git checkout -b your-branch-name
```

Then add, commit, and push again.

---

### Problem 4: requirements.txt not installing

Make sure you are inside the project folder.

```bash
cd open-source-for-intern
```

Then run:

```bash
pip install -r requirements.txt
```

---

## Final Contribution Flow

```text
Fork
↓
Clone
↓
Create Branch
↓
Install Requirements
↓
Make Changes
↓
Git Add
↓
Git Commit
↓
Git Push
↓
Create Pull Request
```

---

## Goal of This Project

The goal of this project is not only to write code.

The main goal is to help students understand how real open-source contribution works.

By completing this project, students will get practical experience with Git, GitHub, branches, commits, and pull requests.
