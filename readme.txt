****cosas de github ****
añadir colaborador : patchwork-->settings-->colaborators-->*name
folk button
pull request
**********************************


****general comands ***********

git status <--- ver el estado del repositorio
git add <file>  <--- añadir al seguimiento
git commit -m "blahblah"   <--- dar seguimiento
git diff  <--- vizualisar las diferencias a los cambios

*********************************

****push and pull commands *******

git remote add origin <url>  <--- añade al servidor tu proyecto local
git push origin master <--- sube los cambios al servidor de tu proyecto local
git clone <url fork> <--- pasa como proyecto local un fork del servidor
git remote add upstream <url> crea un pull de cambios en el proyecto orginal del cual se hace el fork
***************************************

****branch**************
git branch <branchname>  <---- crea un nuevo branch
git checkout <branchname>  <------ te permite moverte entre branches

****check in process (own server forked) **********

git status
git add <filename>
git commit -m "<commit message"
git push origin <branchname>

*************************

****pull process*****
git pull <remotename> <branchname> *remotename = url del fork 
git fetch --dry-run

************************************


*****merge***********
git checkout <principalbranch>
git merge <branchenamethatwannamerge>
git branch -d <branchname>  <---- deleting branch * no necesary

****************************************

*****pullfromupstream******
git pull upstream gh-pages
***********************************


******set user *******
git config --global user.username/name/email <""> 
**************************



