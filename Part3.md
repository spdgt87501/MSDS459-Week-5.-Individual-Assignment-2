# MSDS459-Week-5.-Individual-Assignment-2

Part 3 - Timescale

Similar to Gel, Timescale is also based on PostgreSQL.  However, Timescale is geared toward time series data (Oles, 2022).  Some of the other key features of Timescale are SQL compatibility and compression (Timescale, 2024).

In the project for this class, we will likely be working with time series data.  Utilizing a database optimized for time series data would be very helpful in that regard.  However, similarly to Gel, this appears to not be a novel database solution.  Rather, Timescale is based on PostgreSQL.  There would be an advantage however in this implementation rather than Gel as Timescale would allow us to use our existing SQL knowledge to query the dataset.  According to Timescale (2024), the Timescale db is compatible with the standard PostgreSQL interface.  This would decrease the learning curve compared to Gel as utilizing Gel would require learning a new query language.

The compression feature would also be very useful.  As students, we have limited access to database storage and there is some possibility we may have to pass copies of the database over the internet through file transfers or Github.  Automatic compression could make this easier.

One of the drawbacks of this database would be attempting to store sentiment data.  Although the results of the sentiment analysis could in theory be stored in a database as described by Timescale (2024), the database may struggle to store the entities from the analyzed text and the relationships between them as compared to a graph knowledge base.  On the other hand, if we simply intend on asking our database whether the future for a particular stock looks promising, it may not be necessary to store those relationships.


References

Oles, Bart. “An Introduction to Timescaledb.” Severalnines, June 7, 2022. https://severalnines.com/blog/introduction-timescaledb/.

Timescale. “What Are Open-Source Time-Series Databases-Understanding Your Options.” Timescale, May 21, 2024. https://www.timescale.com/learn/what-are-open-source-time-series-databases-understanding-your-options. 
