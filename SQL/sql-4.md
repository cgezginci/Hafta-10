* ÖDEV-9
1. SELECT city, country
FROM city
INNER JOIN country ON city.country_id = country.country_id;

2. SELECT payment_id , first_name , last_name 
FROM payment
INNER JOIN customer ON payment.customer_id = customer.customer_id;

3. SELECT rental_id , first_name , last_name 
FROM rental
INNER JOIN customer ON rental.customer_id = customer.customer_id;

* ÖDEV-10
1. SELECT city, country 
FROM city 
LEFT JOIN country ON city.country_id = country.country_id;

2. SELECT payment_id , first_name , last_name 
FROM payment
RIGHT JOIN customer ON payment.customer_id = customer.customer_id;

3. SELECT rental_id , first_name , last_name 
FROM rental
FULL JOIN customer ON rental.customer_id = customer.customer_id;

* ÖDEV-11
1. (SELECT first_name 
 FROM actor)
 UNION ALL
 (SELECT first_name
 FROM customer);

2. (SELECT first_name 
 FROM actor)
 INTERSECT
 (SELECT first_name
 FROM customer);

3. (SELECT first_name 
 FROM actor)
 EXCEPT
 (SELECT first_name
 FROM customer);

4. SELECT first_name FROM actor
UNION ALL
SELECT first_name FROM customer;

SELECT first_name FROM actor
INTERSECT ALL
SELECT first_name FROM customer;

SELECT first_name FROM actor
EXCEPT ALL
SELECT first_name FROM customer;
