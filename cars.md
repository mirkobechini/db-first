# db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## Table name: (cars)

- plate CHAR(7)
- brand VARCHAR(30)
- model VARCHAR(30)
- type VARCHAR(30)
- power SMALLINT
- shift_type VARCHAR(15)
- color VARCHAR(100)
- optionals TEXT
- year YEAR
- chilometers MEDIUMINT
- fuel_type VARCHAR(20)
- last_revision DATE
- last_oil_control_km MEDIUMINT
- price DECIMAL(9,2)
- incidents TINYINT
- note TEXT


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