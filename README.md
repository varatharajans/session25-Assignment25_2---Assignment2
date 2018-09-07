# session25-Assignment25_2---Assignment2

                      Data Analytics SESSION 25: GETTING STARTED WITH RDBMS
                                  Assignment 2
Assignment question received through Email

Data Analytics 
1. Introduction This assignment will help you understand the concepts learnt in the session. 
2. Objective To understand and be able to manipulate SQL queries.
 3. Prerequisites Not applicable. 
4. Associated Data Files Use the Sakila schema, which can be found in following link (to be installed in your local system) http://dev.mysql.com/doc/index-other.html("sakila database") http://dev.mysql.com/doc/sakila/en/sakila.html(for full documentation)
 Requirements For each question, you are required to provide the following: - The SQL query you used - The answers
 - Any assumptions you made
 5. Problem Statement
 1. What are the names of all the countries in the databases which start with the letter "B" (sorted by their names)? 
2. Return the first names (sorted) of all the actors with the last name "berry". 
3. Find all the films whose length is more than 184 (inclusive). Order the results by the length (and for films with the same length order them by their name). Return their title and the length

Answers:-

1. What are the names of all the countries in the databases which start with the letter "B" (sorted by their names)? 
Ans:-
Select country from country where country like ‘B%’ order by country;

2. Return the first names (sorted) of all the actors with the last name "berry". 
Ans:-
Select first_name,last_name from actor where last_name=’berry’ order by first_name;

3. Find all the films whose length is more than 184 (inclusive). Order the results by the length (and for films with the same length order them by their name). Return their title and the length
Ans:-
Select title,length from film where length>=184 order by length,title;
