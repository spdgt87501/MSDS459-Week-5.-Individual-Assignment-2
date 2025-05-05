# MSDS459-Week-5.-Individual-Assignment-2

Part 2 - Gel/EdgeDB

Gel, previously called EdgeDB, is one of the recommended architecture options for this class’s project.  Gel is a relational database based on PostgreSQL intended to solve issues inherent to traditional SQL databases such as object relational impedance (Carnegie Mellon Database Group, 2025).  Relational impedance refers to the conflict that can occur between object-oriented programing often use in application code and the relational model typical of SQL based database management systems (GeeksforGeeks, 2023).

In this review we cover three of the key features of this database.  The first of these is that it is what gel calls “End-to-end type safe” (Gel, 2023).  This means that each object has an associated unique and unchangeable id.  This is similar to tuples in a relational database (Carnegie Mellon Database Group, 2025).  A tuple is essentially the core unchangeable record representing a person, place, thing, or concept in a well-organized relational database.

Second, Gel offers querying and programing code flexibility (Carnegie Mellon Database Group, 2025).  This could be useful for the class project for ease and speed of implementation.  Gel supports both EdgeQL and GraphQL for querying.  There is also support for drivers in various programing languages including Python, Rust, Go. Dart, Dotnet, and JS/TS (Carnegie Mellon Database Group, 2025).  This would give our team flexibility to switch or combine approaches as needed should we get stuck without having to change the database architecture.

Third, deep queries can be written without requiring deep stacks of joins to access the appropriate tables (Carnegie Mellon Database Group, 2025).  This would be extremely helpful for the class project.  A relational database structure for relationships indicating sentiment derived from text-based semantics could become verry complex and convoluted in a relational database if not well thought through and structed.  Having a database architecture more suited for that type of data could ease development and implementation.

One interesting thing to note is that this database architecture (Gel) is built on Postgre (Carnegie Mellon Database Group, 2025), a SQL database query standard.  Although the front end of Gel presents as a more graph-based storage solution, the queries and data are translated into SQL to store and access data (Carnegie Mellon Database Group, 2025).  This would indicate that Gel is more of a pathway to quick development of a properly structured relational SQL database well suited to programming rather than a novel database structure.  This could still be very helpful though.  This is especially true in the case or the class project.  A lot of effort, time, knowledge, and experience goes into properly designing a relational database in an efficient manner for a given implementation.  From the Gel documentation as well as the other articles referenced for this review, it would seem that Gel may allow or team to get to an ideal data structure state easier than trying to map it out ourselves. 


References

Carnegie Mellon Database Group. “Gel.” Database of Databases. Accessed May 3, 2025. https://dbdb.io/db/gel. 

GeeksforGeeks. “Impedance Mismatch in DBMS.” GeeksforGeeks, April 5, 2023. https://www.geeksforgeeks.org/impedance-mismatch-in-dbms/. 
Gel. “Postgres Unchained.” Gel. Accessed May 3, 2025. https://www.geldata.com/.
