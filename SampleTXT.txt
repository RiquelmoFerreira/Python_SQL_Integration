CREATE DATABASE SampleDatabase

USE SampleDatabase
CREATE TABLE SampleSales(
	sale_id int,
	customer varchar(50),
	car_name varchar(50),
	sale_date date,a
	price decimal(7,2),
	quantity int,
)

INSERT INTO SampleSales(sale_id, customer, car_name, sale_date, price, quantity)
VALUES
	(1, 'John', 'Honda Civic', '31/03/2023', 21700, 1),
	(2, 'Wade', 'Ford Raptor', '23/03/2023', 51130, 1),
	(3, 'Emma', 'Honda Accord', '12/01/2023', 26520, 1),
	(4, 'Olivia','Dodge Challenger', '01/02/2023', 68320, 1),
	(5, 'Ivan', 'Dodge Charger', '31/03/2023', 31350, 1)

USE SampleDatabase
SELECT *
FROM SampleSales
