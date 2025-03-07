---
name: Onboarding Developer Tasks
about: Template for onboarding new developers to the Recall Analysis WebApp project.
title: "[Onboarding] New Developer Tasks"
labels: good first issue
assignees: ''

---

2. **Set Up Development Environment:**
- Install dependencies:
  ```
  npm install
  ```
- Set up your SQL database with the necessary tables for recall data.

3. **Start Development:**
- Begin implementing features or fixes in the `dev` branch.

### **Step 2: Fork Current Repository and Complete Task 1 and 2**

- **Objective:** Fork the repository, update the `dev` branch, and create a personal feature branch.

**Steps:**

1. **Fork the Repository:**
- Go to the GitHub repository and click the "Fork" button in the top-right corner.

2. **Clone Your Fork:**
- Clone your forked repository to your local machine:
  ```
  git clone git@github.com:[Your GitHub Username]/Recall-Analysis-WebApp.git
  cd Recall-Analysis-WebApp
  ```

3. **Add Upstream Remote:**
- Add the original repository as an upstream remote:
  ```
  git remote add upstream git@github.com:sys-hackathon/Recall-Analysis-WebApp.git
  ```

4. **Complete Task 1: Update `dev` Branch and Propose Changes**

- **Objective:** Update the pre-existing `dev` branch with the latest changes from `main` and propose improvements or fixes.

**Steps:**

1. **Fetch and Merge:**
   ```
   git fetch origin
   git checkout dev
   git merge origin/main
   ```

2. **Make Changes:**
   - Implement any necessary changes or improvements in the `dev` branch.

3. **Commit Changes:**
   ```
   git commit -m "Update: [Brief description of changes]"
   ```

4. **Push Changes:**
   ```
   git push origin dev
   ```

5. **Create a Pull Request:**
   - Go to the GitHub repository and create a pull request from `dev` to `main`.

5. **Complete Task 2: Create Own Branch with Good Naming Convention**

- **Objective:** Create a new branch for personal development work following a good naming convention.

**Steps:**

1. **Create Branch:**
   ```
   git checkout -b feature/[your-initials]-[brief-description]
   ```
   Example: `feature/jd-add-user-authentication`

2. **Work on Your Feature:**
   - Implement your feature or fix in this new branch.

3. **Commit Changes:**
   ```
   git commit -m "Add: [Brief description of feature or fix]"
   ```

4. **Push Branch:**
   ```
   git push -u origin feature/[your-branch-name]
   ```

## Additional Information

- **GitHub Username:** [Your GitHub Username]
- **Any Questions or Concerns:** [Please write any questions or concerns here]

---

**Note:** Please complete these tasks in order. Once you've completed each step, update this issue with your progress or any issues you encounter. Remember to follow our [Contributing Guide](CONTRIBUTING.md) for best practices.
