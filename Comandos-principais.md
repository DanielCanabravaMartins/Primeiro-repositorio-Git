# Comandos principais

## Ajuda

#### Geral 	

git help

#### Específico

git help add

git help commit

git help <comando git>

## Configuração

### Geral

git config

### Usuário

git config --global user.name "Nome"

### Email

git config --global user.email "Email"

### Listar configurações

git config --list

## Repositório

### Criar repositório

git init

### Verificar estado

git status

### Adicionar arquivo/diretório (staged area)

##### Adicionar um arquivo em específico

​		git add meu_arquivo.txt

##### Adicionar um diretório em específico

​		git add meu_diretorio

##### Adicionar todos os arquivos/diretórios

​		git add .

### Comitar arquivo/diretório

##### Comitar um arquivo

​		git commit meu_arquivo.txt

##### Comitar vários arquivos

​		git commit meu_arquivo.txt meu_outro_arquivo.txt

### Remover arquivo/diretório

##### Remover arquivo

​		git rm meu_arquivo.txt

##### Remover diretório

​		git rm -r diretorio

