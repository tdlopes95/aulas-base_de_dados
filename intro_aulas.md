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

Terminologia associada:
Relação - Uma relação é uma tabela com colunas e linhas
Atributo - Um atributo é uma coluna com nome e que pertence a uma relação.
Domínio - Um domínio é o conjunto de valores permitidos para um ou mais atributos.
Tuplo - Um tuplo é uma linha de uma relação.
Grau - O grau de uma relação é o número de atributos que ela contém.
Cardinalidade - A cardinalidade de uma relação é o número de tuplos que ela contém.
Base de Dados Relacional - Uma coleção de relações normalizadas com diferentes nomes para as relações.

Restrições de Integridade
Null - Representa um valor para um atributo que é actualmente desconhecido ou não é aplicável para este tuplo.
Integridade da entidade - Numa relação base, nenhum atributo de uma chave primária pode ser nulo.
Integridade referencial - Se existe uma chave estrangeira em uma relação, ou o valor de chave estrangeira deve corresponder a um
valor da chave candidata de um tuplo dessa relação ou o valor de chave estrangeira deve ser nula.

Diagrama ER
Projeto de BD
1-Relacionamento entre as entidades Diagrama ER;
2-Refinamento;Normalização;
3-Implementação de SGBD;
