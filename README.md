# Bash Calculator Project

## Overview

This project contains Bash scripts for performing basic arithmetic operations. It was created to practice Bash scripting, Linux commands, Git branches, commits, pull requests, and merging.

## Calculator Scripts

- `add.sh`: Performs addition
- `subb.sh`: Performs subtraction
- `multi.sh`: Performs multiplication
- `divide.sh`: Performs division and checks for division by zero
- `hello.sh`: Displays Codespace environment information

## Run the Scripts

Give executable permission to all scripts:

```bash
chmod +x add.sh subb.sh multi.sh divide.sh hello.sh
```

Run the scripts:

```bash
./add.sh
./subb.sh
./multi.sh
./divide.sh
./hello.sh
```

## Linux Commands Used

```bash
pwd
ls
ls -l
ls -la
cat README.md
chmod +x script-name.sh
./script-name.sh
```

## Git Commands Used

```bash
git status
git branch
git switch main
git switch -c feature/branch-name
git remote -v
git diff
git add filename
git commit -m "Commit message"
git push -u origin feature/branch-name
git pull origin main
git branch -d feature/branch-name
```

## Workflow

Each calculator operation was created on a separate feature branch, tested, committed, pushed to GitHub, and merged into `main` through a pull request.