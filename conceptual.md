### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a relational database management service
- What is the difference between SQL and PostgreSQL?
SQL is structured querying language, a language to interact with databases, whereas PostgreSQL is an RDBMS
- In `psql`, how do you connect to a database?
/c database_name
- What is the difference between `HAVING` and `WHERE`?
HAVING only works with GROUP BY to filter, WHERE does not 
- What is the difference between an `INNER` and `OUTER` join?
an INNER join only includes rows where the values match on both tables, an OUTER join will include all rows of one table and as well as matching rows from the other table
- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
a LEFT OUTER join includes all rows from the left table and matching tables from the right, a RIGHT OUTER does the opposite
- What is an ORM? What do they do?
ORM stands for object relational mapping. It's a tool to be able to write object oriented programming that is translated to SQL and then queried.
- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
Using AJAX works from the client side and does not require a refreshing of the page, but all the information can be viewed in the developer console through the browser. The server is more secure, whereas the client side is more responsive.
What is CSRF? What is the purpose of the CSRF token?
- What is CSRF? What is the purpose of the CSRF token?
CSRF is a method in which a website can be attacked through HTTP requests, generally targeting state-changing requests. A CSRF token is used in WTForms to authenticate form submissions.
- What is the purpose of `form.hidden_tag()`?
form.hidden_tag() is used to include the CSRF token in the form submission for the processing by the server