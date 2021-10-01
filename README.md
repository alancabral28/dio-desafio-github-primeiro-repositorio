# Repositório do Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto

### Principais Comandos Aprendidos no Curso


#### Configurar Usuário
 git congig --global user.name "Alan Sant Ana Cabral"
 
#### Configurar e-mail
  git config --global user.email "alanfab28@gmail.com"
  
#### Criar novo repositório
  git init
  
#### Verificar estado dos arquivos/diretórios
  git status
  
Adicionar arquivo/diretório (staged area)
Adicionar um arquivo em específico
git add meu_arquivo.txt
Adicionar um diretório em específico
git add meu_diretorio
Adicionar todos os arquivos/diretórios
git add .	
Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)
git add -f arquivo_no_gitignore.txt
Comitar arquivo/diretório
Comitar um arquivo
git commit meu_arquivo.txt
Comitar vários arquivos
git commit meu_arquivo.txt meu_outro_arquivo.txt
Comitar informando mensagem
git commit meuarquivo.txt -m "minha mensagem de commit"
