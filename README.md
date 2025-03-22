# Demo-Repository
## For Learning Git
### Reference
[Git Tutorial Video](https://www.youtube.com/watch?v=RGOj5yH7evk)

# Git and GitHub Overview

## Git
Git is a version control system (VCS) that helps developers track changes in their code, collaborate with others, and manage different versions of a project efficiently.

- **Type**: Distributed Version Control System (DVCS)
- **Usage**: Tracks changes in files, allows branching and merging, enables collaboration
- **Installation**: Needs to be installed on your local machine

### Common Commands
- `git init` → Initialize a repository
- `git add .` → Stage changes
- `git commit -m "Message"` → Commit changes
- `git push` → Push changes to a remote repository

---

## GitHub
GitHub is a cloud-based platform that provides remote hosting for Git repositories. It allows teams to collaborate, review code, and manage projects online.

- **Type**: Web-based Git repository hosting service
- **Usage**: Stores Git repositories online, provides collaboration tools like pull requests, issues, and actions
- **URL**: [https://github.com](https://github.com)

### Key Features
- Public & Private Repositories
- Pull Requests & Code Reviews
- Issues & Project Management
- GitHub Actions (CI/CD)

---

## Git Commands

```bash
# Initialize a new Git repository
git init

# Check the status of the repository
git status

# Add all changes to the staging area
git add .

# Commit changes with a message
git commit -m "Your commit message"

# Push changes to the remote repository
git push

# Push changes to the master branch of the remote repository
git push origin master

# Set up an empty repository and connect it as remote
git init
# Copy the HTTP link of the empty repository
git remote add origin <repository-link>


```
### Git Branching

To add an image in markdown, use the following syntax:

```markdown
![Alt Text](image-url)
```

For example:

```markdown
![Git Logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)
```

This will display the Git logo in your markdown file.