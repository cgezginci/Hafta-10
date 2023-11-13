* Ödev-1
1. SELECT title , description FROM film;
2. SELECT * FROM film WHERE length > 60 AND length < 75;
3. SELECT * FROM film  WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99);
4. SELECT last_name FROM customer WHERE first_name = 'Mary';
5. SELECT * FROM film WHERE length <= 50 AND (rental_rate != 2.99 AND rental_rate != 4.99);
* Ödev-2
1. SELECT * FROM film WHERE replacement_cost BETWEEN 12.99 AND 16.99;
2. SELECT frist_name , last_ name FROM actor WHERE first_name IN ('Penelope' , 'Nick' , 'Ed');
3. SELECT * FROM film WHERE rental_rate IN (0.99, 2.99, 4.99) AND replacement_cost IN (12.99, 15.99, 28.99);
* Ödev-3
1. SELECT country FROM country WHERE country LIKE 'A%a';
2. SELECT country FROM country WHERE LENGTH(country) >= 6 AND country LIKE '%n';
3. SELECT title FROM film WHERE title ILIKE '%t%t%t%t%';
4. SELECT * FROM film WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99;
