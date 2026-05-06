# DAY 1

## TOPICS
- Installing VS Code + extensions
- Terminal basics (bash/zsh)
- Git init, clone, status, add, commit
- SSH keys & GitHub setup
- Folder structure conventions

## Claude Topics

- Ask Claude to explain a terminal command you don't understand
- Use Claude to generate a .gitignore for your stack
- Prompt: 'Explain what git staging area means in simple terms'

## SAMPLE PROJECT
**Project**: Personal dev setup doc
Create a markdown README documenting your entire local setup — tools, versions, and why each was chosen.
Use Claude to help write cleaner explanations.


---

## 1. Installing vscode and extensions

Installed version : **1.119**

Extensions installed
- Claude Code : To access the Claude with native UI instead of terminal
- Prettier ESLint : To structure the code properly
- Material Icons : To enhance the look of folder structure

## 2. Terminal Basics

- Mkdir : to create the directory
- cd : to change the directory
- ni : to create the file
- rm : to remove the file
- mv : to move the file from one directory to another directory

## 3. Git commands

- init : To initialize the git repository in the current directory
- clone : To clone the existing git repo in our codebase
- status : Used to know the status of stagged and unstagged files
- add : Used to add the unstaged files to commit
- commit - Used to commit the changes

## 4. SSH Keys and Github setup

Using the personal github account for now.

## 5. Folder Structure conventions

### For React
react_project  
&emsp; |-- src  
&emsp;&emsp;&emsp;|-- components/  
&emsp;&emsp;&emsp;|-- pages/  
&emsp;&emsp;&emsp;|-- hooks/  
&emsp;&emsp;&emsp;|-- context/  
&emsp;&emsp;&emsp;|-- services/  
&emsp;&emsp;&emsp;|-- utils/  
&emsp;&emsp;&emsp;|-- assets/  
&emsp;&emsp;&emsp;|-- styles/   
&emsp;&emsp;&emsp;|-- App.jsx/  
&emsp;&emsp;&emsp;|-- main.jsx/  
&emsp; |-- .env  
&emsp; |-- .gitignore  
&emsp; |-- package.json  
&emsp; |-- README.md  


### For Node JS

backend  
&emsp; |-- src/  
&emsp;&emsp;&emsp;|-- controllers/  
&emsp;&emsp;&emsp;|-- models/  
&emsp;&emsp;&emsp;|-- routes/  
&emsp;&emsp;&emsp;|-- middleware/  
&emsp;&emsp;&emsp;|-- services/  
&emsp;&emsp;&emsp;|-- utils/  
&emsp;&emsp;&emsp;|-- config/  
&emsp;&emsp;&emsp;|-- app.js   
&emsp; |-- tests/  
&emsp;&emsp;&emsp;|-- unit/  
&emsp;&emsp;&emsp;|-- integration/  
&emsp; |-- .env  
&emsp; |-- .gitignore  
&emsp; |-- server.js

### Full stack project

myProject  
&emsp; |-- fronted/    
&emsp; |-- backed/   
&emsp; |-- shared/    
&emsp; |-- .gitignore  
&emsp; |-- server.js  

### Feature vs Type folder conventions

Feature : Folders were divided based on the features available in the project. Recommended for Large projects.

Type : Folders were divided based on the type of files and content type. Suitable for small projects.