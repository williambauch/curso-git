# curso-git


#------------ DOS ------------ 
cd [nome da pasta]
ls (lista as pastas)
~$ mkdir name_project
~$ cd name_project

#------------ GIT ------------ 
$ git init 
$ git config --global user.name xxxxxxxx
$ git config --global user.email xxxxx@xxxxxx.com

para ver o status dos arquivos use
$ git status

Adicionar arquivo no Staged
$ git add arquivo.txt (usado para um arquivo)
$ git add . (usado para todos os arquivos)

$ git commit -m 'adição do arquivo txt'
$ git commit -am 'Segundo Commit'


$ git log
use "Q" para sair do log


$ git checkout c534e370624f843c8a2d8ad2de7f8e1e355103f8
$ git checkout master

$ git branch "nome da nova branch"

$ git branch (lista todas as branchs)

#------------ GITHUB ------------ 
$ git clone [link do repositório]

$ git push (sobe os arquivos para o Github)(ajustar as configuração com $ git 

config)

$ git pull (traz todos os arquivos do Github


git push -u origin master
git remote add origin https://github.com/williambauch/curso-git.git

git submodule add https://github.com/williambauch/curso-git.git curso-git
