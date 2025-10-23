# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: (cars)

- plate CHAR(7) UNIQUE NOT NULL PK INDEX
- brand VARCHAR(30) NOT NULL
- model VARCHAR(30) NOT NULL
- type VARCHAR(30) NOT NULL
- power SMALLINT NOT NULL
- shift_type VARCHAR(15) NOT NULL
- color VARCHAR(100) NOT NULL
- optionals TEXT NULL
- year YEAR NOT NULL
- chilometers MEDIUMINT NOT NULL
- fuel_type VARCHAR(20) NOT NULL
- last_revision DATE NULL
- last_oil_control_km MEDIUMINT NULL
- price DECIMAL(9,2) NOT NULL
- incidents TINYINT NOT NULL
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