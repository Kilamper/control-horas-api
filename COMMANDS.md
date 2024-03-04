# Commands

All commands are run from a terminal at the root of the project.

## Git

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `git clone <url>`  | Clone a repository |
| `git add <files names>`  | Add files to staging |
| `git commit -m "<message>"` | Create commit for staged files  |
| `git push -u origin <branch name>` | Push changes to remote repository |
| `git pull origin <branch name>` | Download changes from remote repository |
| `git switch <branch name>` | Switch to a branch |
| `git switch -c <branch name>` | Create a new branch |
| `git branch`  | Show all branches |
| `git branch -d <branch name>`  | Delete a branch |
| `git reset --soft HEAD^` | Undo the last commit, keeping the changes locally, before pushing |
| `git reset --hard HEAD^`  | Undo the last commit, discarding the changes, before pushing |
| `git diff <hash commit 1> <hash commit 2>` | Compare the changes between two different commits |
| `git log`  | Show commit history |
| `git log --oneline --decorate --graph`  | Show commit history in a pretty format in the terminal |
| `git merge <branch name>`  | Merge a branch into the current branch |
| `git commit --amend -m "<fixed message>"` | Amend commit message before pushing |
| `git revert <hash commit>` | Revert changes to a specific commit, creating a new commit from the specified one. *Does not modify the original branch* |

## PNPM

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`  | Install project dependencies |
| `pnpm run dev` | Launch development environment |
| `pnpm version major` | Upgrade major version +1 |
| `pnpm version minor` | Promote minor version (feature/release) +1 |
| `pnpm version patch` | Upgrade patch version (fix) +1 |
