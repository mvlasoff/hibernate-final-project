We have relational database MySQL with schema 'world' (country, city, country_language).
We have frequent query which slows down. We have a solution - move all frequently pulled data into 
Redis (in memory storage, key-value type).
And we need not all data but certain set of fields.

Tools and technology used: Java, IDEA Ultimate, MySQL, Workbench, Docker, Redis, RedisInsight.