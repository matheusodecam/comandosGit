
# Comandos GIT

Este repositório eu uso para anotar alguns dos principais comando GIT que uso diariamente


## 

| Comando   | Descrição                           |
| :---------- | :---------------------------------- |
| `git remote add origin` *link-repositorio-remoto* | Adiciona o repositório *remoto* ao repositório *local* |
|`git remote -v`| Mostra qual repositorio *remoto* está conectado|
|`git init`| Inicializa o repositório *local* |
|`git branch -m master main`| Muda da branch *master* para a branch *main*|
|`git push -u origin main`| Envia os commits para o repositório *remoto*. Cria a main se necessário |
|||
|||
|`git status`| Mostra a lista dos arquivos que devem ser adicionados para o commit, e também os que já foram adicionados|
|`git clone` *repositório-remoto*| Copia todo o repositório *remoto* dentro do repositório local|
|||
|||
|`git add` *nome do arquivo*| Adiciona o arquivo ao repositório *local*|
|`git add -A`| Adiciona todos os arquivos ao repositorio *local*|
|`git commit -m` *mensagem do commit*| Os arquivos são enviados da *area de preparação* para o repositório *local*|
|`git push --set-upstream` *repositório-remoto* *nome-da-branch*| Usado para enviar a branch *local* para a branch *remota* pela primeira vez|
|`git push -u origin` *nome-da-branch*| Versão abreviada do comando anterior, porém o nome da branch *local* precisa ser o mesmo da branch *remota*|
|`git push` *repositório-remoto* *nome-da-branch*| Envia os dados para o repositório *remoto* especifico|
|`git pull` *repositório-remoto*| Atualiza o repositório *local* com as últimas alterações do repositório *remoto*|
|`git pull origin`| O Git irá buscar as alterações do repositório *remoto* especificado e, tentará mesclá-las automaticamente com a sua branch *local* atual|
|||
|||
|`git revert HEAD`| Usado para desfazer o último commit|
|`git commit --amend`| Renomeia a tag do último commit|
|`git log`| Usado para visualizar o histórico dos commits|
|||
|||
|`git branch` *nome-da-branch*| Cria uma branch *local*|
|`git branch`| Mostra todas as branchs do repositório *local*|
|`git branch -d`| Exclui uma branch|
|`git branch -a`| Mostra todas as branchs do repositório *remoto*|

