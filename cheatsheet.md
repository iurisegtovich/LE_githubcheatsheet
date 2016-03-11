git init

Initialized empty Git repository in /home/iurisegtovich/Desktop/pushme/.git/

git config --global user.name "iurisegtovich"
git config --global user.email iurisegtovich@gmail.com

git remote add origin https://github.com/iurisegtovich/repositorio

git pull origin master

Gerenciar merge

Desenvolver as atividades descritas nos issues

git add -A

git commit -m 'mensagem'

git push origin master

Username for 'https://github.com': iurisegtovich
Password for 'https://iurisegtovich@github.com': 




#utilidades
##1 configuração de user.name pós-commit
git commit -m 'mensagem'
git config --global user.name "iurisegtovich"
git config --global user.email iurisegtovich@gmail.com
git commit --amend --reset-author

##2mudar o repositorio remoto

git remote -v

origin	https://github.com/iurisegtovich/repositorio.git (fetch)
origin	https://github.com/iurisegtovich/repositorio.git (push)

git remote remove origin

git remote add origin https://github.com/iurisegtovich/outro_repositorio

git remote -v

origin	https://github.com/iurisegtovich/outro_repositorio.git (fetch)
origin	https://github.com/iurisegtovich/outro_repositorio.git (push)
