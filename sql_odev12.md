## sql ödev12

Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1. film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

SELECT count(length) FROM film
WHERE length >
(
SELECT avg(length)
FROM film
);

2. film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

SELECT count(rental_rate) FROM film
WHERE rental_rate =
(
SELECT max(rental_rate)
FROM film
);

3. film tablosunda en düşük rental_rate ve en düşük replacement_cost değerlerine sahip filmleri sıralayınız.

SELECT title FROM film
WHERE 
rental_rate=
(
SELECT min(rental_rate)
FROM film
)
AND
replacement_cost =
(
SELECT min(replacement_cost)
FROM film
);

4. payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

SELECT customer_id, COUNT(customer_id) 
FROM payment
GROUP BY customer_id
ORDER BY COUNT(customer_id) DESC;
