//To have all the code managed in git and GitHub (everything is local) you have to use:
//Git official website where you can download git (2.43.0): https://git-scm.com/
//GitHub: https://github.com/

//Git is a source code version management system.
//GitHum is a place in the cloud where you can store your source code so you can reach it everywhere and everytime you need.

//GitHub Dave Gray repository example: https://github.com/gitdagray/html_course.git
//////IF you want use my first repository instead: https://github.com/antox73/git-code-playground.git
//command to add git repository from github: git clone https://github.com/gitdagray/html_course.git
//command to remove git repository: rm -rf .git
//command to init git and create file .git: git init
//command to view the status of source files: git status
//U stays for Untracked
//If there are some files in project that you don't want to track, you can insert these in a special file called .gitingnore under file git.
//To add traking of source files now you can type: git add .
//A stays for Added (staged and ready for commit)
//M stays for Modified
//To commit the source files: git commit -m "comment!"
//You can commit also directly from M status: git commit -a -m "comment!"
//To commit is mandathory to say who you are using:
//git config --global user.email "you@example.com"
//git config --global user.name "Your Name"
//I've created a github account and new repository called git-code-playground
//I've linked github repository to this (local) git repository:
//git remote add origin https://github.com/antox73/git-code-playground.git
//git branch -M main
//git push -u origin main
