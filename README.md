# Agencia

## Criar um projeto no Maven
mvn archetype:generate -DgroupId=br.com.senai -DartifactId=agencia -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

## Acessar o projeto
    cd nome_do_projeto

## Inicializando o versionamento
    git.init - Somente no inicio do projeto

## Adicionar os arquivos do projeto
    git add . (o ponto informa que irá adicionar tudo)
## Colocar um comentário no versionamento
    git commit -m "coloque o seu comentário"

## Criar um repositório na minha conta do Github com nome do projeto
    Ex.: agencia | agenciaRh ou agencia-rh

## Capturar o link do git remote em ssh
    Ex.: git@github.com:gleisosantos/agencia.git

## Subir o projeto para GitHub 
    git push -u origin main (ou branch atual)