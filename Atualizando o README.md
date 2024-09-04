# curso-frontend

### EBAC

# GIT 
## Versionamento 
    - Histórico 
    - Controle de versão 
    - Quem alterou
    - O que alterou
    - Quando alterou
    - Todos os arquivos 
    - Evolução contínua 


Arquivo A   / Versão 1 / Versão 2
Arquivo B   / Versão 1 / Versão 2

## Instalação do GIT

## Criar conta no GIT

## Clonar o projeto 
Informação de alteração
- Após testado todo o seu código 
- Git add *
- git commit -m "mensagem"
- git push (para enviar alterações para o repositorio)
- git pull (puxar dados do repositorio)

## Comits
Informação de alteração
- Após testado todo o seu código 

## GitFlow
Fluxo no Git

### Branchs
são ramificações do codigo que podem correr paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop (teste)

- versionamento 0.1.10 

### Criar uma branch 
git checkout -b nome da branch

gti checkout nome da branch (muda de branch)

### Merge
Mescla de branchs 
git merge main

### Pull Requests
Mescla de branchs no repositorio
permite o code review
O repositório resilbe os conflitos automaticamente

### Configurar o git flow 
git flow init 

para iniciar uma feature 
git flow feature start nome-da-feature
git flow feature finish melhoria-html (para finalizar a feature)

### Criar a gitignore
touch .gitignore
