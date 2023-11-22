## O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados.

## O papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados.

Nesse **bootcamp DATABASE**, tivemos um breve introdução a respeito da utilização de banco de dados **NoSQL**. Aprendemos sobre a as diferenças e comparação de desempenho entre ele e o SQL, onde  a velocidade acaba sendo o fator mais importante na decisão de qual banco utilizar em nossa aplicação. Conhecemos muitas opções de bancos de dados NoSQL com diferentes funcionalidades que podem úteis **de acordo com o contexto**. 
O que devemos considerar na escolha entre um **banco de dados relacional (SQL)** e um **não-relacional (NoSQL)**?

Vamos relembrar um pouco sobre cada uma dessas tecnologias?


## SQL

**SQL** é a sigla, em inglês, para **“Structured Query Language”**, ou sem português, **“Linguagem de Consulta Estruturada”**. 
É essa linguagem que utilizamos para de consultar informações em um banco de dados relacional, executando vários comandos para criar, alterar, gerenciar, consultar, inserir (entre outras) informações no seu banco de dados. 
Bancos de dados SQL seguem uma modelagem relacional, com os dados sendo organizados  em tabelas. 

## NoSQL

**NoSQL** é a sigla em inglês para **"Not Only SQL"**, ou no inglês literal, **"Não Somente SQL"**,  é o termo utilizado para banco de dados não relacionais de alto desempenho, onde geralmente não é utilizado o SQL como linguagem de consulta dos dados. 
O **NoSQL** foi criado para ter uma performance melhor e uma escalabilidade mais horizontal para suprir necessidades onde os bancos relacionais não são eficazes. 
De forma geral, temos 4 tipos de bancos de dados NoSQL:

-   **Documento**  – Os dados são armazenados como documentos. Os documentos podem ser descritos como dados no formato de chave-valor, como por exemplo, o padrão JSON. Um exemplo de banco de dados neste formato é o **MongoDB**;
    
-   **Colunas**  – Os dados são armazenados em linhas particulares de tabela no disco, podendo suportar várias linhas e colunas e sub-colunas. Um banco de dados muito utilizado nessa vertente é o Cassandra;
    
-   **Grafos**  – Os dados são armazenados na forma de grafos (vértices e arestas). Para esse seguimento, temos o banco de dados Neo4j;
    
-   **Chave-valor**  – É a família de bancos NoSQL que suporta mais carga de dados, uma vez que ele traz o conceito de que um determinado valor seja acessado através de uma chave identificadora única. O Riak é um exemplo de banco de dados que utiliza chave-valor.


## Conclusão

O **Engenheiro de Dados** terá muitas vantagens ao utilizar o banco de dados **NoSQL**, mas isso não quer dizer que deverá ser usado em todas as situações, sem analizar com critério o contexto. 
Haverá contextos em que o profissional deverá usar o modelo relacional, por fazer mais sentido na aplicação. 
O **NoSQL** é mais indicado para aplicações que demandem mais armazenamento e alto desempenho do banco de dados.

Conforme aprendemos ao longo da jornada, o **NoSQL** não veio para substituir o **SQL**.
Ele foi criado com a idéia de ser uma alternativa de um banco de dados mais flexível no suporte de dados. 
É importante entender que uma boa prática seria trabalhar com uma arquitetura de dados híbrida, dessa forma, beneficiando-se do melhor dos 2 mundos.
