# My Finance Web
 My Finance - Projeto do Curso de Pós-Graduação em Engenharia de Software da PUC-MG.

## 💻 Arquitetura

    A figura abaixo representa a modelagem lógica da aplicação e DER - Diagrama de Entidades e Relacionamentos.

<img src="docs\DER.png" alt="diagram">

<hr />

    A tabela de transação irá guardar as informações de novos lançamentos criados pela usuário. Enquanto a tabela de Plano de Contas será utilizado como uma enumeraçao de tipos diferentes de transações. Esta segunda tabela é importante para facilitar a agregação de dados produzidos para a tabela de Transações.

## 💼 Sistemas

    Requisitos
    Instalar:

    * Windows 10 Home Single Language
    * Git 2.37.1
    * Visual Studio Code 1.71.0
    * SQL Server 2019
    * .NET 6
    * Bootstrap 5


## 🏃 Execução

    Clonar o projeto.
    Executar no SQL Server o script para criação das tabelas e inserção de linhas.
    Abrir a pasta do projeto no Visual Studio Code.
    No terminal do Visual Studio Code, executar os comandos apropriados para fazer o build ou rodar o projeto.

    Acessar a pasta principal:

    cd ./myfinance-web-netcore
    Compilar e rodar o projeto:
    Constrói a aplicação para produção

    dotnet build
    Executa o codigo compilado

    dotnet run
    Acesse o projeto através do link que irá aparecer no terminal

## 🖥️ Telas

<img src="docs\Tela_welcome.png" alt="diagram">

<img src="docs\Tela_transacao.png" alt="diagram">

<img src="docs\Tela_transacoes.png" alt="diagram">

<img src="docs\Tela_planocontas.png" alt="diagram">

<hr />

## 🤟 Agradecimento

    Obrigado ao professor Filipe por comparilhar e ajudar os alunos no desenvolvimento de todo o trabalho!
    
