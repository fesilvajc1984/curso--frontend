# Git

## Conceitos de versionamento
- Histórico
- Controle de versão
- Quem alterou
- O quê alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git

## Criar a conta no GitHub

## Clonar o projeto
- git clone https://github.com/fesilvajc1984/curso--frontend.git

## Commits
Informação de alteração
- após ter testado seu código
- git add *
- git commit -m "mensagem".
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

### Branches
- são ramificações / versões paralelas

- main / master (depois que as mudanças foram efetuadas no versionamento, ele recebe um novo numero que agora seria 1.0.0 que agora essas mudanças serão aplicadas no master que vai para produção, ou seja, ele será publicado)

- develop (geralmente os programadores desenvolvem o conteudo do site ou software nessa      ramificaçao, e somente depois de tudo estar pronto nesse dia de trabalho, dai sim ele vai fazer o commit para o master.)

- DOD -> Definition of Done (critérios de aceite)

- versionamento 0.1.10 (o primeiro digito da esquerda, significa a versao inicial ou Beta. O digito do meio, significa alterações no código e por fim o ultimo digito significa correções de bugs no sistema.)