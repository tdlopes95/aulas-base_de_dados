Conceitos Basicos:
Dados:algo do mundo real
Informação:algo util que pode ser extraido direta ou indiretamente a partir dos dados
Base de Dados(BD): coleção de dados interrelacionados e persistentes
-integrados
-compartilhados

Base de dados=instância de dados + meta dados

instancia de dados: dado propriamente

meta dados: dicionario de dados:
-esquema de base de dados;
-acedido através de linguagens de definição de dados.

->Nos sistemas tradicionais a segurança era muito fraca e havia perda de dados

SGBD -> Software que nos vai ajudar a trabalhar com as nossas BDs.
Exemplos:
    -Livres:
        -Firebird;
        -PostgreSQL;
        -MySQL.

    -Comerciais:
        -Oracle;
        -DB2;
        -SQLServer.

Um esquema de base de dados é especificado por um conjunto de definições expressas por uma linguagem especial chamada linguagem de definição de dados (Data Definition 
Language)

Select * from T -> Visualizar toda a info da tabela T
Select C1 from T -> Visualizar na tabela T com o atributo C1
Select * from T where C1=1 -> Visualizar toda a tabela T dados com o atributo C1=1