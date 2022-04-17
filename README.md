# Projeto Git e GitHub

## Criando meu primeiro projeto de anotações de Git e GitHub.

### Sites úteis:

- [ Markdown ] <https://www.markdownguide.org/basic-syntax/>
- [ GitHub ] <https://www.github.com>

## Comandos do Git 

- Ajuda
  - git help -> comando geral
  
- Comando específico
  - git help add 
  - git help commit
  - git help <qualquer_comando_git> 
  
- Setar usuário e email 
  - git config --global user.name "nome do usuário"
  - git config --global user.email email@email.com
  
- Remover todas as linhas que referenciam o usuário e email 
  - git config --global --unset user.name "nome do usuário"
  - git config --global --unset user.email email@email.com
  
- Lista configurações
  - git config --list
  
- Criando novo repositório 
  - git init
  
- Verificar o estado dos arquivos/diretórios
  - git status (mostra qual a situação do arquivos no seu repositório) 
  
- Adicionando arquivo 
  - git add meu_diretorio (arquivo específico)
  - git add . / git add --all (todos os arquivos)
  
- Comitar arquivo/diretório
  - git commit arquivo -m "mensagem de commit"
  
- Remover arquivo/diretório
  - git rm arquivo (remove arquivo)
  - git rm -r diretório (remove diretório/pasta)
  
- Visualizar histórico
  - git log (exibir histórico)
  - git log -- <caminho_do_arquivo> (exibir histórico de um arquivo específico)
  - git log --author=usuário (exibir histórico de um determinado)


