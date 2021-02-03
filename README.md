# Git Commands
List of git commands.


Repo

- clonar repo - git clone “https da repo”

- stage dos arquivos para commit - git add . OU git add <nome do arquivo>

- commita - git commit -m "nome do commit"

- adiciona a origem do remote - git remote add origin remote repository URL

- faz o push no main - git push origin main


Branch

- cria branch chamado "funcionalidade_x" e seleciona-o - git checkout -b funcionalidade_x

- retorna para o master - git checkout master

- faz o push do branch - git push origin <funcionalidade_x>

- deleta o branch - git branch --delete <funcionalidade_x>


Atualizar & Mesclar

- atualizar repositório local com versão recente - git pull

- na sua pasta de trabalho para obter e fazer merge (mesclar) alterações remotas. para fazer merge de um outro branch ao seu branch ativo (ex. master), use - git merge <branch>

- em ambos os casos o git tenta fazer o merge das alterações automaticamente. Infelizmente, isto nem sempre é possível e resulta em conflitos. Você é responsável por fazer o merge estes conflitos manualmente editando os arquivos exibidos pelo git. Depois de alterar, você precisa marcá-los como merged com - git add <arquivo>

- antes de fazer o merge das alterações, você pode também pré-visualizá-as usando - git diff <branch origem> <branch destino>
