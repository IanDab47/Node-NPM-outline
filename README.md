# HOW TO START A NODE PROJECT

## Starting a Node-based project from scratch
1. Create a new directory and open with VSC
  `mkdir <directory-name>`
  `code <directory-name>`
2. Create a 'package.json' file by initializing npm
  `npm init`
3. Create any necessary files for the project
  `touch <fileName1> <fileName2>...`
4. Install any npm programs for the project
  `npm install <programName> | npm i <programName> | 'Follow program instructions for installation'`
5. Create a '.gitignore' file with the text 'node_modules' listed inside
  `echo node_modules >> .gitignore`
6. Save all files
7. Use git to initialize, add, commit, and push your project to Github
  `git init`
  `git add .`
  `git commit -m "Created Node Project"`
  `git branch -M main`
  `git remote add origin https://github.com/IanDab47/<repository-name>.git`
  `git push origin main`

## Starting a Node-based project from a repository
1. Fork the repo off Github
2. Clone that repo into a separate directory that is easy to access
  `cd <directory-name>`
  `git clone <HTTPS-git-code-link>`
3. Open the newly cloned code in VSC
  `code .`
4. Use NPM to install all dependencies
  `npm install`
  a. If any issues occur, try initializing NPM in the project before retrying
    `npm init`
5. Save all files
