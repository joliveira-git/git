# Principais Comandos Git
$ sudo apt-get install git

# inicialize o git:
$ git init

# Adiciona todas as modificações feitas
$ git add -A or git add .

# Realizar o commit
$ git commit -m "First commit"

# Visualizar se todos os arquivos foram commitados
$ git status

$ git remote add origin your_link

$ git remote -v
# Isso vai listar o link dos seus repositórios remotos

$ git push -u origin <branch>.
# Nesse caso como é nossa estrutura inicial vamos enviar para o master.
Colocando o -u junto com o push ele faz o set-upstream que seria fazer a referência do repositório remoto com a devida branch.
