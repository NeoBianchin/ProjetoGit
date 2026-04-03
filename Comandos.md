Alguns comandos: git --version "Para verificar a versão instalada"

git init: "Para iniciar o git"

git add: (arquivo) "manda os arquivos para a area de staging A área de staging (ou

staging area) no Git é uma zona intermediária que prepara modificações de arquivos para o próximo commit."

git status: "O git status serve para exibir o estado atual do repositório, mostrando quais arquivos foram modificados, excluídos ou criados, e se estão na área de staging (preparados para commit) ou não. Ele é essencial para monitorar o projeto, identificar arquivos untracked (não rastreados) e verificar se o diretório de trabalho está alinhado com o commit anterior"

git config --global user.email "you@example.com": "O comando git config --global user.email "seu_email@exemplo.com" configura o e-mail associado a todos os seus commits no computador. Ele identifica o autor das contribuições em plataformas como GitHub, GitLab ou Bitbucket, permitindo que o histórico de alterações seja atribuído corretamente à sua conta."

git config --global user.name: "O comando git config --global user.name "Seu Nome" é utilizado para definir o nome de usuário que será associado às suas atividades e commits no Git em todos os repositórios da sua máquina."

git branch -M: "Este comando é muito utilizado no início de projetos para renomear o branch padrão local (que às vezes é criado como master) para main (ex: git branch -M main), seguindo as convenções modernas de nomenclatura."

git remote add origin: "O comando
git remote add origin <url> serve para vincular seu repositório Git local a um servidor remoto. Ele cria um "apelido" chamado origin para a URL do repositório, facilitando o envio (push) e a recepção (pull) de código. 