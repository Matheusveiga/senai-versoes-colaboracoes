principais comandos do git

git init // para criar um repositorio git na pasta selecionada

git config --global user.name "Usuario" // para definir seu nome de usuario no git

git config --global user.email "usuario@email.com" /// para definir seu email no git

git status // para ver as alteracoes no stagis

git add 'seus arquivos' // para confirmar as mudancas a serem selecionadas ao stagis

git log // para ver as alteracoes feitas no repositorio

git commit -m 'mensagem aqui' // para subir uma commit ao repositorio

git remote add origin 'seu repostorio online' // para conectar o repositorio online ao seu repositorio local

git remote -v // para visualizar o repositorio online

git push -u origin master // para autenticar o seu usuario github no git 

//esse eu aprendi sozinho

git push origin master // para subir suas commits ao repositorio online // 

// git push indica que estamos subindo uma commit para o remote, origin indica que estamos falando do nossos arquivos locais,
e o terceiro campo eh o local onde estamos subindo a commit, no caso master eh a trunk

git push origin tarefa/minha-primeira-branch // neste exemplo estamos subindo uma commit em uma branch nova que criei

git pull // para atualizar seus arquivos locais com os arquivos do repositorio online

git clone 'nome do repositorio' // para clonar o repositorio

<<<<<<< HEAD
git checkout -b 'nome da branch' // para criar uma branch no repositorio // o valor '-b' indica que estamos criando uma branch nova que nao existe ainda
=======
git checkout -b 'nome da branch' // para criar uma branch no repositorio // o valor '-b' indica que estamos criando uma branch nova que nao existe ainda


>>>>>>> tarefa/minha-primeira-branch

git checkout 'nome da branch' // se move entre as branchs 

git merge 'nome da branch 1' 'nome da branch 2' // une as branchs
