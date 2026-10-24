Read 
Completed with input: {
  "path": "D:\\Data_sciences_& _data_analytics\\Data_analytics]\\module-1-fundamental-ITindustry\\what is github and how to use it.md"
}

**GitHub** is a website for storing and sharing code and other project files. It helps you keep track of changes, work with other people, and publish projects.

**Git** is the version-control tool that records changes on your computer. **GitHub** hosts Git projects online so you can back them up and collaborate.

### The main ideas

- **Repository (repo):** A project’s files and their change history.
- **Commit:** A saved snapshot of changes, usually with a short message.
- **Branch:** A separate line of work where you can make changes without affecting the main version.
- **Pull request:** A proposal to review and merge changes from one branch into another.
- **Clone:** A copy of a GitHub repository on your computer.

### A beginner workflow

1. Create a GitHub account and a repository.
2. Add files, such as a README that describes the project.
3. To edit online, open a file on GitHub, choose the edit option, make your change, and commit it.
4. To work with others, create a branch, make changes, and open a pull request for review.
5. After approval, merge the pull request into the main branch.

You can also work on your computer with Git. A typical sequence is:

```bash
git clone https://github.com/username/repository.git
cd repository
# Make and save your changes
git add .
git commit -m "Describe the change"
git push
```

This copies the repository to your computer, records your changes in a commit, and uploads them to GitHub. GitHub Desktop provides a graphical interface if you prefer not to use commands.

**Tip:** Never upload passwords, API keys, private information, or files you don’t have permission to share.
