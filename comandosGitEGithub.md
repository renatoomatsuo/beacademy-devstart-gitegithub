# Comandos vistos nas aulas de Git e Github e também na live com o professor Régis

#Comandos

# trazer ajuda diretamente no terminal.
git help

# configurar nome do usuário.
git config --global user.name <nome>

# configurar e-mail do usuário.
git config --global user.email <e-mail>

#criar um novo repositório.
git init 

# verificar estado dos arquivos/diretórios.
git status
  
# cria uma cópia exata de um repositório já existente.
git clone <URL do projeto>
  
# adicionar arquivo em específio.  
git add <arquivo>
  
# adicionar diretório em específico.  
git add <diretório>
  
# adicionar todos os arquivos e diretórios.
git add .

# comitar um arquivo.
git commit <arquivo>

# comitar vários arquivos.
git commit <arquivo1> <arquivo2>

# comitar informando uma mensagem.
git commit <arquivo> -m "mensagem"
  
# remover arquivo.
git rm <arquivo>
  
# remover diretório.
git rm -r <diretorio>
  
# exibir histórico.  
git log
  
# exibir resumo do histórico.
git log --stat
  
# criar um stash.
git stash
  
# listar stashes.
git stash list

# voltar para o último stash.
git stash apply

# criar um branch a partir de um stash.
git stash branch <branch>

# lista todas as ramificações.
git branch

# cria um branch com o nome especificado.
git branch <nome_do_branch>

#deleta o branch com o nome especificado.
git branch -d <nome_do_branch>
  
# trocar de uma ramificação para outra.
git checkout

# estabelecer uma conexão entre seu repositório local e um repositório remoto.
git remote add <nomecurto> <url>
  
# subir suas modificações para um repositório remoto conectado anteriormente com git remote.
git push -u <nome_curto> <nome_do_branch>
  
# baixar o conteúdo do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu conteúdo para a última versão.
$ git pull <URL>
  
# armazenar temporariamente seus arquivos modificados em uma área chamada "stash", sem interagir com os outros arquivos até ser necessário.
git stash

# listar todos os "strashs".
git stash list
  
# integrar as mudanças de dois branches diferentes em um único branch. Ele precisa ser iniciado a partir de um branch já selecionado.
git merge <nome_do_branch>
