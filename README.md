# Git e GitHub: controle e compartilhe seu código

### 02.  Iniciando os trabalhos

Nesta aula, aprendemos:

- Que um **commit** é a forma de salvar um estado ou versão do nosso código;

- Como adicionar arquivos para serem commitados com **git add**;

- Como commitar arquivos, utilizando o comando **git commit**;

- Como verificar o histórico de commits, através do **git log** e algumas de suas opções:

 - **git log --oneline**

 - **git log -p**

 - **git log --pretty="parametros de formatação"**

- Como fazer o Git não monitorar arquivos, através do **.gitignore**

- Que não devemos realizar **commit**, ou seja, salvar um estado, da nossa aplicação que não esteja funcionando.

### 04. Trabalhando em equipe

Nesta aula, aprendemos:

- Que uma branch (ou ramo) é uma linha de commits separada, e que pode ser utilizada para desenvolver funcionalidades independentes;

- Que com branches separados, podemos evitar que o código de uma funcionalidade interfira em outra;

- Como trazer o trabalho realizado em uma branch para outra branch, como por exemplo, o **master**, através do comando **git merge**;

- Que o **git merge** gera um novo commit, informando que houve uma mescla entre duas branches;

- Como trazer os commits de uma branch para outra, com o **git rebase**

- Que o **git rebase** não gera um commit de **merge**, simplificando o nosso log;

- Como os conflitos são apresentados pelo Git;

- Como resolver os conflitos e manter apenas as alterações desejadas com o Git.


### 05. Manipulando versões

Nesta aula, aprendemos:

- Que o Git pode nos ajudar a desfazer alterações que não vamos utilizar;

- Que, para desfazer uma alteração antes de adicioná-la para **commit** (com **git add**), podemos utilizar o comando **git checkout -- <arquivos>**;

- Que, para desfazer uma alteração após adicioná-la para **commit**, antes precisamos executar o **git reset HEAD <arquivos>** e depois podemos desfazê-las com **git checkout -- <arquivos>**;

- Que, para revertermos as alterações realizadas em um **commit**, o comando **git revert** pode ser a solução;

- Que o comando **git revert** gera um novo **commit** informando que alterações foram desfeitas;

- Que, para guardar um trabalho para retomá-lo posteriormente, podemos utilizar o **git stash**;

- Que, para visualizar quais alterações estão na stash, podemos utilizar o comando **git stash list**;

- Que, com o comando **git stash apply <numero>**, podemos aplicar uma alteração específica da **stash**;

- Que o comando **git stash drop <numero>** remove determinado item da **stash**;

- Que o comando **git stash pop** aplica e remove a última alteração que foi adicionada na **stash**;

- Que o **git checkout** serve para deixar a cópia do código da nossa aplicação no estado que desejarmos:
 
 - **git checkout <branch>** deixa o código no estado de uma branch com o nome **<branch>**;

 - **git checkout <hash>** deixa o código no estado do commit com o hash **<hash>**.