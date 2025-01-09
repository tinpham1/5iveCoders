# 5iveCoders

# IMDB Data Analysis

Question_1_your_name - What are the most common genres of movies released in the last decade?

Question_2_your_name - Which directors have the highest average IMDb ratings across their films?

Question_3_your_name - What is the trend of movie runtimes over the years (e.g., are movies getting longer or shorter)?

Question_4_your_name - Which actors appear most frequently in high-rated movies (e.g., IMDb ratings > 8)?

Question_5_your_name - How does budget correlate with IMDb rating (if additional budget data is added)?

Question_6_your_name - Which countries produce the highest number of movies in specific genres (e.g., Action, Drama)?

Question_7_your_name - What is the average IMDb rating of movies with a specific keyword in their plot (e.g., "alien")?

Question_8_your_name - What is the distribution of MPAA ratings (e.g., PG, PG-13, R) across different genres?

---
# GitHub Workflow

This guide outlines the workflow and conventions we follow to ensure smooth collaboration.

---

## Workflow

### 1. **Branches**
- **Main branch (`main`)**:
  - Contains stable and reviewed code.
  - Direct pushes to `main` are prohibited.
- **Feature branches**:
  - Create a new branch for each task or feature.
  - Branch naming convention: `feature/task-name` (e.g., `feature/add-data-analysis`).

### 2. **Creating a Feature Branch**
1. Switch to the main branch:
   ```bash
   git checkout main
   ```
2. Pull the latest changes:
   ```bash
   git pull origin main
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature/task-name
   ```

### 3. **Working on Your Branch**
- Commit your changes often and use descriptive commit messages.
- Example commit message:
  ```
  feat: Added new data cleaning function
  ```

### 4. **Pushing Your Branch**
Push your branch to GitHub:
```bash
git push origin feature/task-name
```

---

## Pull Requests (PRs)

### 1. **Creating a PR**
1. Navigate to the repository on GitHub.
2. Go to the **Pull Requests** tab and click **New Pull Request**.
3. Select your feature branch and compare it to `main`.
4. Add a clear title and description for the PR.
5. Assign at least one reviewer.

### 2. **Review and Approval**
- Every PR must be reviewed and approved by at least one team member before merging.
- Reviewers should:
  - Check for functionality.
  - Verify the code follows our conventions.
  - Test changes locally if necessary.

### 3. **Merging the PR**
- After approval, the PR can be merged into `main`.
- Ensure the branch is up-to-date with `main` before merging.

---

## Syncing with `main`

### 1. Pull Updates
- Frequently pull updates from `main` to avoid conflicts:
  ```bash
  git pull origin main
  ```

### 2. Merge `main` into Your Branch
- Before pushing your branch, merge the latest `main` changes:
  ```bash
  git merge main
  ```

---

## Resolving Conflicts
1. Identify conflicting files in the GitHub interface or locally.
2. Open the conflicting files and manually resolve the conflicts.
3. After resolving, add the files to staging:
   ```bash
   git add <file-name>
   ```
4. Commit the resolved changes:
   ```bash
   git commit -m "Resolved merge conflict in <file-name>"
   ```
5. Push the updated branch:
   ```bash
   git push origin feature/task-name
   ```

---

## Issues and Task Assignment
- Use the **Issues** tab to track tasks and assign responsibilities.
- Clearly define the scope of each issue and tag the relevant collaborators.

---

## Code Conventions
- Use clear and descriptive variable names.
- Follow PEP 8 (Python) or relevant language-specific style guides.
- Include comments for complex or non-obvious code sections.

---

Thank you for following this guide and contributing to our project. Happy coding!

