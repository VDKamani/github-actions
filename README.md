# github-actions

# GitHub Actions Demo

This repository contains example workflows to demonstrate the use of GitHub Actions for various tasks, such as continuous integration, deployment, linting, releases, and maintenance.

## Workflows

### 1. **Simple CI Workflow for a Node.js Project**
This workflow:
- Runs tests for a Node.js project on every push and pull request to the `main` branch.

**File**: `ci_node.yml`

---

### 2. **Build and Deploy a Static Website to GitHub Pages**
This workflow:
- Builds and deploys a React app to GitHub Pages on every push to the `main` branch.

**File**: `deploy_static_web.yml`

---

### 3. **Lint and Format Code Using Prettier**
This workflow:
- Checks and fixes code formatting using Prettier on pull requests to the `main` branch.

**File**: `code_formatter.yml`

---

### 4. **Automate Release Creation**
This workflow:
- Automatically creates a release when a new tag is pushed.

**File**: `create-release.yml`

---

### 5. **Scheduled Workflow to Clean Up Old Logs**
This workflow:
- Runs every day at midnight to clean up old log files.

**File**: `cleanup-log.yml`

---

### 6. **Multibranch : Branch wise relese**
This workflow:
- Runs interms of perticular branch, when the mentioned branch runs it will runs as well.

**File**: `multi_branch.yml`

---

### 7. **Docker deployment task**
This workflow:
- Runs the whole CICD where it will build the docker image , upload it to AWS ECR and then it will deploy it on the given ec2 details in secrets.

**File**: `docker_deployment.yml`

---

### 8. **linkdin demo**
This workflow:
- This is the demo file uploded to show the basic CI/CD function of Node Project.

**File**: `linkdin_demo.yml`

---

## How to Use
1. Copy the YAML files into your repository under the `.github/workflows/` directory.
2. Modify the workflows to fit your project's requirements.
3. Push changes to your repository and watch the workflows in the Actions tab.

## Resources
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Workflow Syntax for GitHub Actions](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)


