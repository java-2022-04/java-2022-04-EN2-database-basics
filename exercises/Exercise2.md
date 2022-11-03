## Modeling your own database
1. Create your own EER data model with for a domain you like, or you are familiar with.
   * This can be anything from your business life (Java Topics, Customer Relations / Call-Center Agent / Tech Support / ...) or private life (Travel / Clubs / Animals / ...) Just think of something you can relate to. 
   * Please do NOT reuse the examples we worked with already. (Unless you really liked one, and you want greatly extend it :).
   * Create at least 5 tables. 
   * Make sure you have at least one of each cardinality types. (One-to-Many/Many-Many)
   * Explain the relation between them by using MYSQL - Workbench`s arrows. Find a way to comment on the diagram and state your intentions so I can make sense of them ;). (Sticky note / Textfield).
2. Create a database from your ER diagram. (Save the myDatabase.sql name it how you like).
3. Fill the data with data using INSERT Operations. Add them to the saved myDatabase.sql in a way so that everyone can use your database including the data just by executing that script.
4. Use CRUD Operations to UPDATE/DELETE and READ from your database. Make sure you used some joins there. Put them into an extra crud_mydatabase.sql file.
5. Upload them to your GitHub and send the link or share via github with (erik.hoelzel@posteo.de) 
   * I would like to find the following files on your github (diagram (can be a picture, pdf or saved MYSQL-Workbench-Model) / myDatabase.sql / crud_mydatabase.sql).

6. (Bonus Task 1) Find out what your can understand under the term Transaction in the realm of databases. Discribe and explain it in your own words. Add it as comment to your crud_mydatabase.sql
7. (Bonus Task 2) Use a transaction to perform a couple of CRUD operations on your database and save it right after Bonus Task 1 in to your crud_mydatabase.sql
8. (Bonus Task 3) What other types of a database (besides relational dbs) exist? Look them up and try to find out how they are different to relational databases. How would a CRUD operation look like? (Hint: mongodb, couchdb, casandra, neo4j, ...)
9. (Bonus Task 4) Coming back to relational databases. How does a subquery work? Try to find out how you can use them.
