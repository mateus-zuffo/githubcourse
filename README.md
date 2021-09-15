# Description
This repository was made to practice how to use github, based on 2 courses:

  [Git e Github na Vida Real - Udemy](https://www.udemy.com/course/git-e-github-na-vida-real/)  
  [Git e Github: Controle e compartilhe seu código - Alura](https://cursos.alura.com.br/course/git-github-controle-de-versao)
  
# Notes

**Start Repository** 
- ```git init```

**Verify changes**
- ```git status```

**Add changes to be commited**
-	```git add arquivo```
  
-	```git add . ```
  
**Commit File**
- Use: ```git commit -m "MESSAGE"```
-	Revert commit: ```git revert HASH```

**Show Commit Log**
-	Regular Log:  ```git log```  
-	Compact Log:  ```git log --oneline```  
-	Detailed Log: ```git log -p```
- [Custom log](https://devhints.io/git-log)

**Branch:**
-	Create: ```git branch BranchName```
-	Delete: ```git branco -d BranchName```
-	Update delete: ```git push origin --delete BranchName```
-	Use: ```git checkout BranchName```
-	Use old branch: ```git checkout HASH```

.gitignore : Add file name, folders or path to ignore files

**Stash**
- ```git stash```
- ```git stash apply NUMBER```
- Use: ```git stash```
-	List stash: ```git stash list```
- Last stash: ```git stash pop```
- Drop stash after use: ```git stash drop NUMBER```
