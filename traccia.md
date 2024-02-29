Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.


Colonne|Tipo|Attributi
---|---|---
id| bigint | AUTO_INCREMENT
chassis | CHAR(17) | UNIQUE,NOTNULL
brand | VARCHAR(20)| NOTNULL
model | VARCHAR(20) | NOTNULL
plate | VARCHAR(10) | NULL, UNIQUE
kms | MEDIUMINT | NOTNULL
car_reg | DATE | NOTNULL
price | FLOAT(9,2) | NULL
color | VARCHAR(10) | NULL
power_supply | VARCHAR(5) | NOTNULL
engine_displacement | VARCHAR(4) | NOTNULL
trasmission | VARCHAR(6) | NOTNULL
