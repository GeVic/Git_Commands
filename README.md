# Git_Commands
Quick reference for Git Commands

### Prepare Repository
- Initialize the current directory with an empty repository.
   - `git init`
- Clone Repository
  - `git clone <url> <dir>`
  
### Configure Repository
- To view current configurations
  - `git config --list`
- Set Username
  - 'git config user.name <"username">'
- Set Email
  - `git config user.email <"email">`
- Change default editor
  - `git config core.editor <editor>`
  
### Working with repository
- Show working directory status
  - `git status`
- Add file to index for next commit
  - `git add <file>`
  - `git add .`  (to add all files at once)
- Remove file from the index
  - `git reset --<file>`
- Discard file modification
  - `git checkout --<file>`
- Remove file from the current working directory
  - `git rm <file>`
- To commit changes
  - `git commit -m <"commit message">`
- Replace last commit of the current branch with current index
  - `git commit --amend`
- To view commit logs
  - `git log -n <number>`
  - `git shortlog` (To view shorter commit log)
  - `git shortlog -s` (Short log summary)
  - `git log --onelne` (Shows commits in one line)
- Remove untracked files from the repository
  - `git clean -i`
  
