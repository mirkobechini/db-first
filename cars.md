# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: (cars)

- id: PK BIGINT AUTO INCREMENT NOT NULL UNIQUE
- brand VARCHAR(50) NOT NULL INDEX
- model VARCHAR(50) NOT NULL INDEX
- type VARCHAR(50) NOT NULL
- description: TEXT NULL
- year YEAR NOT NULL INDEX
- fuel_type VARCHAR(20) NOT NULL
- engine_size(cilindrata): CHAR(4) NULL
- horse_power: CHAR(3) NULL
- gear_box VARCHAR(15) NOT NULL
- chilometers MEDIUMINT/FLOAT(8,2) NULL
- price DECIMAL(8,2) NULL
- owners: TINYINT NULL
- seats: TINYINT NULL
- doors: TINYINT NULL
- traction: VARCHAR(20)
- is_available: TINYINT DEFAULT(0)
- status: VARCHAR(20) NULL
- vin: CHAR(17) UNIQUE NULL
- plate: VARCHAR(8) NULL

- last_revision DATE NULL
- last_oil_control_km MEDIUMINT NULL
- incidents TINYINT NULL
- color VARCHAR(50) NOT NULL
- optionals TEXT NULL
- note TEXT NULL


Esempio di auto:
- AA 000 AA
- peugeot
- 208
- station-wagon
- 115 CV
- Diesel
- Manual
- Orange
- unfoldable_roof, led_lights
- 2015
- 115.025
- 09/2020
- 100.003
- 30.000,00
- 1
- ...