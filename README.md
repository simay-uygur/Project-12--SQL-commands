# Project-12--SQL-commands
These are assignments given in Patika Java Intermediate course. 

The tasks are 

List the country names in the country table that start with the letter 'A' and end with the letter 'a'.
List the country names in the country table that are at least 6 characters long and end with the letter 'n'.
List the movie titles in the title column of the film table that contain at least 4 'T' characters, regardless of case.
List all columns in the film table where the title starts with the letter 'C', the length is greater than 90, and the rental_rate is 2.99.


The Queries are:

```
-- Task1

SELECT * 
FROM country
WHERE country LIKE 'A%a'; 

-- Task 2
SELECT *
FROM country
WHERE country LIKE '%_____n';

-- Task 3
SELECT title FROM film
WHERE title ILIKE '%t%t%t%t'; 

-- Task 4
SELECT * FROM film
WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99;

```