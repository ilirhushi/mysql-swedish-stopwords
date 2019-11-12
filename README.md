# mysql-swedish-stopwords

## 1.Create a table to store your keywords-

```
CREATE TABLE sv_stopwords
(
    value VARCHAR(30)
) ENGINE = INNODB;
```

## 2. run the mysql script to insert the stopwords
## 3. mysql > SET GLOBAL innodb_ft_server_stopword_table = 'database_name/my_stopwords';
