# System-Design-Journey

•
Introduction to System Design
◦
What is System Design?
◦
Why is it popular?
◦
Why understanding system design is important?
◦
Side effects of system design
◦
What to do when designing a system?
◦
How to approach system design
◦
Breaking down problem statements into components
◦
Dissecting components into sub-components
◦
Key considerations for each sub-component
▪
Database and caching
▪
Scaling and Fault Tolerance
▪
Asynchronous processing
▪
Communication
◦
Component properties: Scalable, Fault-Tolerant, Available
•
Databases
◦
Relational Databases
▪
Key properties: Data consistency, durability, integrity
▪
ACID properties: Atomicity, Consistency, Isolation, Durability
▪
Isolation levels: Repeatable Reads, Read Committed, Read Uncommitted, Serializable
▪
When to choose relational databases
◦
Scaling Databases
▪
Vertical scaling
▪
Horizontal scaling: Read replicas
▪
Database sharding
▪
Database partitioning
▪
Advantages and disadvantages of sharding
◦
Non-Relational Databases
▪
Document Databases
▪
Key-Value Stores
▪
Graph Databases
◦
Picking the Right Database
▪
Factors to consider when choosing a database
▪
Database selection based on data, queries and access
•
Caching
◦
What is Caching?
◦
Examples of caching: Google News, Auth Tokens, Live Stream
◦
Eager population of caches
◦
Scaling cache
◦
Content Delivery Networks (CDN)
▪
How CDNs work
◦
Remote cache
◦
Database caching
◦
When to cache data
•
Message Brokers and Streams
◦
Features of message brokers
◦
Message Streams
◦
Kafka
▪
Topics and partitions
▪
Limitations
◦
Realtime Pub/Sub
▪
Advantages and disadvantages
▪
Examples
•
Load Balancers
◦
Job of a load balancer
◦
Load Balancing Algorithms
▪
Round Robin
▪
Weighted Round Robin
▪
Least Connections
▪
Hash based routing
◦
Key Advantages of Load Balancers
▪
Scalability
▪
Availability
•
Circuit Breakers
◦
Preventing cascading failures
◦
Implementation of Circuit Breakers
•
Data Redundancy and Recovery
◦
Data Redundancy
◦
Backup and Restore
◦
Continuous Redundancy
•
Communication Protocols
◦
HTTP
◦
WebSockets
•
Blob Storages and S3
◦
Evolution of File Storage
◦
S3/Blob Storage
◦
Advantages and Disadvantages of S3
◦
When to use S3
•
Bloom Filters
◦
Approximate data structures
◦
How Bloom Filters work
◦
Space efficiency and false positives
◦
Practical application and use cases
•
Consistent Hashing
◦
Hash based ownership
◦
Consistent hashing for data ownership
◦
Scaling up and down using consistent hashing
•
Big Data Processing
◦
Big data processing concepts
◦
Approaches to counting word frequency
◦
Distributed Computing
◦
Spark and Flink
•
System Design Examples
◦
Designing an e-commerce product listing system
◦
Designing a Rate Limiter
◦
Designing a Notification Service
◦
Designing a Realtime Abuse Masker
◦
Designing a Tinder Feed
◦
Designing Twitter Trends
◦
Designing a URL Shortener
◦
Designing PasteBin
◦
Designing a Fraud Detection System
◦
Designing a Recommendation Engine
◦
Designing a Web Crawler
