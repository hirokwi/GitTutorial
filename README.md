Resumo dos comandos e explicações do tutorial Git.

## Inicialização do repositório
- `git init` → Inicializa um repositório Git local.  
  Cria a pasta `.git` onde ficam os dados do repositório.

## Adicionar arquivos
- `git add <arquivo>` → Adiciona um arquivo específico à área de staging.  
- `git add .` → Adiciona todos os arquivos modificados à área de staging. -> para checar a área de staging, o comando: `git status`

## Commit (salvar alterações)
- `git commit -m "mensagem"` → Cria um commit com a mensagem informada.

## Branches
- `git branch -M main` → Renomeia a branch principal para `main`.  
- `git checkout -b <nome-branch>` → Cria e já muda para a nova branch.  
- `git checkout <nome-branch>` → Muda para uma branch existente.

## Merge (juntar alterações)
- `git merge <nome-branch>` → Junta as alterações da branch informada na branch atual.

## Repositório remoto
- `git remote add origin <link>` → Conecta o repositório local ao remoto.  
- `git push -u origin main` → Envia a branch principal para o remoto (primeiro push).  
- `git push origin <branch>` → Envia uma branch específica para o remoto.

## Atualizar repositório local
- `git pull` → Puxa as alterações do repositório remoto para a máquina local.

## Clonar repositório
- `git clone <link>` → Clona um repositório remoto para a máquina local.

## Trabalhando com GitHub
- **Fork** → Cria uma cópia de um repositório de outra conta para a sua.  
- **Pull Request** → Solicitação para enviar suas alterações para o repositório original.
