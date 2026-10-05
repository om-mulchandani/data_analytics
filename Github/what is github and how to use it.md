GitHub is a website for storing and collaborating on projects that use **Git**. Git tracks changes to files over time; GitHub hosts Git repositories online so you can back them up, share them, and work with others.

A basic workflow:

1. **Create a GitHub account** at [github.com](https://github.com).
2. **Create a repository** (repo) for your project. Choose public if anyone can view it, or private if access should be limited.
3. **Put files in the repo.** You can upload them on GitHub’s website, or use Git from a terminal:
   ```bash
   git clone https://github.com/USERNAME/REPOSITORY.git
   ```
4. **Record your changes** from the project folder:
   ```bash
   git add .
   git commit -m "Describe the changes"
   ```
   A commit is a saved snapshot of your work.
5. **Send commits to GitHub:**
   ```bash
   git push
   ```
6. **Get the latest changes** from GitHub:
   ```bash
   git pull

   # github commands for upload data on repository
   
   1. create account on github
   2. create a repository on github
3. upload data using gitbash software

  # upload data via git bash software

  #commands are

 

1. git init
2. git add .
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/om-mulchandani/data_analytics.git
6. git push -u origin main
   ```

For changes you want reviewed before adding them to the main project, create a **branch**, make commits there, then open a **pull request** on GitHub. A pull request lets people review and discuss the changes before merging them.

In short: **Git tracks your project’s history; GitHub hosts that history and provides tools for collaboration.**