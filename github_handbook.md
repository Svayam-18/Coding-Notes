# GitHub Student Handbook

*A complete practical guide for beginners and future developers*

---

## Module 1 — Foundations of Version Control

1. What is Version Control?  
2. What is Git?  
3. What is GitHub?  
4. Git vs GitHub  
5. Why Companies Use Git and GitHub  
6. How Teams Collaborate Using GitHub  

---

## Module 2 — Setup and First Contact

7. Creating a GitHub Account  
8. Installing Git on Your Computer  
9. Configuring Git (Name and Email)  
10. Creating Your First Repository  
11. Cloning a Repository  
12. Connecting VS Code with GitHub  

---

## Module 3 — Daily Git Workflow

13. Understanding Project Folder Structure  
14. Checking File Status  
15. Staging Files  
16. Making Commits  
17. Writing Professional Commit Messages  
18. Pushing Changes to GitHub  
19. Pulling Updates from GitHub  

---

## Module 4 — Branching and Merging

20. Understanding Branches  
21. Creating and Switching Branches  
22. Working on Feature Branches  
23. Merging Branches  
24. Resolving Merge Conflicts  

---

## Module 5 — Team Collaboration

25. Forking Repositories  
26. Creating Pull Requests  
27. Code Review Basics  
28. Handling Review Feedback  
29. Using Issues for Bug Tracking  
30. Introduction to Project Boards  

---

## Module 6 — Professional GitHub Usage

31. Writing a Strong README File  
32. Documenting Your Projects  
33. Maintaining Clean Commit History  
34. Optimizing Your GitHub Profile  
35. Using GitHub as Your Developer Portfolio  

---

## Module 7 — Advanced but Practical

*Stuff companies love but beginners rarely learn properly*

36. `.gitignore`  
37. Reverting commits  
38. Stashing work  
39. Tagging versions  
40. Release management basics  

---
---
# Module 1 — Foundations of Version Control

---

## 1. What is Version Control?

> *“Version control is the memory of your project.”*

### Concept Explanation

When you write a program, you rarely finish it in one attempt.  
You keep changing it — fixing bugs, adding features, removing mistakes, improving structure.

After a few days, questions appear:

- Which version was working?
- What exactly did I change yesterday?
- Can I go back if today’s code breaks?

**Version Control** is a system that:

- records every change made to your files  
- stores the complete history of the project  
- allows you to return to any previous version  
- helps multiple people work safely on the same code  

Think of it as the **save system of a video game**.  
If today’s save is broken, you simply load yesterday’s.

---

### Why This Matters in Real Work

In professional development:

- dozens of developers work on the same project  
- mistakes are unavoidable  
- features are developed simultaneously  

Without version control:

- people overwrite each other’s work  
- bugs destroy stable versions  
- teamwork becomes impossible  

Version control creates **order, safety, and accountability**.

---

### Key Terms

| Term | Meaning |
|------|--------|
| Repository | Main project folder with full history |
| Commit | Saved checkpoint |
| History | All previous versions |
| Revert | Go back to an older version |
| Branch | Independent line of development |

---

### Example — Without Version Control

```
project_v1
project_v2
project_v3
final_project
final_project_fixed
final_project_really_fixed
```

### With Version Control

```
Project
 └── History
      ├── Version 1
      ├── Version 2
      ├── Version 3
      └── Version 4
```

One folder. Full safety.

---

### Common Mistakes

- Keeping many backup folders  
- Editing final versions directly  
- Losing track of working code  

---

### Practice

1. Write two reasons why version control is important.  
2. Describe a situation where version control could have saved your work.

---

## 2. What is Git?

> *“Git is the engine of version control.”*

### Concept Explanation

**Git** is a software that runs on your computer and performs version control.

Git allows you to:

- track file changes  
- save checkpoints  
- create separate work branches  
- merge work safely  
- recover lost versions  
- work offline  

Git is the most widely used version control system in the world.

---

### Why This Matters

Every serious software company uses Git.  
Knowing Git is not optional — it is essential.

---

### Core Concepts

| Concept | Meaning |
|-------|---------|
| Working Directory | Your project folder |
| Staging Area | Files prepared for commit |
| Repository | Where history is stored |
| Commit | Saved snapshot |

---

### Basic Git Flow

```
Edit → Stage → Commit → Repeat
```

---

### Common Mistakes

- Making huge commits  
- Forgetting to commit regularly  
- Not checking status before committing  

---

### Practice

1. Research why Git was created.  
2. Explain the difference between saving a file and committing.

---

## 3. What is GitHub?

> *“GitHub is the home of your projects on the internet.”*

### Concept Explanation

**GitHub** is a website that stores Git repositories online and enables collaboration.

It provides:

- online backup  
- team collaboration  
- pull requests  
- issue tracking  
- project management  
- portfolio building  

Your GitHub profile becomes your **technical identity**.

---

### Why This Matters

Companies host products on GitHub.  
Recruiters judge your skills using GitHub.  
Developers collaborate using GitHub.

---

### Git vs GitHub

| Git | GitHub |
|-----|--------|
| Software | Online platform |
| Local | Cloud |
| Tracks changes | Hosts projects |
| Manages history | Enables teamwork |

---

### Common Mistakes

- Confusing Git with GitHub  
- Using GitHub without understanding Git  

---

### Practice

1. Create a GitHub account.  
2. Explore trending repositories.

---

## 4. Git vs GitHub

Git is the engine.  
GitHub is the collaboration platform.  

Both are required.

---

## 5. Why Companies Use Git and GitHub

Companies require:

- stability  
- collaboration  
- accountability  
- safety  
- history tracking  

Git and GitHub provide all of this.

---

## 6. How Teams Collaborate Using GitHub

Teams collaborate using:

- branches  
- pull requests  
- code reviews  
- issues  

Direct edits to main branch are avoided.

---

# Module 2 — Setup and First Contact

---

## 7. Creating a GitHub Account

Visit **https://github.com**  
Create an account  
Verify your email  
Choose a professional username  

Your username becomes part of your career.

---

## 8. Installing Git

Download Git from:  
https://git-scm.com  

Install with default settings.

Verify installation:

```
git --version
```

Expected output:

```
git version 2.x.x
```

---

## 9. Configuring Git

Set your identity:

```
git config --global user.name "Your Name"
git config --global user.email "you@email.com"
```

Check configuration:

```
git config --list
```

---

## 10. Creating Your First Repository

Create repository on GitHub.  
Add README file.  
Choose public.

---

## 11. Cloning a Repository

```
git clone https://github.com/username/project.git
```

Expected output:

```
Cloning into 'project'...
Receiving objects...
Resolving deltas...
```

---

## 12. Connecting VS Code with GitHub

Open project in VS Code.  
Open Source Control panel.  
Sign in to GitHub.

---

## 13. Understanding Project Structure

```
project/
 ├── README.md
 ├── src/
 ├── docs/
 └── .gitignore
```

---

## 14. Checking File Status

```
git status
```

---

## 15. Staging Files

```
git add .
```

---

## 16. Making Commits

```
git commit -m "Initial commit"
```

---

## 17. Writing Professional Commit Messages

Good commits are:

- short  
- descriptive  
- written in present tense  

---

## 18. Pushing Changes

```
git push origin main
```

---

## 19. Pulling Updates

```
git pull origin main
```
---




---

# Module 3 — Daily Git Workflow

---

## 20. Understanding the Daily Git Cycle

> *“This module transforms Git from a tool you know into a habit you live with.”*

### Concept Explanation

Every professional developer follows the same working cycle every day.

Whenever you start coding, the flow should be:

```

Edit → Check → Stage → Commit → Push

```

This cycle keeps your project:

- safe  
- structured  
- recoverable  
- easy to understand  

If you skip this discipline, your project becomes fragile and confusing.

---

### Why This Matters in Real Work

In real companies, developers make dozens of commits every week.  
Following a strict workflow prevents:

- broken builds  
- lost work  
- team conflicts  
- messy project history  

---

### Common Mistakes

- Editing code without checking project state  
- Making large, unclear commits  
- Forgetting to push work  

---

### Practice

1. Write the daily Git cycle on paper.  
2. Follow it during your next coding session.

---

## 21. Checking the Current Project State

### Concept Explanation

Before making any change, you must understand what state your project is in.

### Command

```

git status

```

### Example Output

```

On branch main
Changes not staged for commit:
modified: index.html

Untracked files:
notes.txt

```

This tells you exactly what Git sees.

---

### Why This Matters

`git status` prevents accidental mistakes and gives you complete control over your work.

---

### Common Mistakes

- Skipping `git status`  
- Committing without reviewing changes  

---

### Practice

Modify any file and run `git status`.

---

## 22. Understanding Tracked and Untracked Files

### Concept Explanation

Tracked files are already known to Git.  
Untracked files are new files that Git has never seen before.

To start tracking a file:

```

git add filename

```

Once added, the file becomes part of your project history.

---

### Why This Matters

Understanding file tracking prevents accidental commits and lost files.

---

### Practice

Create a new file and observe the output of `git status`.

---

## 23. Staging Files

### Concept Explanation

Staging means selecting which changes will be saved in the next commit.

### Commands

```

git add filename

```
```

git add .

```

Staging allows you to control your save precisely.

---

### Why This Matters

Staging prevents unwanted files from entering your commit.

---

### Practice

Stage one file only, then stage all files.

---

## 24. Making Commits

### Concept Explanation

A commit is a permanent checkpoint of your project.

### Command

```

git commit -m "Add login validation"

```

Good commits:

- contain one logical change  
- explain clearly what was done  
- are easy to understand later  

Bad commits:

```

updated stuff

```
```

fixed things

```

---

### Why This Matters

Good commit history makes your project easy to understand and maintain.

---

### Practice

Make two commits for two different changes.

---

## 25. Viewing Commit History

### Command

```

git log

```

This shows the complete memory of your project.

Each commit contains:

- ID  
- Author  
- Date  
- Message  

---

### Why This Matters

Your project becomes traceable and recoverable.

---

### Practice

Run `git log` and study your commit history.

---

## 26. Pushing Work to GitHub

### Command

```

git push origin main

```

This sends your work from your computer to GitHub.

---

### Why This Matters

If you do not push, your work exists only on your machine.

---

### Practice

Push your latest commit to GitHub.

---

## 27. Pulling Updates from GitHub

### Command

```

git pull origin main

```

This downloads the latest version of the project from GitHub.

Always pull before starting new work.

---

### Why This Matters

Pulling first prevents conflicts and lost work.

---

### Practice

Run `git pull` before your next coding session.

---

## 28. Fixing Common Workflow Problems

### Forgot to add a file?

```

git add forgotten_file
git commit --amend

```

### Wrong commit message?

```

git commit --amend -m "Correct message"

```

---

### Why This Matters

These commands help you fix mistakes without breaking project history.

---

## 29. Daily Professional Routine

Every working session:

1. `git pull`  
2. write code  
3. `git status`  
4. `git add`  
5. `git commit`  
6. `git push`  

This is how real developers work.

---

### Practice

Follow this routine for your next five coding sessions.

---

## 30. End of Module Challenge

Create a small project and perform the full workflow at least five times.  
By the end, this cycle should feel natural and automatic.

---

---

# Module 4 — Branching and Merging

---

## 31. Understanding Branches

> *“Branches allow you to work without breaking the main project.”*

### Concept Explanation

A **branch** is a separate line of development inside the same project.  
It allows you to experiment, build features, and fix bugs without affecting the main working code.

The default branch is called **main**.

When you create a branch, Git makes a copy of your project at that moment.  
You can change that copy freely.

---

### Why This Matters in Real Work

In real companies, developers **never** work directly on the main branch.

They create new branches for:
- new features  
- bug fixes  
- experiments  

This prevents:
- breaking production code  
- overwriting others’ work  
- losing stable versions  

---

### 🧪 Practice

Create a new branch and move into it.

---

## 32. Creating and Switching Branches

### 📌 Commands

Create a new branch:

```

git branch feature-login

```

Switch to the branch:

```

git checkout feature-login

```

Create and switch in one step:

```

git checkout -b feature-login

```

---

### 🧠 Explanation

These commands allow you to move between different development paths safely.

---

### 🧪 Practice

Create a branch named `test-feature` and switch to it.

---

## 33. Working on Feature Branches

### Concept Explanation

When you are on a branch, every change you make stays inside that branch.

You can:
- edit files  
- commit changes  
- experiment freely  

The main branch remains untouched.

---

### 🧪 Practice

Modify a file and commit it while staying on your new branch.

---

## 34. Merging Branches

### Concept Explanation

Merging combines the work from one branch into another.

Usually, you merge your feature branch into the main branch after your work is complete.

---

### 📌 Commands

First, switch back to main:

```

git checkout main

```

Then merge your feature branch:

```

git merge feature-login

```

---

### 🧠 Explanation

If there are no conflicts, Git combines both branches automatically.

---

### 🧪 Practice

Merge your test branch into main.

---

## 35. Resolving Merge Conflicts

### Concept Explanation

A **merge conflict** happens when two branches change the same line of a file differently.

Git cannot decide which version is correct, so it asks you to fix it manually.

---

### 🛠 How to Resolve a Conflict

1. Open the conflicted file  
2. Look for conflict markers  
3. Choose the correct code  
4. Delete conflict markers  
5. Save the file  
6. Add and commit the fix  

---

### 🧪 Practice

Create a conflict between two branches and resolve it.

---

## 36. Deleting Branches

### Concept Explanation

After a branch is merged, it should be removed to keep the project clean.

---

### 📌 Command

```

git branch -d feature-login

```

---

### 🧪 Practice

Delete your test branch after merging it.

---

## 37. End of Module Challenge

Create two feature branches.  
Make changes in both.  
Merge them into main.  
Delete the old branches.

If you complete this challenge, you understand branching.

---
---
# Module 5 — Team Collaboration

---

## 38. Why Team Collaboration Matters

> *“Software is built by teams, not individuals.”*

### Concept Explanation

Modern software projects involve many developers working on the same codebase.  
Without proper collaboration, projects quickly become chaotic.

Team collaboration using Git and GitHub ensures that:
- work is divided safely  
- changes are reviewed before merging  
- mistakes are caught early  
- every contributor is accountable  

---

### Why This Matters in Real Work

Every professional company uses GitHub for collaboration.  
Knowing how to collaborate is as important as knowing how to code.

---

### 🧪 Practice

List three reasons why collaboration is essential in software development.

---

## 39. Forking Repositories

### Concept Explanation

**Forking** creates your own copy of someone else’s repository on GitHub.  
It allows you to experiment and make changes without affecting the original project.

---

### 📌 Steps

1. Open a repository on GitHub  
2. Click **Fork**  
3. GitHub creates a copy under your account  

---

### 🧪 Practice

Fork any open-source repository.

---

## 40. Cloning a Fork

### Concept Explanation

After forking, you clone the project to your computer.

---

### 📌 Command

```bash
git clone https://github.com/your-username/repository-name.git
````

---

### 🧪 Practice

Clone your forked repository.

---

## 41. Creating Feature Branches for Team Work

### Concept Explanation

In team projects, every task is done on its own branch.

This prevents conflicts and protects the main code.

---

### 📌 Commands

Create a new feature branch:

```bash
git checkout -b feature-update-readme
```
```
---

### 🧪 Practice

Create a branch for a small change.

---

## 42. Committing and Pushing Team Work

### Concept Explanation

After finishing your task, you commit and push your work.

---

### 📌 Commands

```bash
git add .
```

```bash
git commit -m "Update README formatting"
```

```bash
git push origin feature-update-readme
```

---

### 🧪 Practice

Make a commit and push it to your feature branch.

---

## 43. Opening a Pull Request

### Concept Explanation

A **Pull Request (PR)** asks the main project to review and merge your changes.


### Steps

1. Open your repository on GitHub
2. Click **Compare & pull request**
3. Write a clear description
4. Submit the pull request

### Practice

Open a pull request for your branch.

---

## 44. Code Review Process

### Concept Explanation

Other developers review your pull request before merging.

They:

* check logic
* suggest improvements
* catch bugs

This process improves code quality.

---

### Practice

Review a pull request in any public repository.

---

## 45. Updating Your Branch from Main

### Concept Explanation

While you work, the main branch may change.
You must update your branch before merging.

---

### Commands


```bash
git checkout main
```

```bash
git pull origin main
```

```bash
git checkout feature-update-readme
```

```bash
git merge main
```

---

### Practice

Update your branch with the latest main changes.

---


## 46. Merging Pull Requests

### Concept Explanation

After approval, your pull request is merged into main.

This integrates your work into the project.

---

### Practice

Merge your pull request.

---

## 47. End of Module Challenge

Participate in one real GitHub project:

* Fork it
* Create a feature branch
* Commit and push changes
* Open a pull request
* Respond to review comments
* Merge your work

Perfect — now we move into the power-user zone.
Here is **Module 6 — Advanced Git Operations**, written in the **same high-quality handbook format**, clean visuals, and correct code formatting.

Paste this **directly after Module 5** in your single `.md` file.

---
---

# Module 6 — Advanced Git Operations

---

## 48. Understanding the Git Internals (High Level)

> *“Advanced Git begins when you stop seeing commands and start seeing states.”*

### Concept Explanation

Git does not simply save files.  
It tracks **snapshots of your project over time**.

Internally, Git manages:
- commits  
- branches  
- pointers  
- the HEAD reference  

Understanding this makes every advanced command easier.

---

###  Practice

Draw the relationship between:
`Working Directory → Staging Area → Repository`

---

## 49. Undoing Changes Safely

### Concept Explanation

Mistakes happen.  
Git gives you multiple safe ways to undo them.

---

### Undo unstaged changes

```bash
git restore filename
````

---

### Unstage a staged file

```bash
git restore --staged filename
```
```
---

### Practice

Modify a file, stage it, then undo both steps.

---

## 50. Reset vs Revert

### Concept Explanation

Both undo commits — but differently.

| Command  | Effect                                   |
| -------- | ---------------------------------------- |
| `reset`  | Moves HEAD backward (rewrites history)   |
| `revert` | Creates a new commit that undoes changes |

---

### Reset last commit

```bash
git reset --soft HEAD~1
```

---

### Revert last commit

```bash
git revert HEAD
```

---

### Practice

Create a commit and try both commands.

---

## 51. Stashing Work

### Concept Explanation

Stashing temporarily saves unfinished work without committing.

---

###  Commands

```bash
git stash
```

```bash
git stash list
```

```bash
git stash apply
```

---

###  Practice

Stash your changes, switch branches, restore them.

---

## 52. Tagging Versions

### Concept Explanation

Tags mark important project versions like releases.

---

###  Create a tag

```bash
git tag v1.0
```

---

###  Push tags

```bash
git push origin v1.0
```

---

###  Practice

Create and push a tag.

---

## 53. Cleaning the Working Directory

### Concept Explanation

Remove unwanted untracked files safely.

---

###  Commands

```bash
git clean -n
```

```bash
git clean -f
```

---

###  Practice

Create temporary files and clean them.

---

## 54. Viewing Detailed History

###  Command

```bash
git log --oneline --graph --all
```

This shows the full project history visually.

---

###  Practice

Run the command and study your project history.

---

## 55. Rewriting History (Interactive Rebase)

### Concept Explanation

Rebase lets you modify past commits.

---

###  Command

```bash
git rebase -i HEAD~3
```

---

###  Practice

Change commit messages using rebase.

---

## 56. End of Module Challenge

Create a messy history, then:

* stash work
* reset commits
* revert mistakes
* tag a version
* clean files
* rewrite history
Perfect — this is your **capstone module**.
Here is **Module 7 — Advanced but Practical**, written in the same clean handbook format and with the formatting fixes applied.

Paste this directly after **Module 6** in your single `.md` file.

---
---
# Module 7 — Advanced but Practical

> *“Stuff companies love but beginners rarely learn properly.”*
---

## 57. Understanding `.gitignore`

### Concept Explanation

`.gitignore` tells Git which files it should **never track**.

This is used for:
- secret files  
- build files  
- system files  
- logs  
- temporary files  

---

### Example `.gitignore`

```bash
node_modules/
.env
.DS_Store
*.log
````

---

###  Practice

Create a `.gitignore` file and add entries for temporary files.

---

## 58. Reverting Commits

### Concept Explanation

Reverting creates a new commit that cancels the effect of an old commit.

---

###  Command

```bash
git revert commit_id
```
```
---

###  Practice

Revert one of your previous commits.

---

## 59. Stashing Work Properly

### Concept Explanation

Stashing allows you to pause work and resume later.

---

###  Commands

```bash
git stash
```

```bash
git stash pop
```

---

###  Practice

Stash your work, switch branches, and restore it.

---

## 60. Tagging Versions

### Concept Explanation

Tags represent official versions of your project.

---

### Commands

```bash
git tag v2.0
```

```bash
git push origin v2.0
```

---

###  Practice

Create and push a version tag.

---

## 61. Release Management Basics

### Concept Explanation

A release is a packaged version of your software.

Releases include:

* version number
* release notes
* attached files

They communicate progress to users and teams.

---

###  Practice

Create a release on GitHub using your latest tag.

---

## 62. Final Project Challenge

Build a real project and apply:

* professional workflow
* branching
* pull requests
* version tags
* releases
* collaboration

When finished, you will be working at **industry level**.

