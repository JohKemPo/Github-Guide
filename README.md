
<!-- <a href="https://github.com/anuraghazra/github-readme-stats"> github-readme-stats </a><br>
<a href="https://github.com/tandpfun/skill-icons"> skill-icons </a><br>
<a href="https://github.com/VishwaGauravIn/pretty-readme-badges"> pretty-readme-badges </a><br>
<a href="https://github.com/alexandresanlim/Badges4-README.md-Profile"> Badges4-README.md-Profile </a><br>
<a href="https://github.com/anuraghazra/github-readme-stats"> github-readme-stats</a><br>
<a href="https://github.com/vn7n24fzkq/github-profile-summary-cards"> github-profile-summary-cards </a><br>
<a href="https://github.com/ryo-ma/github-profile-trophy"> github-profile-trophy</a><br>
<a href="https://github.com/DenverCoder1/github-readme-streak-stats"> github-readme-streak-stats </a><br>
<a href="https://github.com/Ashutosh00710/github-readme-activity-graph"> readme-activity-graph </a><br>
<a href="https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_pt-BR.md">Markdown Tutorial </a><br>
<a href="https://docs.github.com/pt/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks"> rCriar e realçar blocos de código</a><br>
<https://github.com/iuricode/padroes-de-commits><br>
<https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657><br>
<https://blog.betrybe.com/git/git-branch/><br>
<https://www.conventionalcommits.org/en/v1.0.0/#summary><br>
 -->


<div align="center">
  <!-- <img src="images/2.png"width=" 80px">
  <img src="images/3.png"width=" 80px"> -->
  <img src="images/4.png"width=" 120px">
  <img src="images/1.png"width=" 120px">
  <h1>Guia prático de Git e Github</h1>
</div>

<p align = "justify"> &emsp; Este repositório fornece um guia abrangente sobre o Git e o GitHub, duas ferramentas essenciais para o controle de versão e colaboração no desenvolvimento de software. </p>


<h2 align="center">S U M A R I O</h2>
<br>

1. [Introdução](#capitulo1)
   - O que é Git? 
   - O que é Github? 
   - O que é Versionamento de Código?
   - Vantagens do Versionamento de Código
   - Tipos de estado de um arquivo

2. [Capítulo 1: Git Básico](#capitulo2)
    1. Instalação do Git
        - Como instalar o Git no Windows
        - Como instalar o Git no macOS
        - Como instalar o Git no Linux
    1. Configuração Inicial do Git
        - Configurando seu nome de usuário e email
        - Configurando seu editor de texto preferido
        - Configurações globais e locais do Git
    1. Conceitos Fundamentais do Git
        - Repositórios Git
        - Commits
        - Branches
        - Tags
        - Working directory, Staging area e Repository
    1. Comandos Básicos do Git
        - git init: Iniciando um repositório Git
        - git clone: Clonando um repositório
        - git add: Adicionando alterações ao Staging area
        - git commit: Criando um commit
        - git status: Verificando o status do repositório
        - git log: Visualizando o histórico de commits
        - git diff: Comparando mudanças
        - git reset: Desfazer commits
        - Comandos para Modificar o Estado de um Arquivo

3. [Capítulo 2: Trabalhando com Branches](#capitulo3)
    1. Branches no Git
        - O que é uma branch?
        - Criando e alterando branches
        - Excluindo branches
    1. Merges e Conflitos
        - Merging de branches
        - Resolvendo conflitos de merge
        - Rebase vs. Merge
    1. Fluxo de Trabalho Básico
        - Criando e trabalhando em uma nova branch
        - Fazendo commits em uma branch
        - Merging de uma branch

4. [Capítulo 3: GitHub](#capitulo4)
    1. Criando uma Conta no GitHub
        - Configurando seu perfil
        - Criando uma organização (se aplicável)
    2. Trabalhando com Repositórios
        - Criando um novo repositório
        - Configurações do repositório
        - Clonando um repositório
        - Issues e Pull Requests
    1. Colaboração no GitHub
        - Colaboradores e permissões
        - Forking de repositórios
        - Trabalhando em colaboração
        - Revisão de código
    1. Segurança
      - Chave SSH
      - Token

5. [Capítulo 4: Dicas e Boas Práticas](#capitulo5)
    - Boas práticas de escrita de mensagens de commit
    - Organização de commits
    - Uso eficiente de branches
    - Mantendo um repositório limpo

## Apêndices

1. [Apêndice A: Solução de Problemas Avançados](#appendix-a)
    - Erros de Git
    - Problemas de Conflitos
    - Problemas de Desempenho
    - Problemas de Autenticação
    - Problemas de Configuração
    - Problemas de Gerenciamento de Branches
    - Problemas de Integração de Terceiros

2. [Apêndice B: Referências Adicionais e Leitura Recomendada](#appendix-b)
    - Recursos adicionais

3. [Apêndice C: Links Úteis para Recursos, Plugins e Extensões](#appendix-c)
    - Recursos adicionais online

</div>


<br>

<h2 id="capitulo1">Introdução</h2>
<h3 id="">O que é o Git?</h3>
<p align = "justify"> &emsp; O Git é um sistema de controle de versão distribuído que permite rastrear as mudanças em um conjunto de arquivos ao longo do tempo. Ele é amplamente utilizado para o gerenciamento de código fonte em projetos de desenvolvimento de software, mas pode ser usado para qualquer tipo de arquivo.</p>

<h3 id="">O que é o GitHub?</h3>
<p align = "justify"> &emsp; O GitHub é uma plataforma web que usa o Git para hospedar repositórios de código fonte e colaboração em projetos. Ele oferece recursos como controle de acesso, rastreamento de problemas (issues), solicitações de pull (pull requests) e muito mais.</p>

<h3 id="">Vantagens do Versionamento de Código</h3>
<p align = "justify"> &emsp; O versionamento de código oferece uma série de benefícios que são fundamentais para o desenvolvimento de software colaborativo e gerenciamento de código-fonte. </p>

1. **Colaboração Eficiente:** Permite que várias pessoas trabalhem em um projeto simultaneamente, rastreando quem fez quais alterações.

2. **Histórico de Alterações:** Mantém um registro completo de todas as modificações feitas em um projeto ao longo do tempo.

3. **Experimentação Segura:** Os desenvolvedores podem criar branches para experimentar novos recursos ou correções sem afetar a versão principal do projeto.

4. **Rastreamento de Bugs:** Facilita a identificação e correção de problemas, permitindo que os desenvolvedores voltem a versões anteriores para isolar bugs.

5. **Recuperação de Versões Anteriores:** Possibilita a restauração de versões anteriores de um projeto, caso seja necessário reverter as alterações.


<h3 id="">Tipos de Estado de um Arquivo</h3>
<p align = "justify"> &emsp; Quando se trabalha com Git, os arquivos em um repositório podem estar em diferentes estados. Esses estados refletem o status do arquivo em relação ao controle de versão. Os quatro tipos principais de estados de um arquivo são:</p>

1. **Untracked:** Arquivos que o Git não está rastreando. Isso significa que o Git não tem conhecimento desses arquivos. Para rastreá-los, você precisa adicioná-los ao Git.

1. **Staged:** Arquivos que estão preparados para serem incluídos no próximo commit. Quando você realiza alterações em um arquivo e o "adiciona" ao Staging area, ele entra nesse estado.

1. **Unmodified:** Arquivos que não foram alterados desde o último commit. Quando um arquivo é confirmado, ele fica neste estado até sofrer novas alterações.

1. **Modified:** Arquivos que foram alterados desde o último commit. Quando você faz alterações em um arquivo rastreado, ele entra neste estado.

<p align = "justify"> &emsp;Entender e gerenciar esses estados é fundamental para o uso eficaz do Git, pois permite controlar quais alterações serão incluídas em um commit. O comando `git status` é usado para verificar o estado atual dos arquivos no repositório.</p>

<p align = "justify"> &emsp;</p>

<h2 id="Equipe">Equipe</h2><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |<https://github.com/JohKemPo>   |<https://www.linkedin.com/in/joao-vitor-de-moraes/>|