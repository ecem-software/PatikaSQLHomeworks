# patikaSQL-ödev08
## First Question 
(film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.)

SELECT DISTINCT replacement_cost FROM film;
## Second Question
(film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?)

SELECT COUNT(DISTINCT replacement_cost) FROM film;
## Third Question
(film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?)

SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating='G';

## Fourth Question