## Git Command Cheat Sheet:

Git is a powerful version control system that helps developers track changes to their code over time. Here are some commonly used Git commands that can be helpful in managing your code repository:

- This command creates a new local Git repository and initializes it.

```sh
git init
```

- This command creates a copy of an existing Git repository on your local machine.

```sh
git clone link
```

- Use this command to check the status of your repository and see any modified files.

```sh
git status
```

- This command adds all changes in your working directory to the staging area.

```sh
git add -all
```

- This command adds changes in the current directory to the staging area.

```sh
git add .
```

- This command adds all changed files except deleted ones to the staging area.

```sh
git add \*
```

- This command adds a specific changed file to the staging area.

```sh
git add link
```

- This command resets changes that were added to the staging area.

```sh
git reset
```

- Use this command to commit your changes to the repository with a commit message.

```sh
git commit -m "message"
```

- This command undoes the last commit and returns your repository to the previous state.

```sh
git reset HEAD~
```

- Use this command to create a new Git branch with the given name.

```sh
git branch name
```

- Use this command to switch to the Git branch with the given name.

```sh
git checkout name
```

-Use this command to list all the branches in your repository.

```sh
git branch
```

- Use this command to merge changes from a different branch into your current branch.

```sh
git merge name
```

- Use this command to transfer your local repository changes to an online GitHub repository.

```sh
git push origin name
```

- This command is equivalent to running git fetch and git merge together.

```sh
git pull
```


