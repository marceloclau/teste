# teste
- Descompacte o arquivo prova.zip no workspace:

A estrutura ficará como abaixo:

/prova/ex1_numeros
/prova/ex2_session_cookie
/prova/ex3_dao
/prova/ex4_rest
/prova/frameworks_e_bibliotecas
.htaccess
dump_mysql.sql
manual.txt

- Copie o arquivo .htaccess para o seu Apache na raiz do site.

- No Mysql realize o restore do arquivo dump_mysql.sql

- Ajuste a conexão do banco de dados mysql nos arquivos abaixo:

\prova\ex3_dao\class\sql\ConnectionProperty.class.php
\prova\ex4_rest\class\sql\ConnectionProperty.class.php

----------------------------------------------------------------------

Sobre o exercício 4 seguem abaixo os métodos:

- Listar todos os itens:

http://127.0.0.1/prova/ex4_rest/list/

- Listar um único item por id:

http://127.0.0.1/prova/ex4_rest/list/1/

- Inserir um novo registro:

http://127.0.0.1/prova/ex4_rest/list/i/?titulo=Tarefa1&descricao=Manuais&prioridade=1

- Update de um registro

http://127.0.0.1/prova/ex4_rest/list/u/?id=3&titulo=teste&descricao=teste&prioridade=1

- Remover um registro

http://127.0.0.1/prova/ex4_rest/list/e/?id=1

-------------------------

Referencias

http://phpdao.com/index_pt.php

http://phppot.com/php/php-restful-web-service/

https://webdevdoor.com/php/mod_rewrite-windows-apache-url-rewriting
