# mysql-swedish-stopwords

## Full-Text MySQL Stopwords for Swedish language

1. Create a table to store your keywords

```
CREATE TABLE sv_stopwords
(
    value VARCHAR(30)
) ENGINE = INNODB;
```

2. run the mysql script to insert the stopwords: `insert_stopwords.mysql`
3. then run mysql > `SET GLOBAL innodb_ft_server_stopword_table = 'database_name/sv_stopwords';`
