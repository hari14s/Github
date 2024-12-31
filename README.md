# Github tutorial

## How to Commit it to Local Git Repository:

To intialise the git repository:
`git init`

To add it to the staging area:
`git add .`

To commit it to the local git repository:
`git commit -m "<commit-msg>"`

## How to Push Code to GitHub:

Follow these steps to push your code to a GitHub repository:

### Step 1: Add a Remote Repository
Use the following command to add a remote repository:
```bash
git remote add <remote_name> <github-repo-url>
```
`<remote_name>`: This is the name you assign to the remote repository, which is usually origin by convention.

`<github-repo-url>`: The URL of your GitHub repository.

Example:
```bash
git remote add origin https://github.com/your-username/your-repo.git
```

### Step 2: Push Your Code
Push your code to the specified branch of the remote repository:
```bash
git push -u <remote_name> <branch_name>
```
`<remote_name>`: The name of the remote repository, typically origin.

`<branch_name>`: The name of the branch you are pushing to, which is usually main (default branch).

## How to clone a Github Repo to your dektop:

Use the command: `git clone <github-repo-url>`
