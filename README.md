
* * * * * * Pincipais comandos iniciais do git * * * * * *


git init: inicializar o projeto no diretório
git add <arquivo> : adiciona o arquivo na staging
git add .: adiciona todos os arquivos que foram alterados na staging
git add *.txt: adiciona todos os arquivos com a extensão desejada (nesse exemplo, todos os arquivos .txt)
git commit -m “<descrição>”
git commit -a -m “<descrição>”: o -a dispensa a etapa de git add

———— AULA 03 ——————————————————————————————————————————————————————————————————————————
git diff: mostra as alterações feitas. Em verde as alterações que foram adicionadas ao arquivo
git diff --staged: saber as alterações que estão na staged área 
git log: mostra um log(informações) de todos os commits feitos no projeto
git log -p: mostra o diff de cada um dos commits
git log -p -1.: traz 1 commit no log. Pode ser qualquer número
gitk: interface do git para analisar os logs

————— AULA 04 ———————————————————————————————————————————————————————————————————————————————————
git log --pretty=oneline: exibe todos os commits com seu log e mensagem em uma única linha
git commit --amend -m “<texto aqui (edicao)>”: edita o último commit que foi feito - caso tenha esquecido de alterar algo e não quer fazer um outro commit.
git reset HEAD <arquivo> ou git restore --staged <arquivo>: remove um arquivo da staged 
git checkout -- <arquivo>:  desfaz todas as alterações feitas no arquivo desde o último commit
git rm <arquivo>: remover os arquivos que foram excluídos no projeto  

———— AULA 05 ———————————————————————————————————————————————————————————————————————————————————————
TAG: etiqueta, um ponto de atalho para trocar o status do sistema!!
git tag -a <nome_da_tag> -m “<mensagem>”: cria uma tag. A tag sempre é criada no seu commit atual, onde se está trabalhando no momento!
git tag: listar as tags
git show <nome_da_tag>: exibe mais detalhes sobre a tag
git checkout <nome_da_tag>: volta os arquivos para o momento em que a tag foi criada
git tag -d <nome_da_tag>: excluir uma tag
——————————————
BRANCH: é uma ramificação, um outro espaço para trabalhar
git branch <nome_da_banch>: criar uma nova branch
git checkout <nome_branch>: ir para a branch que deseja
git checkout -b <nome_branch>: cria e seleciona a branch
FAZER MERGE: trazer as alterações de outra branch para a master. Você precisa já estar na master!
git merge <nome_da_banch_para_trazer_as_modificações> : trazer as modificações de uma branch para a master
git branch -d <nome_branch>: apagar uma branch
git branch: listar todas as branch 

———— AULA 07 ————————————————————————————————————————————————————————————————————————————————————
git clone <arquivo/link>: clona todos os dados/arquivos de um repositório 
Dar um PUSH: mandar os arquivos da sua máquina(local) para o servidor
git remote: mostra o nome do servidor remoto
git push <servidor> <branch> (EX.: git push origin master): envia os arquivos que estão na branch master para o servidor Origin. 
git pull <servidor> <branch>: traz as atualizações do servidor para a branch em que está trabalhando

——— AULA 08 ———————————————————————————————————————————————————————————————————————————
FORK : clonar o repositório que vc quer colaborar para dentro da sua conta do gitHub
PULL REQUEST: enviar as alterações para o autor do repositório/projeto



