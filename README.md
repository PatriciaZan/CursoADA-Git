#Configurações do git

---USER AND EMAIL---
git config --global user.name " "
git config --global user.email ''

---VERSIONAMENTO---
#Clonar repositório
GitHub -> Code -> HTTPS -> copy link

PromptComando
cd CTR+V(pasta destino) 
git clone (link copiado)

#pelo VSCODE
git init

---ESTADOS DO GIT---
---GRAVANDO MUDANÇAS DO REPOSITÓRIO---
Untracked -
Unmodified - Já mapeado, salvo no estado que está (comitados).
Modified (M)- modificados, mudanças que podem ser passados para proximo comit.
Stage - Preparatório para comit.

git status   -> checa o Status
get add .\'' -> adicionar modificações para o Stage

---GIT DIFF E COMMIT---
git diff -> mostra as linhas modificadas -#vermelho | +#verde
git diff --stage -> quando em Stage
git commit -m "mensagem"

---GIT LOG E RESTORE---
git log -> mostra histórico de commits Q
git restore .\'' -> restaura anterior
get restore --stage .\'' -> retira da area de Stage

---REPOSITÓRIOS REMOTOS---
GIT PUSH






