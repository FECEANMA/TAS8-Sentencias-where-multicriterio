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

## 3. Contar el número de productos cuyo precio está dentro de un rango específico 
  - Sentencia:
  ```
SELECT COUNT (*) AS product_100_500
FROM product
WHERE price > 100 AND price < 500
  ```
  - Captura:
<img src="./capturas/3.png"/>

## 4. Seleccionar clientes que viven en una ciudad específica y tienen un tipo de cliente específico
  - Sentencia:
  ```
SELECT *
FROM client
WHERE city = 'New York' AND type_of_client = 'BASIC'
  ```
  - Captura:
<img src="./capturas/4.png"/>

## 5. Seleccionar productos que pertenecen a una categoría específica y cuyo precio está por encima de un valor específico
  - Sentencia:
  ```
SELECT *
FROM product
WHERE category = 'Mobile Phones' AND price > 500
  ```
  - Captura:
<img src="./capturas/5.png"/>

## 6. Seleccionar productos que fueron producidos en un año específico y en un país de origen específico
  - Sentencia:
  ```
SELECT *
FROM product
WHERE year_of_production = 2021 AND country_of_origin = 'USA'
  ```
  - Captura:
<img src="./capturas/6.png"/>

## 7. Seleccionar clientes cuyo nombre completo comience con 'J'.
  - Sentencia:
  ```
SELECT *
FROM client
WHERE fullname LIKE 'J%'
  ```
  - Captura:
<img src="./capturas/7.png"/>

## 8. Seleccionar clientes cuya ciudad contenga la letra 'a'
  - Sentencia:
  ```
SELECT *
FROM client
WHERE fullname LIKE '%a%'
  ```
  - Captura:
<img src="./capturas/8.png"/>
