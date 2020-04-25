create database cars_Db

create table car_efficiency(
	Manufacturer varchar(25) not null Primary Key,
	CO2_Emissions float not null,
	CO_Emissions float not null);

create table car_sales(
	Manufacturer varchar(25) not null Primary Key,
	Sales_Thousands float not null,
	Fuel_Efficiency float not null);
	
	
SELECT car_sales.manufacturer, car_sales.sales_thousands, car_sales.fuel_efficiency, car_efficiency.co2_emissions,
car_efficiency.co_emissions
FROM car_sales
JOIN car_efficiency
ON car_efficiency.manufacturer = car_sales.manufacturer;