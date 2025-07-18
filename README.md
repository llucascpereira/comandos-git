# Comandos Git

![Badge de Status](https://img.shields.io/badge/Status-Manutenção-yellow)

- Projeto dedicado para deixar registrado os comandos que eu mais utilizo no git, para caso eu esqueça algo, ter um local no qual consiga lembrar mais facilmente e deixe meu fluxo mais organizado.
- Poderia ir em qualquer lugar na internet para ver isso, mas prefiro criar meu fluxo.

## Fluxo para baixar o projeto do GitHub:
- <> Code -> copiar HTTP ou SSH
- Abrir Git Bash e escolher página onde os arquivos ficarão salvos.
- Digitar no Git Bash **git clone git@github.com:USER-NAME/REPOSITORY-NAME.git** para baixar os arquivos
- Digitar no Git Bash **git log** ou **git log --oneline** para visualizar o histórico de commits.

## Fluxo para editar os arquivos
- **git pull** para baixar o conteúdo de um repositório remoto e atualizar imediatamente o repositório local, para que o conteúdo de ambos seja o mesmo
- **git status** para exibir o estado atual do seu repositório Git, mostrando quais arquivos foram modificados, adicionados, excluídos ou ainda não estão sendo rastreados pelo Git.

## Fluxo para enviar para o GitHub
- **git add .** para adicionar todas as alterações feitas em arquivos e diretórios dentro do diretório atual (e seus subdiretórios) para a área de preparação (staging area) do Git, deixando-as prontas para serem incluídas no próximo commit.
- **git commit -m "Versão e Descrição do que foi feito"** para enviar as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva.
- **git push** ou **git push origin main** para enviar as alterações locais do seu repositório Git para um repositório remoto

## Observações
- git status e git log podem ser utilizados sempre que se acha necessário
- A sintaxe básica do Git é: programa | ação | destino (git | commit -m | "mensagem")
