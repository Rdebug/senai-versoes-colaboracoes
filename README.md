# senai-versoes-colaboracoes

**Comandos Básicos para a funcionalidade GIT.**

Para instalar a ferramenta git podemos seguir o passo a passo descrito no próprio site do GIT, atentando apenas para o seu sistema operacional.

![Download GIT](https://git-scm.com/images/logo@2x.png)

[Página para Download GIT](https://git-scm.com/downloads)

Para configurar suas informações no git utilizaremos dois comandos básicos. 

Para configurar o seu nome na ferramenta git utilizaremos o código:

* *git config --global user.name "Seu Nome"*

Para configurar o seu email na ferramenta git utilizaremos o código:

* *git config --global user.email "Seu Email"*

Sempre ao iniciar um projeto temos a opção de entrar na pasta do projeto pelo terminal e iniciar o git pelo comando:

* *git init*

Isso irá criar um subdiretório git que irá conter toda a estrutura padrão do git. Até aqui nada é rastreado mas agora tempos todas as ferramentas para monitorar e organizar nosso projeto.
Para adicionar seus arquivos para o staging, usaremos o comando:

* *git add *

Nesse momento se quisermos verificar as alterações que estão no nosso staging podemos utilizar o camando""

* *git status*

Para confirmar todas as adições, alterações ou exclusões que estão no staging usaremos o comando:

* *git commit -m "comentário"*

Para trabalharmos em um ambiente separado da nossa versão principal podemos criar uma branch(ramo) com o seguinte comando:

* *git checkout -b "nome da branch*

Com esse comando entraremos na branch escrita e caso a branch não exista, ela irá ser criada.
Quando queremos juntar as modificações 'comitadas' em outra branch podemos utilizar o comando:

* *git merge "nome da branch"*

Por fim, mas não menos importante, para subirmos todas as informações comitadas para nosso repositório online podemos utilizar o comando:

* *git push origin master*

E para fazer o caminho inverso, ou seja, tudo da nosso repositório local é só utilizar o comando:

* *git pull*

Lembrando que quando trabalhamos com repositório online precisamos fazer as devidas configurações para se conectar corretamente com ele, descritos na documentação de cada site que trabalha com repositório git.


Lista de Comandos:
* git config --global user.name "Seu Nome""
* git config --global user.email "Seu Email"
* git init
* git add 
* git commit -m "comentário"
* git status
* git log
* git checkout -b "nome da branch"
* git merge "nome da branch"
* git push origin master
* git pull

