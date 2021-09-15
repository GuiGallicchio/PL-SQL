# Selecionando todas Colunas

```sql
SELECT * 
  FROM departamento;
```
**Resultado da execução do SELECT:**

|departamento_id| nm_departamento| localizacao|
|---------------|----------------|------------|
|              1| Suporte        | Limeira    |
|              2| Administração  | São Paulo  |
|              3| Desenvolvimento| Campinas   |

Pode exibir o resultado de todas as colunas de dados de uma tabela colocando um asterisco (\*) logo após a palavra chave SELECT. Neste exemplo feito acima, a tabela de departamentos possue três colunas **(departamento_id, nm_departamento, localizacao)**, ao executar o select podemos ver que o resultado é que a tabela possui três linhas, uma para cada departamento.

Também é possivel exibir todas as colunas da tabela apenas listando-as depois da palavra chave **SELECT**. Exemplo abaixo, o comando SQL também exibe todas as colunas e todas linahs da tabela de departamentos.

```sql
SELECT departamento_id, nm_departamento, localizacao
  FROM departamento;
```

 
