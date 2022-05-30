Cars

Model:Car

Table:Cars


id: BIGINT (not null,unique)
model: VARCHAR(60) (NOT NULL)
doors: TINYINT(NOT NULL)
years: YEAR (NOT NULL)
equipment; VARCHAR(255) (NULL)
km: FLOAT(6,2) (NOT NULL)
kw: FLOAT(4,0) (NOT NULL)
price: DECIMAL(9,2)
color:VARCHAR(30) (NOT NULL)
engine: VARCHAR(30) (NOT NULL)
note: TEXT
description: TEXT
