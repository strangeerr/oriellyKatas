# Database 

## MySQL as DBMS

Since the entities have relations among each other, choosing a relational database over 
other types such as key-value db, document type db seems logical. 

We prefer using MySql as our DBMS since it is an open source software and is the most popular relational DBMS.
This helps us ensure the developers face the least complexity while working with the database without compromising on the functionalities.
MySQL is an open source engine hence helps with the TCO.

## RDS to host the DBMS

Since entire tech stack sits on AWS, a managed database is easier to maintain as compare to self hosted database.
Over the variety of managed DB services offered by AWS, RDS is most popular and hence easy to use and cost effective solution.
Having a managed database makes our system highly scalable. RDS is highly robust, failsafe and makes future migration(if needed) very easy.


## Pros and Cons

### Pros

- **Easy to use** - Amazon provides both API and CLI access to RDS which makes it 
easier for both developers and database administrators to work with the db.
- **Performance** - RDS provides variety of choices for SSDs, performance classes and workload types.
This allows the developers to suit their requirements yet adapt to user traffic.
- **Scalability** - We need a scalable architecture since the userbase is expected to grow gradually.

## Cons

- **Zero Downtime not Guarenteed** - Amazon does not guarantee zero downtime with RDS which makes it susceptible to
system failures but considering the stability of AWS, this should be rare.