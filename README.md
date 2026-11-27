#   PowerBI Template Project
-----------------------------------------------------
**Necessary Setup:**
- Visual Studio Code
- Install Git
- Python

**Helpfull Extensions:**
- Github Actions
- Python

# How to:

**When you are creating a new PBI project:**
1. Click on your profile > Repositories > New 
2. Name your repository: pbi_[project_name]
3. Start with Template: Data-AI-Axians/pbi-project-template
4. Create Repository!

**When  the project has been created:**  
Cheat Sheet https://education.github.com/git-cheat-sheet-education.pdf
1. Select the Repository
2. Click on Code and copy the link shown
3. Open your Visual Studio Code Terminal
4. Git Clone [paste link]

**Create your Branch**  
1. Open your project in Visual Studio Code and open the terminal
2. Make sure you are in the main branch
    ```
    git branch
    ```
    Your current branch will have an aesterix <mark style="background-color: lightblue;"> *</mark> before it

3. Switch to the main branch and download the latest changes:

   ```bash
   git switch main
   git pull origin main
   ```

3. Create and switch to your new branch (replace `branch-name` with your branch name):

   ```bash
   git switch -c branch-name
   ```

   <div style="background-color: hsl(212, 100%, 95%); padding: 8px; border-radius: 3px;">
   Make sure your branch name is understandable, associate it with tasks or objectives — for example: <code>task_123</code> or <code>fix_turnover_chart</code>
   </div>

4. Publish your branch to GitHub:

   ```bash
   git push -u origin branch-name
   ```
   If you don't do this part, only you can see your branch!

**Save your changes to GitHub:**
1. Make your changes and save your files
2. Check which files have changed:

   ```bash
   git status
   ```

3. Add the changes to your commit. This adds all changed files in the project:

   ```bash
   git add .
   ```

4. Create a commit with a short message describing your changes:

   ```bash
   git commit -m "Describe your changes"
   ```

5. Push your commit to GitHub:

   ```bash
   git push
   ```

For future changes on the same branch, repeat these steps.

**Merge your changes on GitHub:**
1. Open your repository on GitHub
2. Select your branch and click **Compare & pull request**
3. Check that the base branch is `main`, add a description, and create the pull request
4. After the changes are reviewed, merge the pull request
