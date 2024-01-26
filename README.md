SELECT title,description FROM film ORDER BY film_id ASC

SELECT * FROM film AS f WHERE f.length > 60 AND f.length < 70 ORDER BY f.length ASC;

SELECT * FROM film AS f WHERE f.rental_rate = 0.99 AND (f.replacement_cost = 12.99 OR f.replacement_cost = 28.99) ORDER BY film_id ASC

SELECT last_name From customer AS cus where cus.first_name = 'Mary'

SELECT * FROM film AS f WHERE NOT f.length > 50 AND (f.rental_rate = 2.99 OR f.rental_rate = 4.99) ORDER BY film_id ASC
