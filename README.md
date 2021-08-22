>### Selecione o idioma | Select the language:

>[<img width="30" height="30" src="https://images.emojiterra.com/twitter/512px/1f1e7-1f1f7.png"></img>](#português)  [<img width="30" height="30" src="https://images.emojiterra.com/twitter/512px/1f1fa-1f1f8.png"></img>](#inglês) 

<img width="700" height="400" src="https://media0.giphy.com/media/cFkiFMDg3iFoI/giphy.gif"></img>


<a name="português"></a>
## 💻 Sobre o Projeto

Esse projeto tem como objetivo ensinar os **comandos principais** para serem executados na linha de comando, para que você possa começar utilizar o Git em seus projetos já criados, e subir seus repositórios para algum servidor. Como também clonar projetos para mexer localmente.

Nos exemplos abaixo estarei utilizando o GitHub para subir o projeto e irei abordar dois caminhos, então clique no que mais se adequa ao que você precisa:

- [Clonar um repositório do GitHub](#clonar)
- [Subir um projeto local para o GitHub](#subir)

</br>

## 🛠 Tecnologias

- **[Git](https://git-scm.com/)**
- **[GitHub](https://github.com/)**

</br>

## 📀 Instalação

Após fazer a instalação do Git em seu pc, rode os comandos abaixo em seu terminal para configurar as informações principais:

```sh
git config --global user.name "Seu Nome Aqui"

git config --global user.email seuemail@exemplo.br
```

</br>


## <img width="25" height="25" align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Git_icon.svg/1024px-Git_icon.svg.png"></img> Principais Comandos Git 
</br>
<a name="clonar"></a>
Para clonar um repo do GitHub para o seu computador, execute o comando abaixo alterando a URL pelo que você copiou:

```sh
git clone https://github.com/nathwagana/git-commands.git
```
Para visualizar o próximo passo que é commitar o seu projeto e subir as alterações, clique [aqui](#aqui).

</br>
</br>
<a name="subir"></a>
Para adicionar o Git ao seu projeto, na linha de comando digite:

```sh
git init
```
</br>
O próximo passo é criar sua repo no servidor remoto escolhido.
Para vincular sua repo remota ao seu projeto local, use o comando abaixo, colocando como último parâmetro a web URL que você copiou:

```sh
git remote add origin https://github.com/nathwagana/git-commands.git
```
</br>
Será necessário fazer a criação de uma branch onde serão realizados os commits, utilizando o comando abaixo:

```sh
git branch -M main
```
<a name="aqui"></a>
</br>
Para adicionar os arquivos novos/modificados no pacote para serem commitados (escolher uma das opções de acordo com a necessidade): 

```javascript
git add . //Add todos os arquivos

git add nomeDoArquivo.txt //Add apenas o arquivo citado

git add -A //Add todos os arquivos que não estavam trackeados anteriormente
```
</br>
Comando para realizar o commit:

```sh
git commit -m "descrição das alterações/inclusões realizadas"
```
</br>
Comando para subir os commits para o repo remoto, alterando o último parâmetro para o nome da branch para a qual você deseja enviar:

```sh
git push origin main
```
</br>
Para verificar as branches que existem (o * indica em qual você está):

```sh
git branch
```
</br>
Para criar uma nova branch local:

```sh
git branch nome-da-branch-aqui
```
</br>
Para subir uma branch local para o remoto:

```sh
git push origin nome-da-branch-que-quer-subir-aqui
```
</br>
Para trocar a branch onde está trabalhando:

```sh
git checkout nome-da-branch-para-qual-quero-ir-aqui
```
</br>
É possível também verificar o que foi modificado em um (ou mais) arquivo antes do commit (escolha uma das opções de acordo com a necessidade):

```javascript
git diff //Mostra a diferença em todos os arquivos modificados

git diff --name-only //Mostra somente o nome dos arquivos modificados

git diff nome-arquivo-aqui //Mostra a diferença somente no arquivo especificado
```
</br>
Para ver detalhes sobre o repo remoto:

```sh
git remote -v
```
</br>
Comando para verificar se teve algum commit que não foi sincronizado:

```sh
git status
```
</br>
Para sincronizar o seu projeto local com as alterações realizadas por outros devs no repo remoto:

```sh
git pull origin nome-da-branch-para-onde-quero-puxar-alterações
```
</br>
Para fazer o merge entre branches. Esse comando deverá ser executado na branch para onde você deseja trazer as informações:

```sh
git merge nome-da-branch-que-quero-puxar-para-fazer-merge-com-atual
```
</br>
Para remover uma branch do repo remoto:

```sh
git push origin :nome-da-branch-para-remover
```
</br>
Para remover uma branch local:

```sh
git branch -D nome-da-branch-para-remover
```
</br>
Para visualizar os detalhes de todos os commits que já foram feitos na branch selecionada:

```javascript
git log
```

</br>

## 🦸 Autor

Projeto desenvolvido por Nath Wagana. Se quiser saber mais sobre mim ou entrar em contato, acesse meu LinkedIn clicando abaixo.

<a href="https://github.com/nathwagana">
<a href="https://www.linkedin.com/in/nathaliarioswagana/" target="_blank"><img height="30" width="30" src="https://im6.ezgif.com/tmp/ezgif-6-7dda21616c22.gif" target="_blank"></a>

</br>
</br>
</br>
</br>

#

</br>
</br>


<a name="inglês"></a>
## 💻 About the Project

This project aims to teach the **main commands** to be used on the command line, so you can start to use Git in your already created projects and upload your repositories to any server. As also clone projects to move locally.

In the examples bellow I'll be using GitHub to upload the project and approach two ways, so click on the one that best suits your needs.

- [Clone a GitHub repository](#clone)
- [Upload a local project to GitHub](#upload)

</br>

## 🛠 Tecnologies

- **[Git](https://git-scm.com/)**
- **[GitHub](https://github.com/)**

</br>

## 📀 Instalation

After Git installing in your computer, run the commands bellow in your command line to set up the main information:

```sh
git config --global user.name "Your Name Here"

git config --global user.email youremail@exemplo.com
```

</br>


## <img width="25" height="25" align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Git_icon.svg/1024px-Git_icon.svg.png"></img> Main Git Commands 
</br>
<a name="clone"></a>
To clone a GitHub repo to your computer, run the command bellow changing the URL for what you copied:

```sh
git clone https://github.com/nathwagana/git-commands.git
```
To view the next step that is commit your project and upload the changes, click [here](#here).

</br>
</br>
<a name="upload"></a>
To add Git to your project, in the command line type it:

```sh
git init
```
</br>
The next step is create your repo in the chosen remote server.
To bind your remote repo to your local project, use the command bellow, putting as last parameter the URL web that you copied.

```sh
git remote add origin https://github.com/nathwagana/git-commands.git
```
</br>
It'll be necessary to create a branch where commits will be performed, using the command bellow:

```sh
git branch -M main
```
<a name="aqui"></a>
</br>
To add the new/modified archives in the package to be commit (choose one of the options according to the necessity):

```javascript
git add . //Add all files

git add archiveName.txt //Add just the quoted file

git add -A //Add all files that wasn't tracked previously
```
</br>
Command to commit:

```sh
git commit -m "description of changes/additions made"
```
</br>
Command to upload the commits for the remote repo, changing the last parameter to the name of the branch you want to send to:

```sh
git push origin main
```
</br>
To verify the existing branches (the * indicates which one you are):

```sh
git branch
```
</br>
To create a new local branch:

```sh
git branch branch-name-here
```
</br>
To upload a local branch to remote:

```sh
git push origin branch-name-want-upload-here
```
</br>
To change the branch when you're working:

```sh
git checkout branch-name-want-to-go-here
```
</br>
It's also possible to check what has been modified in one (or more) files before committing (choose one of the options as needed):

```javascript
git diff //Show the difference in all modified files

git diff --name-only //Show only modified file names

git diff archive-name-here //Show the difference just in the specified file
```
</br>
To see details about remote repo:

```sh
git remote -v
```
</br>
Command to check if there were any commits that were not synchronized:

```sh
git status
```
</br>
To synchronize your local project with changes made by other devs in remote repo:

```sh
git pull origin branch-name-where-want-pull-changes
```
</br>
To merge between branches. This command should be run on the branch you want to bring the information to:

```sh
git merge branch-name-pull-to-merge-with-current
```
</br>
To remove a remote repo branch:

```sh
git push origin :branch-name-to-delete
```
</br>
To remove a local branch:

```sh
git branch -D branch-name-to-delete
```
</br>
To view details of all commits that have already been made on the selected branch:

```javascript
git log
```

</br>

## 🦸 Author

Project developed by Nath Wagana. If you want know more about me or get in touch, access my LinkedIn by clicking in the .gif bellow.

<a href="https://github.com/nathwagana">
<a href="https://www.linkedin.com/in/nathaliarioswagana/" target="_blank"><img height="30" width="30" src="https://im6.ezgif.com/tmp/ezgif-6-7dda21616c22.gif" target="_blank"></a>