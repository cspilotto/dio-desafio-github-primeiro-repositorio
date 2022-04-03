# GIT:computer:

## Git é um software de versionamento de código

### A navegação via command line interface

#### No Windows

​	CD: navegação entre pastas

​	DIR: diretório/pastas

​	MKDIR: criar uma pasta

​	CLS: limpar o terminal e também CTRL + L para limpar

​	DEL: deleta o arquivo

​	RMDIR: deleta o diretório

​	LS: listar

​	

## Instalação do GIT

Acessar o link: https://git-scm.com/download/win



# Primeiros comandos com GIT

GIT INIT

GIT ADD

GIT COMMIT

#### Como criar um repositório?

1º Criar uma pasta em um local especifico para armazenar os arquivos, por exemplo em C:.

2º Navegue até a pasta, clique com o botão direito do mouse e abra o GIT BASH

3º Para criar uma pasta dentro, digite:

> mkdir nome-da-pasta

Para verificar, seguir os passos:

> ls
>
> cd nome-da-pasta

4º Para iniciar o GIT nesta pasta:

>  git init

Após, caso queira verificar os arquivos ocultos dentro desta pasta, digite

> ls -a

5º Criando o primeiro arquivo - Primeiro realizamos a configuração. Para configurar, digite:

> git config -- global user.email "seu.email@seu.email.com"

>  git config -- global user.name "seuusername"

Feito as configurações, agora iremos adicionar o arquivo. Para isso, navegue até a pasta nome-da-pasta, clique com o botão direito do mouse e crie um novo arquivo de texto: exemplo.md

## *Observação importante*: Arquivos com extensão .md são arquivos MARKDOWN. Para você conseguir alterar a extensão do seu arquivo de texto é necessário ter instalado em seu computador um editor de texto com suporte ao Markdown. Estamos usando o TYPORA. Link para download: https://typora.io/

6º Após criar o seu arquivo, e escrever o conteúdo dentro, iremos "commitar" o arquivo. No GIT BASH, digite:

> git add *
>
> git commit -m "commit inicial"





​	

