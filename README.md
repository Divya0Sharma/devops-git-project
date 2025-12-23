# DevOps Git Project

This project demonstrates the practical use of Git and GitHub for version control within a DevOps-oriented workflow. The repository is designed to showcase how source code changes can be efficiently managed using branching, committing, merging, and conflict resolution techniques.

A simple application is used as the base to simulate real-world development activities such as feature implementation, testing, bug fixing, and experimentation. The project follows a structured Git workflow, including the use of multiple branches and meaningful commit messages to maintain a clear and traceable history.
## Branches
- feature
- test
- bugfix
- experiment

## Tools Used
- Git Bash
- GitHub
- HTML, CSS

## Commands Used
- Repository Initialization
git init

- Open Project in VS Code
code .

- First Commit
git status
git add index.html
git commit -m "Initial commit with basic HTML structure"

- Checking Repository Status
git status

- Adding Files to Staging Area
git add style.css
git commit -m "Added basic CSS styling"
git add about.html
git commit -m "Added about page"
git add contact.html
git commit -m "Added contact page"

- Viewing Commit History
git log
git log --oneline

- Creating and Switching Branches
git branch feature
git branch test
git branch bugfix
git branch experiment

git checkout feature
git checkout test
git checkout bugfix
git checkout experiment

- Merging Branches
git checkout master
git merge feature
git merge test
git merge bugfix

- Check Commit Count
git log --oneline

- Connecting to Remote GitHub Repository
git remote add origin https://github.com/Divya0Sharma/devops-git-project
git branch -M main
git push -u origin main

- Pushing Code to GitHub
git push -u origin master
git push origin feature
git push origin test
git push origin bugfix
git push origin experiment

## Command Screenshots
![](screenshots/dev1.jpg)
![](screenshots/dev2.jpg)
![](screenshots/dev3.jpg)
![](screenshots/dev4.jpg)
![](screenshots/dev5.jpg)
![](screenshots/dev6.jpg)
![](screenshots/dev7.jpg)
![](screenshots/dev8.jpg)
![](screenshots/dev9.jpg)
![](screenshots/dev10.jpg)

## Conclusion
This project successfully demonstrates the practical implementation of Git and GitHub within a DevOps workflow. By using multiple branches, performing regular commits, and managing merges, the project highlights how version control helps maintain organized and traceable source code.

The hands-on experience with branch management and merge conflict resolution reinforces the importance of structured development practices. Integration with a remote GitHub repository further emphasizes real-world usage of collaborative tools and remote version control.

Overall, this project strengthens understanding of Git fundamentals, improves workflow discipline, and reflects industry-standard practices essential for modern software development and DevOps environments.
