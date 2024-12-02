# Db structure
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name
- cars

## Tambe structure
- id | BIGINT - AUTO_INCREMENT - PRIMARY_KEY - UNIQUE - NOT_NULL
- model | VARCHAR(100) - NOT_NULL
- brand | VARCHAR(100) - NOT_NULL
- year | YEAR - NOT_NULL
- type (SUV, sportiva, ...) | VARCHAR(100) - NOT_NULL
- price | DECIMAL(10,2) - NOT_NULL
- Fuel | VARCHAR(100) - NOT_NULL
- Interior_color | VARCHAR(50) - NULL
- Exterior_color | VARCHAR(50) - NULL
- trasmission | VARCHAR(50) - NULL
- power (cavalli) | SMALLINT - NOT_NULL
- available | TINYINT - DEFAULT(1)
- condition (nuova, usata, ...) | VARCHAR(50) - NULL
- description | VARCHAR(500) - NULL

