| COLONNA             | TIPO        | ATTRIBUTI                 |
| ------------------- | ----------- | ------------------------- |
| id                  | bigInt      | PRIMARY KEY,Autoincrenent |
| marca               | varchar(50) | NOT NULL                  |
| modello             | varchar(50) | NOT NULL                  |
| carburante          | varchar(50) | NOT NULL                  |
| km                  | FLOAT(8,2)  | NULL                      |
| cilindrata          | FLOAT(6,2)  | NULL                      |
| data_produzione     | YEAR        | NOT NULL                  |
| data_di_acquisto    | DATE        | NULL                      |
| data_di_vendita     | DATE        | NULL                      |
| condizioni          | TINYINT     | DEFAULT(10),UNSIGNED      |
| luogo_di_produzione | VARCHAR(20) | NOT NULL                  |
| colore              | VARCHAR(20) | NULL                      |
| tipologia           | VARCHAR(20) | NULL                      |
| prezzo_vendita      | FLOAT(8,3)  | NULL ,UNSIGNED            |
| prezzo_netto        | FLOAT(8,3)  | NULL ,UNSIGNED            |
| prezzo_di_acquisto  | FLOAT(8,3)  | NOT NULL ,UNSIGNED        |
| porte               | TINYINT(1)  | NULL                      |
| posti               | TINYINT(2)  | NULL                      |
| ricondizionata      | TINYINT(1)  | DEFAULT(0)                |
