### Step 0: Install Git & Create a GitHub Account
- **Install Git** by following the instructions for your operating system.
- **Create a GitHub account** to host your repositories online.

### Step 1: Create a Local Git Repository
- Use the terminal to navigate to the project directory and initialize a Git repository with:
  ```bash
  git init
  ```

### Step 2: Add a New File to the Repository
- Add a new file using a text editor or `touch` command:
  ```bash
  touch newfile.txt
  ```
- Check the file status using:
  ```bash
  git status
  ```

### Step 3: Add the File to the Staging Environment
- Stage the file using:
  ```bash
  git add newfile.txt
  ```
- Check the status again to confirm it's staged.

### Step 4: Create a Commit
- Commit the staged changes with a message:
  ```bash
  git commit -m "Initial commit"
  ```

### Step 5: Create a New Branch
- Create a new branch for development:
  ```bash
  git checkout -b my-new-branch
  ```
- Switch back to the primary branch using `git checkout master`.

### Step 6: Create a Repository on GitHub
- On GitHub, create a new repository. 
- Link your local repository to GitHub and push your changes:
  ```bash
  git remote add origin https://github.com/yourusername/yourrepo.git
  git push -u origin master
  ```

### Step 7: Push a Branch to GitHub
- Push your branch to GitHub:
  ```bash
  git push origin my-new-branch
  ```

### Step 8: Create a Pull Request (PR)
- On GitHub, create a Pull Request (PR) to propose merging your branch into the main branch.
