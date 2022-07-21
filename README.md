# 🎯 postgre-sql-DBeaver
Este repositório é um espaço reservado para armazenar o conteúdo de projetos, tutoriais e cursos que realizei para reforçar o aprendizado sobre Postgres, SQL e DBeaver.

## Sumário

- [Conhecendo as ferramentas](#ferramentas)
- [Instalação de Ferramenta](#instalacaoferramentas)
- [Instalação JDBC](#instalacaojdbc)
- [Revisão de Conceitos e Linguagem SQL](#revisao)

# Conhecendo as ferramentas (#ferramentas)

## 🐘 PostgreSQL
O PostgreSQL é um poderoso sistema de banco de dados relacional de objeto de código aberto que usa e estende a linguagem SQL combinada com muitos recursos que armazenam e dimensionam com segurança as cargas de trabalho de dados mais complicadas. As origens do PostgreSQL remontam a 1986 como parte do projeto POSTGRES na Universidade da Califórnia em Berkeley e tem mais de 30 anos de desenvolvimento ativo na plataforma principal. Para saber mais [clique aqui](https://www.postgresql.org/about/).

## 🦫 DBeaver
DBeaver é uma ferramenta de banco de dados universal gratuita e de código aberto para desenvolvedores e administradores de banco de dados. Para saber mais [clique aqui](https://dbeaver.io/about/)

# Instalação de Ferramentas (#instalacaoferramentas)

[Baixar e instalar PostgreSQL](https://www.postgresql.org/download/)

[Baixar e instalar DBeaver](https://dbeaver.io/download/)

# Instalação JDBC (#instalacaojdbc)

No DBeaver seguir os passos:
Flie>> New>> DBeaver>> DatabaseConnection>> PostgreSQL>> Next >> Download>> Finish
[Passo-a-passo](https://dbeaver.com/docs/wiki/Database-drivers/)

# Revisão de Conceitos e Linguagem SQL (#revisao)

## Tipos de dados 

[Tipos de dados do PostgreSQL](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-data-types/)

## Tipos de linguagem SQL

### DDL - Data Definition Language
- CREATE – para criar banco de dados e seus objetos como (tabela, índice, visualizações, procedimento de armazenamento, função e gatilhos)
- ALTER – altera a estrutura do banco de dados existente
- DROP – exclui objetos do banco de dados
- TRUNCATE – remove todos os registros de uma tabela, incluindo todos os espaços alocados para os registros.

### DML - Data Manipulation Language 
- SELECT – recupera dados do banco de dados
- INSERT – insere dados em uma tabela
- UPDATE – atualiza os dados existentes em uma tabela
- DELETE – Excluir todos os registros de uma tabela de banco de dados
- MERGE – operação UPSERT (inserir ou atualizar)

### DTL - Linguagem de Transação de Dados
- BEGIN TRAN (OU BEGIN TRANSACTION) – Marca o começo de uma transação no banco da dados  que pode ser completada ou não.
- COMMIT – Envia todos os dados da transação permanentemente para o banco de dados.
- ROLLBACK – Desfaz as alterações feitas na transação realizada.

### DCL - Data Control Language
- GRANT – permite que os usuários acessem privilégios no banco de dados
- REVOKE – retira os privilégios de acesso dos usuários dados usando o comando GRANT

# Conhecendo do DBeaver (#dbeaver)

# Aplicando Comandos em SQL

## Create
````
```
## Insert
## Update
## Delete
## Where
## And
## Or
## Operadores Condicionais
## Order By
## Funções Agregadas - Count, Max, Min, AVG, SUM
## Group By

