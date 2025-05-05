# MSDS459-Week-5.-Individual-Assignment-2

Part 4 - ParadeDB

ParadeDB is yet another database solution based on Postgres.  The primary advantage of ParadeDB are its search features.  The search functionality of Parade DB utilizes BM25 scoring (Ying, 2023a).  BM25 ranks documents or search results based on the frequency with which search terms appear in documents in relation to the length of the document (Gomede, 2024).  This allows ParadeDB to search the full text of the database.  Additionally, ParadeDB allows fuzzy matches so that misspellings or different forms of a word can still result in a match (Ying, 2023a).  This could be very helpful in the class project.  Projects who’s goals were to allow a user to quickly search for details or information about a corporation could use ParadeDB for potentially faster results.

Another feature of ParadeDB is its strong analytical performance.  ParadeDB utilizes Parquet files to store data in a column-oriented format (ParadeDB, 2025a).  A column-oriented format essentially saves data group in the reverse of the traditional manner.  Whereas a CSV file may save data grouped by the row the data is in, a column-oriented file such as a Parquet file groups data by column (Mock, 2024).  According to ParadeDB, 2025b using this format improves database performance.  Once again, for class projects wishing to have specific questions answered, this feature could be very beneficial.

A third feature of ParadeDB that would be important for this class’s project is the ability to use standard SQL.  ParadeDB uses the function @@@ in the where statement of standard SQL to call its search functions (Ying, 2023b).  This would decrease the learning curve necessary to implement and utilize ParadeDB for the class project. 


References

Gomede, Everton. “Understanding the BM25 Ranking Algorithm.” Medium, March 11, 2024. https://pub.aimind.so/understanding-the-bm25-ranking-algorithm-19f6d45c6ce.

Mock, Emma. “Parquet File Format: The Complete Guide.” Coralogix, August 11, 2024. https://coralogix.com/blog/parquet-file-format/#:~:text=Parquet%20file%20format%20is%20a%20columnar%20storage%20format%2C%20which%20means,separate%20line%20in%20the%20file.

ParadeDB. ParadeDB, 2025a. https://www.paradedb.com/.

ParadeDB. “Welcome to Paradedb.” ParadeDB, 2025b. https://docs.paradedb.com/welcome/introduction.

Ying, Ming. “Introducing ParadeDB.” ParadeDB, August 31, 2023a. https://www.paradedb.com/blog/introducing_paradedb. 

Ying, Ming. “Pg_search: Elastic-Quality Full Text Search Inside Postgres.” ParadeDB Blog, October 1, 2023b. https://www.paradedb.com/blog/introducing_search.
