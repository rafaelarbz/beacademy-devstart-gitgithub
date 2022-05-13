## Git e GitHub
Este repositório tem o propósito de armazenar comandos úteis do Git e GitHub.

## Autor
👻 [Rafaela Rabelo](https://linkedin.com/in/rafaelarsouza)

## Comandos
- git config : Permite atribuir configurações ao Git;
- git status : Verifica as condições do diretório/versionamento;
- git init : Inicializa o repositório;
- git add : Adiciona alteração ao repositório;
  - git *add  .*  : Adiciona **todas** as alterações ao repositório;
- git rm : O arquivo será adicionado à  *staging area*  com o status  *deleted*  e também será removido do diretório;
  - git rm  *--cached* : Leva até a  *staging area*  a informação de que o arquivo deve ser deletado, mas o arquivo físico continua no diretório;
- git commit  *-m* : Possibilita adicionar mensagem ao  *commit*  a respeito das alterações realizadas;
- git log : Exibe o histórico de  *commits*;
- git branch : Lista a ramificação disponível;
  - git branch  *nome_da_branch* : Cria ramificação;
  - git branch  *-d* : Remove ramificação;
- git checkout : Permite alternar entre ramificações;
  - git checkout  *-b* : Cria e acessa nova ramificação;
- git merge : Permite integrar/mesclar ramificações;
