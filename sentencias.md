# TAS8 - Sentencias where multicriterio

## 1. Contar el número de productos de una categoría específica.
  - Sentencia:
  ```
SELECT COUNT (*) AS products_total_computers
FROM product
WHERE category = 'Computers'
  ```
  - Captura:
<img src="./capturas/1.png"/>

## 2. Contar el número de clientes en una ciudad específica.
  - Sentencia:
  ```
SELECT COUNT (*) AS clients_total_NewYork
FROM client
WHERE city = 'New York'
  ```
  - Captura:
<img src="./capturas/2.png"/>
