# db-first

Boolean Class 104 exercise: First DB Template

## DATABASE NAME: used_cars

id: PRIMARY_KEY, UNIQUE, INT, NOTNULL, AUTO_INCREMENT,

Brand: VARCHAR(10), NOTNULL 

Model: VARCHAR(50), NOTNULL 

Fuel_type: VARCHAR(10), NOTNULL //es diesel, electric, ecc

Km: FLOAT(5, 3), NULL 

Color: VARCHAR(10), NULL

Gearbox: VARCHAR(10), NOTNULL //es automatic or manual

Horse_power: SMALLINT, NULL 

Year: YEAR, NULL

Description: TEXT, NULL

Status: VARCHAR(20), NULL //es new, used, crashed, ecc

Price: DECIMAL(5, 3), NULL 
