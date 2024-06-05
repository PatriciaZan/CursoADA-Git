# Resumo comandos GIT


- USER AND EMAIL
`git config --global user.name "user name"`
`git config --global user.email 'user email'`

- VERSIONAMENTO
#Clonar repositório
GitHub -> Code -> HTTPS -> copy link

PromptComando
cd CTR+V(pasta destino) 
git clone (link copiado)

#pelo VSCODE
Adiciona .git e inicializa
`git init` 

- ESTADOS DO GIT
- GRAVANDO MUDANÇAS DO REPOSITÓRIO
Untracked -
Unmodified - Já mapeado, salvo no estado que está (comitados).
Modified (M)- modificados, mudanças que podem ser passados para proximo comit.
Stage - Preparatório para comit.

`git status`  -> checa o Status
`get add .\`'nome do arquivo' -> adicionar modificações para o Stage

- GIT DIFF E COMMIT
`git diff` -> mostra as linhas modificadas -#vermelho | +#verde
`git diff --stage` -> quando em Stage
`git commit -m` "mensagem"

- GIT LOG E RESTORE
`git log` -> mostra histórico de commits Q
`git restore .\`'nome do arquivo' -> restaura anterior
`get restore --stage .\`'nome do arquivo' -> retira da area de Stage

- REPOSITÓRIOS REMOTOS
`git remote`

`git push origin master`

`git pull` -> adiciona novos do repositório

`git fetch` -> verifica oque está para vir de novo/diferente

- GIT BRANCH
`git branch` 'nome da nova branch ex.testing' -> cria nova branch
`git log --oneline -decorate` -> indica onde HEAD está
`git checkout` 'testing' -> HEAD aponta para testing

- MERGING BRANCHES
`git merge` 'testing' -> irá unir as branchs

`git rm` 'nome do arquivo' -> remove arquivo




