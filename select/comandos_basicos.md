# Executando comandos de SQL básico

```sql
 SELECT [ DISTINCT ] {*, colunas [alias], ...}  
   FROM tabela;
 ```
  
  Um comando de SELECT simples deve incluir o seguinte:
- Uma cláusula SELECT no qual especifica as colunas que serão exibidas.
- Uma cláusula FROM no qual especifica as tabelas que contém as colunas informadas na cláusula SELECT.

Na sintaxe:
* **SELECT**       lista de uma ou mais colunas&nbsp;
* **DISTINCT**     suprime duplicidades
*  **\***            selectiona todas as colunas da tabela
* **colunas**      seleciona as colunas informadas
* **alias**        inclui títulos diferentes para a coluna informada
* **FROM tabela**  especifica a tabela que contém as colunas informadas no SELECT
