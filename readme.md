### comando para iniciar um repositorio ###
git init

### comando para ver o status de um repositório ###
git status

### comando para ver adicionar as alterações do arquivo na staging antes do commit ###
### para adicionar todos os arvuivos da pasta ###
git add .

### comando para adicionar arquivos especificos ###
git add "nome arquivos"

### comando para configurar o usuário que está responsável por este repositório ###
git config --local user.name "Nome pessoa"

### comando para configurar o e-mail do usuário que está responsável por este repositório ###
git config --local user.email "email@seila.com"

### comando para comitar alterações realizadas ###
git commit -m "mensagem descritiva do commit"

### comando para visualizar as alterações ###
git log ou git log --oneline ou git log -p

### criamos o arquivo .gitignore para ignorar tudo o que não quisermos que o git visualize, podemos botar um nome de um arquivo, ou então o nome da pasta/###
.gitignore

### comando para listarmos repositorios remotos ###
git remote

### comando para listar os caminhos ###
git remote -v

### comando para clonar um repositorio remoto ###
### podemos mudar o nome da pasta no ultimo parametro ###
git clone /c/Users/abdon/Documents/git-e-github/servidor/ projeto 

### comando para renomear o repositorio remoto ###
git remote rename origin local

### comando para criar o repositorio remoto ###
git remote add local /c/Users/abdon/Documents/git-e-github/servidor

### comando para puxar dados de um repositório remoto ###
git pull "nome repo" "branch"