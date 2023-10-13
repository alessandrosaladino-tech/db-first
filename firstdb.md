# db-first

Boolean Class 104 exercise: First DB Template

## DATABASE NAME: used_cars

id: PRIMARY_KEY, UNIQUE, INT, NOTNULL, AUTO_INCREMENT,

Brand: VARCHAR(10), NOTNULL //es: Mercedes-Benz

Model: VARCHAR(50), NOTNULL //es: Coupè AMG Line GTronic

Fuel_type: VARCHAR(10), NOTNULL //es: GPL, diersel, gas

Km: FLOAT(5, 3), NULL //es: 30,000 Km

Color: VARCHAR(10), NULL

Gearbox: VARCHAR(10), NOTNULL //es: manual, auto

Horse_power: SMALLINT, NULL //es: 204 CV

Year: YEAR, NULL

Description: TEXT, NULL

Status: VARCHAR(20), NULL //es: Like new, good, minor scratches, ecc...

Price: DECIMAL(5, 3), NULL //es: 20.000€
