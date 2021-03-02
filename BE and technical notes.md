# VueJS 
- [Vue mastery tutorial](https://www.vuemastery.com/courses)
- [tutorial with node](https://www.youtube.com/watch?v=1n-Uk1QlNd4&t=822s&ab_channel=TylerPotts)

# JWT

AXIOS => Promise based HTTP client for the browser and node.js  

write promises into axios > Fetch from Mongo (with monk) into Vue app (upgrade to Vue 3) > write into Vue variables on webpage, run scripts that works with variables updated with Vue 

- [JWT authentication](https://blog.nextzy.me/implementing-json-web-token-jwt-to-secure-your-app-c8e1bd6f6a29?gi=fd0c3294c588)
- [JWT decoder](https://jwt.io/ )
- [JWT tutorial](https://www.youtube.com/watch?t=4265&v=2jqok-WgelI&feature=youtu.be&ab_channel=DevEd)
 
# MongoDB

- [Mongo vs SQL](https://www.knowi.com/blog/mongodb-vs-sql/) 
- [some tutorial](https://www.youtube.com/watch?v=rPqRyYJmx2g&ab_channel=MongoDB )

## Inter Company DB
    Collections:
        users {id, name, email, password, database(connection string for user's data DB connection), date}

## User DB
    Collections:
        data (posts, products)

 
# GraphQL

## Graph QL vs REST 
- [GraphQL vs REST](https://www.youtube.com/watch?v=T571423fC68&feature=emb_logo&ab_channel=Prisma)
- [GraphQL usability](https://www.youtube.com/watch?v=zMa8rfXI6MM&feature=emb_logo&ab_channel=Prisma)
- [GraphQL cons](https://www.root.cz/clanky/tri-nastrahy-graphql-na-co-si-dat-pozor/)
- [GraphQL tutorial](https://www.youtube.com/watch?v=ZQL7tL2S0oQ&ab_channel=WebDevSimplified) 

The architecture of SQL databases like MySQL is governed by the principles of ACID property. 
ACID stands for Atomicity, Consistency, Isolation, and Durability. These properties focus on the consistency and reliability of the transaction done in the database.  
MongoDB is built on the principles of CAP Theorem which focuses on Consistency, Availability, and Partition. Unlike the ACID properties of SQL databases, CAP theorem focuses on availability of data in the case of MongoDB. 

### Graph QL 

U Graph QL API při requestu stačí specifikovat endpointy s kterých čerpáme a provést je všechny v jednom requestu 
Má definované své schéma => při práci na backendu a front endu můžou oba týmy pracovat zvlášť 
Low level performance monitoring 

### REST API 

U REST API se musí každý request provést zvlášť 

## Scalability 

MySQL database or the SQL databases, in general, can be scaled only vertically by increasing memory size, disk space or computing power of the server. Vertical scaling can be expensive with costs growing rapidly for large databases with high query volume. 
NoSQL databases like MongoDB support horizontal scaling, also known as sharding. In this case, instead of increasing the server configuration a new server is added for the purpose of scalability. This approach is usually less expensive because a cluster of low-cost commodity hardware can together meet the requirements to support high query volume in a cost-effective manner. 


# APPS

- [blog app](https://www.youtube.com/watch?v=aKCdThHAIwI&ab_channel=TylerPotts)
- [Authentication App](https://www.youtube.com/watch?v=2jqok-WgelI&ab_channel=DevEd)
- [Strapi headless CMS](https://www.youtube.com/watch?v=6FnwAbd2SDY&ab_channel=TraversyMedia)