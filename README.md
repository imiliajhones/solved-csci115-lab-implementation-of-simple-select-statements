Download Link: https://assignmentchef.com/product/solved-csci115-lab-implementation-of-simple-select-statements
<br>
<h1></h1>

This assignment is related to implementation of simple SELECT statements, SELECT statement with GROUP BY and HAVING clauses, SELECT statements that join and antijoin relational tables, nested SELECT statements with set membership operation, and nested SELECT statements with EXISTS/NOT EXISTS clauses.

Connect to Moodle and download the files dbcreate.sql, dbdrop.sql, dbload.sql, dbcount.sql, and dbschema.pdf from Sample database on

Moodle

SQL script dbcreate.sql can be used to create the relational tables of a sample database. SQL script dbdrop.sql can be used to drop the tables of a sample database. SQL script dbload.sql can be used to load data into a sample database. SQL script dbcount.sql can be used to display the total number of rows in each table included in a sample database. Finally, a file dbschema.bmp contains a conceptual schema of a sample database.

Connect to MySQL database server either through command line interface mysql or graphical user interface MySQL Workbench.

When connected, select a database csit115 with a command use csit115.

To create the relational tables of a sample database, process SQL script dbcreate.sql.

To load data into the relational tables created in the previous step process SQL script dbload.sql.

To list the names of relational tables created, use a command show tables.

To list a structure of a relational table &lt;table-name&gt; use a command describe &lt;table-name&gt;.

To list the total number of rows in each relational table process a script dbcount.sql.

Use a pdf viewer to open a file dbschema.pdf with a conceptual schema of the sample database.

no report is expected from the implementation of the actions listed above.

<strong> </strong><strong>        </strong>

<h1>Tasks</h1>

<h2>Task 1</h2>

Download a file solution1.sql and insert into the file the implementations of the following queries as SELECT statements of SQL.

Your implementation must directly follow a comment with a specification of a subtask.

<ul>

 <li>Find the pub names which located at KING ST. or OXFORD ST..</li>

 <li>Find the pub names that serve WHISKY, or VODKA, or COGNAC. Display each pub name only once.</li>

 <li>Find the drinkers who have ordered drinks in January 2020. Display each drinker only once.</li>

 <li>Find the drinkers who have ordered the drink WHITE WINE at LONG JOHN.</li>

</ul>

Display each drinker only once.

<ul>

 <li>Find the drink and the rating of drinks that liked. The results must be displayed in the descending order of the ratings, and for all drinks that have the same rating the results must be displayed in the ascending order of drinks. Display each pair only once.</li>

 <li>Find the drink and the lowest price of each drink served in pubs.</li>

 <li>Find the drinker and the total number of drinks ordered by each drinker in the first three months of 2020.</li>

 <li>find the drink and the total amount of ratings of drinks for each drink. Do not display a drink if it hasn’t been rated.</li>

 <li>Find the pub and the total number of drinks served in each pub that has more than three types of drinks.</li>

 <li>Find the pub, the drink, and the price of pubs that drinks contain a letter E.</li>

</ul>

When ready process a script file solution1.sql with SELECT statements.

To create a report from processing of SELECT statements open a Terminal window and start the command line interface mysql in the following way: <strong>mysql -u csit115 -p -v -c </strong>

Next, process SQL script solution1.sql and save a report in a file solution1.rpt. Note, that when started with the options <strong>-v</strong> and <strong>-c</strong> the command line interface includes both listing of SELECT statements processed and the comments included in the original version of a file solution1.sql.

<h2>Deliverables</h2>

A file solution1.rpt with a report from processing of SQL script solution1.sql. The report must be created with the command line interface mysql, the report MUST NOT include any errors, and the report must list all SQL statements processed and all comments included in the original (downloaded) version of solution1.sql. Marks will be deducted for the missing comments. Submission of a file with a different name and/or different extension and/or different type scores no marks

<h2>Task 2</h2>

Download a file solution2.sql and insert into the file the implementations of the following queries as SELECT statements of SQL.

Your implementation must directly follow a comment with a specification of a subtask.

The queries listed below must be implemented as SELECT statements with JOIN or LEFT / RIGHT OUTER JOIN operation.

<ul>

 <li>Find the distinct drinkers who have ordered drinks at a pub on VICTORIA AVE. in March 2020.</li>

 <li>Find the drinker and total number of times that the drinker rated drinks for all drinkers. Include drinkers who haven’t rated a drink.</li>

 <li>Find the drinker and total amount of money spent on drinks for all drinkers in February 2020. Include drinkers who haven’t ordered a drink in this period.</li>

 <li>Find the drinkers who haven’t ordered any drinks so far.</li>

 <li>Find the drinkers who haven’t order any drinks in April 2020.</li>

 <li>Find the drinker and the drink liked by the drinker but the drinker hasn’t order the drink so far. Sort the drinker and the drink pairs in the ascending order of drinkers and drinks.</li>

</ul>

When ready process a script file solution2.sql with SELECT statements.

To create a report from processing of SELECT statements open a Terminal window and start the command line interface mysql in the following way: <strong>mysql -u csit115 -p -v -c </strong>

Next, process SQL script solution2.sql and save a report in a file solution2.rpt. Note, that when started with the options <strong>-v</strong> and <strong>-c</strong> the command line interface includes both listing of SELECT statements processed and the comments included in the original version of a file solution2.sql.

<h2>Deliverables</h2>

A file solution2.rpt with a report from processing of SQL script solution2.sql. The report must be created with the command line interface mysql, the report MUST NOT include any errors, and the report must list all SQL statements processed and all comments included in the original (downloaded) version of solution2.sql. Marks will be deducted for the missing comments. Submission of a file with a different name and/or different extension and/or different type scores no marks.

Task 3 (3 marks)

Download a file solution3.sql and insert into the file the implementations of the following queries as SELECT statements of SQL.

Your implementation must directly follow a comment with a specification of a subtask.

The queries listed below must be implemented as nested SELECT statements with IN/NOT IN set membership operation.

<ul>

 <li>Find the distinct drinkers who have ordered drinks at a pub on VICTORIA AVE. in March 2020.</li>

 <li>Find the drinker and the drink liked by the drinker but the drinker hasn’t order the drink so far. Sort the drinker and the drink pairs in the ascending order of drinkers and drinks.</li>

</ul>

The queries listed below must be implemented as nested queries with EXISTS/NOT EXISTS clauses.

<ul>

 <li>Find the distinct drinkers who have ordered drinks at a pub on VICTORIA AVE. in March 2020.</li>

 <li>Find the drinker and the drink liked by the drinker but the drinker hasn’t order the drink so far. Sort the drinker and the drink pairs in the ascending order of drinkers and drinks.</li>

</ul>

A query listed below must be implemented with a set algebra operation.

(5) Find the distinct drinkers who like either BEER or RED WINE.

A query listed below must be implemented as a nested query.

(6) Find the distinct drinkers that ordered both VODKA and WHISKY.

When ready process a script file solution3.sql with SELECT statements.

To create a report from processing of SELECT statements open a Terminal window and start the command line interface mysql in the following way: <strong>mysql -u csit115 -p -v -c </strong>

Next, process SQL script solution3.sql and save a report in a file solution3.rpt. Note, that when started with the options <strong>-v</strong> and <strong>-c</strong> the command line interface includes both listing of SELECT statements processed and the comments included in the original version of a file solution3.sql.

<h2>Deliverables</h2>

A file solution3.rpt with a report from processing of SQL script solution3.sql. The report must be created with the command line interface mysql, the report MUST NOT include any errors, and the report must list all SQL statements processed and all comments included in the original (downloaded) version of solution3.sql. Marks will be deducted for the missing comments. Submission of a file with a different name and/or different extension and/or different type scores no marks.




<strong> </strong>