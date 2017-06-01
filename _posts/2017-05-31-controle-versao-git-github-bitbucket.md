---
layout: post
cover: 'false'
title: Controle de Versão,Git, Github e Bitbucket – Afinal, o que é tudo isso ?
date: 2017-05-31 19:35:00
tags: git controle-de-versionamento
subclass: 'post tag-fiction'
categories: 'controle de versionamento'
---

Naquele curso técnico ou na graduação, todo iniciante já deu os seus “pulos de gato” para entregar o TCC. Programar paralelamente a um colega pode parecer uma ideia complicada. Você programa, manda a pasta pra ele, ele programa e te passa de novo. E seu eu dissesse que existe uma coisa chamada **controle de versionamento**, e que ela acabaria com esse dor de cabeça ?

####Controle de Versão####

Um sistema de **controle de versão**(nome auto-explicativo) tem o objetivo de gerenciar diferentes versões de um mesmo projeto. É possível obter históricos das modificações, permitir que vários programadores trabalhem no mesmo projeto e permitir um comparativo entre várias versões do projeto.

Dentre as muitas funções do **controle de versão** existem 3 que são características fundamentais:

#####Ele salva seu histórico#####
Qualquer alteração no projeto, aquela linha modificada, ele irá salvar a modificação. Isso ajuda muito para saber o que foi mudado de uma versão para outra.

#####Você pode desenvovler versões diferentes#####
Os sistemas possuem **branches**(ramificações), permitindo que você crie versões diferentes do mesmo sistema sem afetar outros.

#####Programar em paralelo#####
Permiti que os desenvolvedores possam programar paralelamente sem haver alterações no código alheio.

####Como funciona####

O projeto fica armazenada no servidor(repositório), onde ficam armazenados os históricos e modificações de cada versão. O desenvolvedor pode baixar a última versão e trabalha-la e posteriormente atualizar a versão contida no servidor.

![My helpful screenshot]({{ site.baseurl }}/assets/images/post/controle-de-versao-git-github-bitbucket/1.png)

Essa **sincronização** de arquivos entre a **estação de trabalho** e o **servidor** é feito através dos comandos **commit** e **update**.

O **commit** envia o conjunto de arquivos alterados ao servidor, gerando um novo histórico de atualização. O **update** faz o inverso, mandando a última versão dele ao computador do desenvolvedor.

####Controle de Versão Centralizado####

Seguindo a **topologia em estrela**, existe **apenas um servidor** e **várias** cópias do projeto nas diversas **estações de trabalho**. Para haver comunicação entre as estações de trabalho, tal como a topologia, elas precisam passar pelo servidor.

![My helpful screenshot]({{ site.baseurl }}/assets/images/post/controle-de-versao-git-github-bitbucket/2.png)

####Controle de Versão Distribuído####

Nesse tipo de controle, cada **estação de trabalho** possui seu próprio “servidor”, onde faz as operações básicas de commit e update, além de cada estação de trabalho poder comunicar-se diretamente com a outra.

![My helpful screenshot]({{ site.baseurl }}/assets/images/post/controle-de-versao-git-github-bitbucket/3.png)

####GIT####

GIT é um dos muitos sistemas para controle de versão. É rápido, possui um design simples, gratuito, fácil instalação, configuração e baixa curva de aprendizado.

Segue abaixo alguns termos que você verá muitas vezes no terminal de comando e também de outros sistemas:

Commit: Salvar alterações realizadas.

Branch:  Cria uma nova ramificação do projeto – assim como em uma árvore -, permitindo seguir várias “linhas” diferentes de desenvolvimento para o mesmo projeto.

Clone: Copiar um projeto já existente de algum repositório para sua estação de trabalho.

Fork: Faz a cópia do repositório para outro repositório(Um projeto em uma conta do Github para outra conta).

Merge: Junção de branches.

####Github & Bitbucket####

Você já sabe pelo menos um pouco o que é controle de versão, conhece uma ferramenta pra isso, o Git, e agora conhecerá 2 repositórios para alocar seu projeto.

Quem já procurou um pouco de projetos na internet percebeu que o Github aloca a maioria esmagadora deles. Abaixo citarei alguns diferenciais de cada repositório para você tirar suas conclusões:

Github & Bitbucket
Você já sabe pelo menos um pouco o que é controle de versão, conhece uma ferramenta pra isso, o Git, e agora conhecerá 2 repositórios para alocar seu projeto.

Quem já procurou um pouco de projetos na internet percebeu que o Github aloca a maioria esmagadora deles. Abaixo citarei alguns diferenciais de cada repositório para você tirar suas conclusões:

|        |Repositório Públic  |Repositório Privado|Quantidade de Usuários|Preço
Github   |Sim	              |Sim	              |4 milhões	         |Por 25 dólares até 10 repositório, tendo aumento variado até de 100 dólares.
Bitbucket|Sim  	              |Sim	              |1 milhão	             |De graça até 5 repositórios. Com o aumento o preço pode variar de 10 até 200 dólares.