## The following tasks are used with the world database
(you can Download it here: )

1. Select all the information from https://github.com/kakakakakku/mysql-world-database-dockerfiles/blob/master/5.5/world.sql.gzall the countries in the country table.
2. Get all Names of all the countries.
   
   ```
   SELECT Name FROM country
3. Get all Names and continents from all countries.
   ```
   SELECT Name, Continent FROM country
4. Get all the Information about your home country (filtering).
   ```
   SELECT *
   FROM country
   WHERE Name="Germany"
5. Get names of countries in Europe and in Africa.
   ```SELECT Name
   FROM country
   WHERE Continent="Europe"
   

6. How many countries are there in the world?

7. How many countries are there in Europe?

8. How can I rename the column header for the result? (use an alias).

9. What is the total population of Europe?

10. What is the average population by country in Europe?

11. What is the smallest population of a country in the world?

12. What is the biggest population of a country in the world?


13. Display the number of countries for each continent.

14. Display the total population of each continent.

15. Show only the Regions which have more than 15 countries.

16. Show only the Regions in Europe which have more than 5 countries.
17. How many countries are there in the world that have a population smaller than 10 million and that have gained independent before 1900?
18. Same thing, but showing the names and the population of these countries, ordered by population (most populous first).
19. Display all countries which have "Arab" in their names.
20. Countries from Asia that have a population bigger than 100 million or a lifeexpectancy smaller than 65.



