
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
    1. [Instalação do Git](#instalacao)
        - Como instalar o Git no Windows
        - Como instalar o Git no macOS
        - Como instalar o Git no Linux
    1. [Configuração Inicial do Git](#inicial)
        - Configurando seu nome de usuário e email
        - Configurando seu editor de texto preferido
        - Configurações globais e locais do Git
    1. [Conceitos Fundamentais do Git](#funfamental)
        - Repositórios Git
        - Commits
        - Branches
        - Tags
        - Working directory, Staging area e Repository
    1. [Comandos Básicos do Git](#basico)
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
    1. [Branches no Git](#)
        - O que é uma branch?
        - Criando e alterando branches
        - Excluindo branches
    1. [Merges e Conflitos](#)
        - Merging de branches
        - Resolvendo conflitos de merge
        - Rebase vs. Merge
    1. [Fluxo de Trabalho Básico](#)
        - Criando e trabalhando em uma nova branch
        - Fazendo commits em uma branch
        - Merging de uma branch

4. [Capítulo 3: GitHub](#capitulo4)
    1. [Criando uma Conta no GitHub](#)
        - Configurando seu perfil
        - Criando uma organização (se aplicável)
    2. [Trabalhando com Repositórios](#)
        - Criando um novo repositório
        - Configurações do repositório
        - Clonando um repositório
        - Issues e Pull Requests
    1. [Colaboração no GitHub](#)
        - Colaboradores e permissões
        - Forking de repositórios
        - Trabalhando em colaboração
        - Revisão de código
    1. [Segurança](#)
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

<p align = "justify"> &emsp;Entender e gerenciar esses estados é fundamental para o uso eficaz do Git, pois permite controlar quais alterações serão incluídas em um commit. O comando <b><i>git status</i></b> é usado para verificar o estado atual dos arquivos no repositório.</p>

<h2 id="capitulo2">Git básico</h2>
<h3 id="instalacao">Instalação Git</h3>

### No Windows:

1. Acesse o site oficial do Git para Windows em https://git-scm.com/download/win.
1. Baixe o instalador para Windows.
1. Execute o arquivo de instalação baixado.
1. Siga as instruções do instalador, aceitando as configurações padrão, a menos que você tenha necessidades específicas.
1. Após a instalação, você pode verificar se o Git foi instalado corretamente executando o seguinte comando no Terminal:
```
git --version
```

### No macOS:

1. Use o Homebrew, um gerenciador de pacotes, para instalar o Git. Abra o Terminal e execute o seguinte comando:

```powershell
brew install git
```
1. Baixe o instalador para Windows.
1. Execute o arquivo de instalação baixado.
1. Siga as instruções do instalador, aceitando as configurações padrão, a menos que você tenha necessidades específicas.
1. Após a instalação, você pode verificar se o Git foi instalado corretamente executando o seguinte comando no Terminal:
```
git --version
```

### No Linux (Debian/Ubuntu):

1. No terminal execute o comando a seguir para instalar o Git:
```
sudo apt-get install git
```
1. Após a instalação, você pode verificar se o Git foi instalado corretamente executando o seguinte comando no Terminal:
```
git --version
```

<h3 id="inicial">Configuração Inicial do Git</h3>

<p align = "justify"> &emsp; Quando você instala o Git pela primeira vez, é importante configurar algumas informações iniciais, como seu nome de usuário e endereço de email, para que seus commits sejam identificados corretamente. Aqui estão as principais configurações iniciais:</p>

- Configurando seu nome de usuário e email:

  - Use os comandos git config para definir seu nome de usuário e endereço de email globalmente, para que sejam usados em todos os repositórios Git.
  - Exemplo:
  ```
  git config --global user.name "Seu Nome"
  git config --global user.email "seu@email.com"
  ```
  
- Configurando seu editor de texto preferido (Opicional):

  - Você pode escolher o editor de texto que deseja usar ao escrever mensagens de commit. Isso é configurado globalmente.
  - Exemplo: 
  ```
  git config --global core.editor "seu_editor_preferido"
  ```

- Configurações globais e locais do Git:
  - As configurações do Git podem ser definidas globalmente ou localmente para um repositório específico.
  - Configurações globais se aplicam a todos os repositórios em sua máquina.
  - Configurações locais se aplicam apenas a um repositório específico.
  - Para listar as cofigurações globais:
  ```
  git config --list
  ```

<h3 id="funfamental">Conceitos Fundamentais do Git</h3>
<p align = "justify"> &emsp; O Git é baseado em alguns conceitos fundamentais que são essenciais para entender como ele funciona:</p>

- **Repositórios Git:** Um repositório Git é um diretório que contém todos os arquivos do seu projeto, juntamente com um banco de dados especial para rastrear as alterações (histórico).

- **Commits:** Um commit é um snapshot do estado do seu projeto em um determinado momento. Cada commit tem uma mensagem descritiva que explica o que foi alterado.

- **Branches:** As branches são ramificações do desenvolvimento do seu projeto. Elas permitem que você trabalhe em funcionalidades ou correções separadamente, sem afetar o código principal.

- **Tags:** As tags são usadas para marcar pontos específicos no histórico do Git, como versões estáveis ou marcos importantes.

- **Working Directory, Staging Area e Repository:** O Working Directory é onde você faz as alterações nos arquivos. O Staging Area é onde você prepara as alterações para serem commitadas. O Repository é onde todas as alterações são armazenadas.

<h3 id="basico">Comandos Básicos do Git</h3>
<p align = "justify"> &emsp; O Git oferece uma variedade de comandos fundamentais que são essenciais para o gerenciamento de repositórios. Aqui estão os principais comandos e suas descrições:</p>

### git init: Iniciando um repositório Git
<p align = "justify"> &emsp;O comando <b><i>git init</i></b> é usado para iniciar um novo repositório Git em um diretório. Isso cria um ambiente de controle de versão para os arquivos naquele diretório.</p>

- Exemplo:
```
git init
```

### git clone: Clonando um repositório
<p align = "justify"> &emsp;O comando <b><i>git clone</i></b> permite criar uma cópia local de um repositório Git remoto. Isso é útil quando você deseja colaborar em um projeto existente ou trabalhar em diferentes máquinas.</p>

- Exemplo:
```
git clone URL_do_Repositório
```

### git add: Adicionando alterações ao Staging area
<p align = "justify"> &emsp;O comando <b><i>git add</i></b> é usado para adicionar alterações específicas de arquivos ao que é chamado de "Staging area". Isso prepara as alterações para serem incluídas no próximo commit.</p>

- Exemplo:
```
git add nome_do_arquivo
```

### git commit: Criando um commit
<p align = "justify"> &emsp;O comando <b><i>git commit</i></b> é usado para criar um novo commit que inclui todas as alterações que estão no Staging area. Cada commit deve ter uma mensagem descritiva.</p>

- Exemplo:
```
git commit -m "Mensagem do commit"
```
### git status: Verificando o status do repositório
<p align = "justify"> &emsp;O comando <b><i>git status</i></b> permite verificar o estado atual do repositório, mostrando quais arquivos foram modificados, adicionados ao Staging area ou estão não rastreados.</p>

- Exemplo:
```
git status
```

### git log: Visualizando o histórico de commits
<p align = "justify"> &emsp;O comando <b><i>git log</i></b> é usado para visualizar o histórico de commits do repositório. Isso inclui informações como o autor, data e mensagem de cada commit.</p>

- Exemplo:
```
git log
```

### git diff: Comparando mudanças
<p align = "justify"> &emsp;O comando <b><i>git diff</i></b> é utilizado para visualizar as diferenças entre o estado atual dos arquivos e o último commit. Isso é útil para entender as alterações feitas.</p>

- Exemplo:
```
git diff
```

### git reset: Desfazer commits
<p align = "justify"> &emsp;O comando <b><i>git reset</i></b>  é utilizado para desfazer commits. Ele permite mover os commits para um estado anterior e pode ser útil para corrigir erros ou reorganizar o histórico.</p>

- Exemplo:
```
git reset HEAD~1
```

<p align = "justify"> &emsp;HEAD~1: Esta parte do comando especifica o ponto para o qual você deseja reverter. O HEAD representa o commit mais recente na branch atual, e o ~1 indica que você deseja voltar um único commit. Se você desejar voltar mais de um commit, poderá ajustar o número após o til (~).</p>

<p align = "justify"> &emsp;Portanto, quando você executa git reset HEAD~1, o Git moverá a branch atual para o commit anterior, desfazendo o último commit. As alterações feitas no commit desfeito não são perdidas; elas voltam ao estado "unstaged" no diretório de trabalho, permitindo que você modifique e reconfigure as alterações antes de fazer um novo commit.</p>

### Comandos para Modificar o Estado de um Arquivo
<p align = "justify"> &emsp;Além dos comandos mencionados acima, também é possível usar git checkout para desfazer alterações não salvas em um arquivo específico e git reset para mover arquivos do estado "staged" para "unmodified" ou "modified".</p>


<h2 id="Equipe">Equipe</h2><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |<https://github.com/JohKemPo>   |<https://www.linkedin.com/in/joao-vitor-de-moraes/>|