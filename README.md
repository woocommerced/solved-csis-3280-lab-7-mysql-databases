Download Link: https://assignmentchef.com/product/solved-csis-3280-lab-7-mysql-databases
<br>
Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard</li>

 <li>Extract it</li>

 <li>Fill in the relevant code to create the solution and meet the requirements</li>

</ol>

Solution

Create a .sql file that does the following:

You must drop your database if it exists

You must create the appropriate SQL file that specifies 3 tables for a web application (that you will make up) your tables must have your naming convention at the end of the table for example (Lab07_SWh-56789.sql).

Your solution will include the Lab07_SWh_56789.sql file that will be run via the command line MySQL utility.

You must provide the proper command to run the mysql file and have tested its creation by entering it either into the MySQL command line.

Requirements:

<ol>

 <li>Create three tables representing three entities in mysql. (ex: Student_SWh_56789, Course_SWh_56789, Enrollment_SWh_56789)</li>

 <li>Be sure that you append the naming convention to your tables</li>

 <li>You cannot use the example above.</li>

 <li>You must CREATE a database to populate the tables and records specified below you must drop the database if it already exists. Be sure to stick to the naming connection for example: Database_SWh_56789 where Database is the name of your database.</li>

 <li>Your tables must enforce proper referential integrity between each other (they must be related and have the primary and foreign key constraints – What this means is that two of your tables must have at least one foreign key reference).</li>

 <li>Your script in addition to creating the database and tables must INSERT 5 records into each table.</li>

 <li>You must then demonstrate CRUD operations on your database (see the template file)

  <ol>

   <li>Create (this will be coverd by inserting at least 5 rows per table)</li>

   <li>An UPDATE Query that updates one of the values in your table in your strong entity.</li>

   <li>Read ( A SELECT query that references all of your tables and joins by primary and foreign key). This query should verify that your UPDATE query worked.</li>

   <li>Delete ( A DELETE query that that removes one of the records in your strong entity)</li>

  </ol></li>

 <li>You may assume that the root user will execute the mysql command with no password and that the mysql command is set in the PATH on the machine executing the code.</li>

</ol>

Note: Please refer to the attached sample .sql file.

1 / 1