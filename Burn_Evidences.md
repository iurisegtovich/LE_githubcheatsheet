Consertar erros gramaticais ortografico no commit

$	git commit --amend -m "essa msg sobrescreve a mensagem do ÚLTIMO commit feito"

Pegar ID de commits antigos

$	git log

olhar arquivos antigos

$	git checkout IDantiga

Abandonar desenvolvimento atual e ficar com arquivos antigos

$	git reset IDantiga

?acho q o comando a seguir é importante para complementar esse passo
REF: https://www.atlassian.com/git/tutorials/undoing-changes/git-clean

$	git clean -df

Se trabalhar mais encima do reset:

$	git add-A
$	git commit -m "mensagem aí"

para enviar para o hub, usar comando -f caso queira forçar apagar histórico no site

$	git push origin master -f

