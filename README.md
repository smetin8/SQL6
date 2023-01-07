# SQL6
Homwork-6-in-kodluyoruz


select avg(rental_rate) from film

select COUNT(title) from film
WHERE title LIKE  ('C%');


select max(length) from film
where rental_rate = 0.99;


select count(distinct(replacement_cost))from film
where length > 150 ;
