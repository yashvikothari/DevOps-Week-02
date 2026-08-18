# DevOps Week 02 Project
## DevOps Week 02 - Git and GitHub Practice
# DevOps Week 02 Project

## Project Overview

This project demonstrates basic Git and GitHub workflow practices as part of the DevOps Week 02 hands-on activity.

The project covers:

* Git repository creation
* Project file management
* Feature branch creation
* Making changes on separate branches
* Branch merging
* Pull Request workflow
* Merge conflict resolution
* README documentation
* Pushing the final project to GitHub

## Project Structure

```text
DevOps-Week-02/
├── README.md
├── app.py
├── Dockerfile
├── deploy.sh
├── requirements.txt
└── .gitignore
```

## Technologies Used

* Git
* GitHub
* Python
* Docker
* Bash

## Git Workflow

The project uses the following workflow:

```text
main
 │
 ├── feature/docker
 │
 └── feature/deployment
```

Changes were developed independently on feature branches and merged into the main branch.

## Application

The Python application contains a simple example application:

```python
print("DevOps Week 02 Application")
```

## Docker

The Dockerfile defines a lightweight Python-based container image and configures the application to run inside the container.

## Deployment

The `deploy.sh` script demonstrates a basic deployment workflow.

## Learning Outcomes

Through this activity, I practiced:

1. Creating and managing Git repositories.
2. Working with feature branches.
3. Committing and pushing changes.
4. Merging multiple branches.
5. Creating and managing Pull Requests.
6. Resolving Git merge conflicts.
7. Maintaining project documentation using README.md.

## Author

DevOps Week 02 Hands-on Project

