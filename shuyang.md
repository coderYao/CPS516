Data Platforms

Shuyang Yao sy86

-   General Purpose:

System

Pros

Cons

-   Lotus Notes:

<!-- -->

-   Better security control than its competitor
-   Supports more platforms than its competitor
-   Support hardware as well as software virtualization

\

-   It’s not very flexible in term of using because it’s a little bit
    too secure

\

-   Actian Versant

<!-- -->

-   It’s Object Oriented! It’s simple and straight forward to build
    complex data models which are hierarchical.
-   No need to use a query language
-   No primary keys
-   Make developer’s life easier by allowing database to process complex
    objects models without writing mappings.
-   Allows you to change database schema while your service is on-line.
-   Good Scalability
-   Full support for transactions, logging and locking.

<!-- -->

-   Lack of solid theoretical basis.
-   API is language dependent
-   Schema change may need a system-wide compile(not in Versant’s case)

<!-- -->

-   InterSystems Cache

<!-- -->

-   A fully persistent database with high throughput even comparing with
    in-memory database
-   Good scalability and performance when hosted on inexpensive
    machines.

<!-- -->

-   

<!-- -->

-   McObject:

<!-- -->

-   Memory data base with good scalability.
-   ACID-Compliant
-   It’s Object Oriented! It’s simple and straight forward to build
    complex data models which are hierarchical.
-   No need to use a query language
-   No primary keys
-   Lack of solid theoretical basis.
-   API is language dependent
-   Schema change may need a system-wide compile(not in Versant’s case)

<!-- -->

-   ObjectStore:

<!-- -->

-   It’s Object Oriented! It’s simple and straight forward to build
    complex data models which are hierarchical.
-   No need to use a query language
-   No primary keys
-   Lack of solid theoretical basis.
-   API is language dependent
-   Schema change may need a system-wide compile(not in Versant’s case)

<!-- -->

-   WakandaDB:

<!-- -->

-   Everything(schema, server-side processing, querying) can all be done
    in JavaScript
-   Open Source
-   Open Source and not mature

<!-- -->

-   IBM IMS:

<!-- -->

-   It’s a full function database
-   Optimized for high transection rates.
-   High Availability
-   -   Developers may need to write more code.

<!-- -->

-   Adabas

<!-- -->

-   Is able to work close with previously existing database system
-   No access control in term of native network encryption

<!-- -->

-   UniVerse:

<!-- -->

-   Multi-valued database
-   High Availability
-   Good Scalability
-   Intuitive database design
-   High Performance
-   Does not constrain by 1st Normal Form
-   The fact that it does not adhere to 1FN can be abused

<!-- -->

-   UniData

<!-- -->

-   Secure
-   Similar to UniVerse
-   Similar to UniVerse

<!-- -->

-   Documentation xDB

<!-- -->

-   XML-based Database
-   Allows the schema to be easily modified.
-   Flexible schema compared to relational database
-   EMC\^2’s disaster-recovery options
-   Not ACID-compliant

<!-- -->

-   Tamino XML Server

<!-- -->

-   XML-based Database advantage described in Documentation xDB
-   Not ACID-compliant like many other document based database

<!-- -->

-   Ipedo XML Database

<!-- -->

-   XML-based Database advantage described in Documentation xDB
-   Not ACID-compliant like many other document based database

<!-- -->

-   OrientDB:

<!-- -->

-   Document oriented database with graph database feature
-   Open Source
-   Can be queried using SQL
-   AICD
-   Not Mature, API changes over time.

<!-- -->

-   SQLite

<!-- -->

-   Easy to use<span class="Apple-converted-space"> </span>
-   Consumes less resources
-   Doesn’t scale very well

<!-- -->

-   Firebird

<!-- -->

-   Free open source<span class="Apple-converted-space"> </span>
-   Relational database
-   Well established and tested based on solid theoretical foundation
-   ACID
-   SQL as access language
-   Join!
-   Large Throughput
-   Not very scalable in term of horizontal scaling
-   Difficult to model complex data model because it is table based

<!-- -->

-   SAP Sybase ASE:

<!-- -->

-   Relational database advantages as described in Firebird
-   Relational database disadvantages described in Firebird

<!-- -->

-   SAP SQL Anywhere

<!-- -->

-   Relational database advantages as described in Firebird
-   Embed: consume less resources.
-   -   Relational database disadvantages described in Firebird

<!-- -->

-   Postgres-XL:<span class="Apple-converted-space"> </span>

<!-- -->

-   ACID
-   Open Source
-   Cluster-wide Consistency
-   Secure
-   SQL
-   Horizontal scaling
-   Rich feature set.
-   Too complex for simple stuff

<!-- -->

-   Pecona

<!-- -->

-   Same as MySql
-   Same as MySql

<!-- -->

-   MySQL

<!-- -->

-   Relational database advantages as described in Firebird

\

-   Not very Scalable

<!-- -->

-   Oracle Database

<!-- -->

-   Relational database advantages as described in Firebird
-   Commercial
-   Price
-   Relational database disadvantages as described in Firebird

<!-- -->

-   IBM DB2

<!-- -->

-   Relational database advantages as described in Firebird
-   Commercial
-   Price
-   Relational database disadvantages as described in Firebird

\

-   Specialist analytic

System

Pros

Cons

-   Google BigQuery

<!-- -->

-   Allows users to use SQL-like queries to query massive datasets
-   Rest API
-   Google’s infrastructure makes the operation fast and economic.
-   Makes ad-hoc and trial-and-error interactive query on large dataset
    possible
-   Not able to do complex data processing.
-   You can’t update your data, only appending is allowed.
-   No large Join.

<!-- -->

-   InfluxDB

<!-- -->

-   Open Source
-   SQL-like language
-   Native HTTP API
-   Can process big amount of data.
-   Focus on time series.
-   Maturity

<!-- -->

-   1010data <span class="Apple-converted-space"> </span>

<!-- -->

-   Interactive analytical service.
-   A rich set of analytic functions are integrated.
-   Suit for very large data set.
-   Decent performance with high scalability.
-   Price.
-   Should support more complex database operations.

<!-- -->

-   BitYota:

<!-- -->

-   Data warehouse as a service
-   SQL
-   Real time data analysis
-   

<!-- -->

-   AWS RedShift

<!-- -->

-   Scaling is easy
-   You can use SQL to query
-   Can work seamlessly with other AWS services
-   Because RedShift does not maintain the uniqueness of data,
    programmer are responsible for their data integrity.

<!-- -->

-   SpaceCurve:

<!-- -->

-   Focus mainly on spatial data.
-   Good at real-time location analysis
-   Query: Some patent-pending strategies that optimize quires
-   View: Algorithm that make updating views more efficient
-   Supports serializable concurrent transection

<!-- -->

-   LogicBlox:<span class="Apple-converted-space"> </span>

<!-- -->

-   Query: Some patent-pending strategies that optimize quires
-   View: Algorithm that make updating views more efficient
-   Supports serializable concurrent transection
-   

<!-- -->

-   MonetDB:<span class="Apple-converted-space"> </span>

<!-- -->

-   Column oriented store:
-   Good at OLAP scenario
-   Higly Compressed
-   Increased disk seek time
-   Insertion costs more

<!-- -->

-   Pivotal GreenPlum:

<!-- -->

-   Supports both row and column-oriented storage
-   Highly scalable
-   Column oriented store disadvantage
-   Increased disk seek time
-   Insertion costs more
-   

<!-- -->

-   HP Verica

<!-- -->

-   Column Oriented
-   Highly compressed
-   Good at log parsing
-   Immaturity
-   Increased disk seek time
-   Insertion costs more

<!-- -->

-   SAP Sybase IQ

<!-- -->

-   Column Oriented
-   Increased disk seek time
-   Insertion costs more

<!-- -->

-   ParStream:

<!-- -->

-   Real time analysis
-   Focus on IOT(Internet of Things) data

\

-   IBM InfoSphere

<!-- -->

-   Real-time analytic platform
-   Merge diverse data
-   Rapid deployment analysis
-   Column-oriented database
-   In memory
-   Highly compressed

<!-- -->

-   Kx Systems:

<!-- -->

-   Column store database advantages described in MonetDB
-   Column store database disadvantages described in MonetDB

<!-- -->

-   LucidDB:

\

-   Column store database advantages described in MonetDB
-   Open Source
-   Bitmap indexing
-   Hash join/aggregation
-   Multiversioning
-   Column store database disadvantages described in MonetDB

<!-- -->

-   Kognitio:

<!-- -->

-   In memory
-   Support SQL
-   integrated with HADOOP
-   

<!-- -->

-   Actian Vector

<!-- -->

-   A high performance analytic frame built on Hadoop
-   Developer can use SQL to interact with the system
-   

<!-- -->

-   MetaMarkets Druid:

<!-- -->

-   A distributed real-time data store
-   Real time ingestion
-   Column-oriented storage’s advantage
-   Bitmap indexing
-   Fault tolerance
-   Column-oriented storage’s disadvantage

<!-- -->

-   Teradata

<!-- -->

-   A decent data warehouse system
-   Developers can choose to store the data either based on row or
    column
-   Price

<!-- -->

-   SQream

<!-- -->

-   Scalable SQL data base
-   GPU based database brings high parallel processing ability
-   Column oriented storage advantages<span
    class="Apple-converted-space"> </span>
-   Column oriented storage disadvantages

<!-- -->

-   RainStor

<!-- -->

-   Can work with different data types
-   

<!-- -->

-   HPCC

<!-- -->

-   Introduced a new programming language: ECL
-   It is more complex than a key-value pair storage.
-   High availability, scalability and consistent
-   Still growing.

<!-- -->

-   Teradata Aster:

<!-- -->

-   Allows users to write map reduce code that manipulate relational
    data base data.
-   Graph analytics engine
-   Support massive parallel processing
-   

<!-- -->

-   SciDB

<!-- -->

-   Array data model
-   Supports complex mathematic processing on the arrays
-   Can model uncertainty
-   Focus mainly on Mathematic operations

<!-- -->

-   Hadapt

<!-- -->

-   Brings SQL to Hadoop, which allows users to write SQL to query on
    massive amount of data
-   Uses a hybrid storage engine which stores structured data in a
    traditional relational database while unstructured data in HDFS.
-   No transections

<!-- -->

-   JethroData

<!-- -->

-   Like Hadapt, it builds a layer on top of Hadoop that allows user to
    write SQL on Hadoop
-   Unique index strategy
-   Scalability that comes with HDFS
-   No transections

<!-- -->

-   CitusDB:<span class="Apple-converted-space"> </span>

<!-- -->

-   SQL on Hadoop
-   Also suppor semi-structured data
-   Optimized specially for time-series data.
-   No transections

<!-- -->

-   Impala:

<!-- -->

-   SQL on Hadoop
-   It’s supported by Cloudera
-   No transections
-   Data need to be stored in a specific data format

<!-- -->

-   IBM Big SQL

<!-- -->

-   SQL on Hadoop
-   No transections

<!-- -->

-   Presto

<!-- -->

-   Sql on Hadoop
-   Can query data from different source and bring them together
-   No transections

<!-- -->

-   Apache Drill:

<!-- -->

-   SQL on Hadoop
-   Apache license
-   Can work with semi-structured or nested data
-   Low latency
-   No transections

<!-- -->

-   -   Apache Hive:

<!-- -->

-   Data warehouse built on Hadoop
-   Use a SQL like language
-   Bitmap index
-   Supports different storage type.
-   Data are compressed
-   -   No update and delete operation
-   No access control
-   The overhead brought by Map Reduce make it a little bit slow

<!-- -->

-   -   Apache Tajo

<!-- -->

-   Fully distributed SQL
-   Various query optimization<span
    class="Apple-converted-space"> </span>
-   Supports ANSI/ISO SQL
-   Has a shell<span class="Apple-converted-space"> </span>
-   No transections

\

-   Big Tables

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   Google Cloud         | -   No schema is needed, | -   No database layer    |
|     Datastore            |     Aims at storing      |     caching              |
|                          |     non-relational data  | -   No Join              |
|                          | -   Write scale and read | -   Filter results using |
|                          |     scale.               |     a subquery is not    |
|                          | -   Supports             |     supported            |
|                          |     transection<span     |                          |
|                          |     class="Apple-convert |                          |
|                          | ed-space"> </span>       |                          |
+--------------------------+--------------------------+--------------------------+
| -   Google App Engine    | -   Key-value pair store | -   Does not support     |
|     Datastore            |     makes it more        |     ACID transactions    |
|                          |     flexible             | -   No join              |
+--------------------------+--------------------------+--------------------------+
| -   Cassandra.io         | -   Linear               | -   No Join              |
|                          |     scalability(All      | -   Does not support     |
|                          |     nodes are identical) |     ACID                 |
|                          | -   Fault-tolerance on   |                          |
|                          |     inexpensive hardware |                          |
|                          | -   The language it      |                          |
|                          |     uses(CQL3) is very   |                          |
|                          |     similar to SQL       |                          |
|                          | -   Constant-time        |                          |
|                          |     writes<span          |                          |
|                          |     class="Apple-convert |                          |
|                          | ed-space"> </span>       |                          |
|                          | -   Integrated with      |                          |
|                          |     Hadoop               |                          |
+--------------------------+--------------------------+--------------------------+
| -   Accumulo             | -   Wode Column Store DB | -                        |
|                          |     similar to Cassandra |                          |
|                          |     and HBase            |                          |
|                          | -   Better               |                          |
|                          |     Performance(can scan |                          |
|                          |     800k entries per     |                          |
|                          |     second per node)     |                          |
|                          |     compare to HBase     |                          |
|                          | -   Provides cell-level  |                          |
|                          |     security             |                          |
+--------------------------+--------------------------+--------------------------+
| -   Hbase                | -   Works hand in hand   | -   No strict ACID       |
|                          |     with Hadoop          | -   Because of its       |
|                          | -   Specially optimized  |     master and slave     |
|                          |     for real time        |     architecture, Hbase  |
|                          |     analysis             |     has the problem of   |
|                          | -   Also linear          |     single point failure |
|                          |     scalability          | -   No join              |
|                          | -   Consistent reads and |                          |
|                          |     writes               |                          |
|                          | -   Row level Atomic     |                          |
+--------------------------+--------------------------+--------------------------+
| -   HyperTable           | -   Implements using c++ | -                        |
|                          | -   Runs on haddop       |                          |
|                          | -   SQL like language    |                          |
|                          | -   Faster and smaller   |                          |
|                          |     than HBase           |                          |
+--------------------------+--------------------------+--------------------------+
| -   DataStax Enterprise  | -   Built on Cassandra   | -   Similar to Cassandra |
|                          | -   Comercial            |                          |
|                          | -   Similar to Cassandra |                          |
+--------------------------+--------------------------+--------------------------+

-   Key value stores

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   AWS DynamoDB         | -   Supports both        | -   Consume more         |
|                          |     document and         |     resource because its |
|                          |     key-value data       |     stronger Consistent  |
|                          | -   Low latency          |     constrain            |
|                          | -   Highly scalable      | -   No join              |
|                          | -   Highly available     | -   No support for       |
|                          | -   Strong consistency   |     transection          |
|                          |     on read              | -   No ACID              |
|                          | -   Supports atomic      |                          |
|                          |     counters             |                          |
|                          | -   Secure: find access  |                          |
|                          |     control              |                          |
+--------------------------+--------------------------+--------------------------+
| -   AWS SimpleDB         | -   Fit for smaller      | -   Table cannot grow    |
|                          |     workloads            |     over 10 GB           |
|                          | -   Automatically index  | -   Not as scalable as   |
|                          |     all things           |     DynamoDB             |
|                          |                          | -   No joins             |
+--------------------------+--------------------------+--------------------------+
| -   MagnetoDB            | -   A key-value storage  | -   No join              |
|                          |     for open stack       | -   No support for       |
|                          | -   Highly scalable      |     transection          |
|                          | -   Supports both        | -   No ACID              |
|                          |     eventual and strong  |                          |
|                          |     consistency reads    |                          |
|                          | -   Fault tolerance      |                          |
+--------------------------+--------------------------+--------------------------+
| -   Redis Cloud          | -   In memory            | -   No ACID              |
|                          |     non-relational       |                          |
|                          |     database             |                          |
|                          | -   Scale out seamlessly |                          |
|                          | -   Zero Down time       |                          |
|                          | -   Secure               |                          |
+--------------------------+--------------------------+--------------------------+
| -   Redis Labs           | -   Similar to Redis     | -   Similar to Redis     |
|                          |     Cloud                |     Cloud                |
+--------------------------+--------------------------+--------------------------+
| -   AWS ElastiCashe      | -   You can choose from  | -   Disadvantages are    |
|                          |     two in memory cache  |     similar to Redis     |
|                          |     options: Redos or    |                          |
|                          |     Memcached            |                          |
|                          | -   The advantages are   |                          |
|                          |     similar to those two |                          |
+--------------------------+--------------------------+--------------------------+
| -   Redis-to-go          | -   A redis management   | -   Redis’ disadvatages  |
|                          |     tool                 |                          |
+--------------------------+--------------------------+--------------------------+
| -   RedisGreen           | -   A redis hosting      | -   Redis’ disadvatages  |
|                          |     service              |                          |
+--------------------------+--------------------------+--------------------------+
| -   ObjectRocket Redis   | -   A redis hosting      | -   Redis’ disadvatages  |
|                          |     service              |                          |
+--------------------------+--------------------------+--------------------------+
| -   HyperDex             | -   Key-value storage    | -   No Join              |
|                          | -   Strong consistency   |                          |
|                          | -   Fault tolarence      |                          |
|                          | -   ACID                 |                          |
+--------------------------+--------------------------+--------------------------+
| -   LevelDB              | -   Key-value            | -   No indexes           |
|                          | -   Comparison function  | -   It only allows one   |
|                          |     can be customized    |     process to access    |
|                          | -   Compressed           |     the database at a    |
|                          |                          |     time                 |
+--------------------------+--------------------------+--------------------------+
| -   BerkeleyDB           | -   Provides building    | -                        |
|                          |     blocks that can help |                          |
|                          |     you develop your own |                          |
|                          |     data management      |                          |
|                          |     solution             |                          |
+--------------------------+--------------------------+--------------------------+
| -   Oracle NoSQL         | -   Key value storage    | -   No Join              |
|                          |     with secondary       |                          |
|                          |     indexes              |                          |
|                          | -   ACID<span            |                          |
|                          |     class="Apple-convert |                          |
|                          | ed-space"> </span>       |                          |
|                          | -   Secure               |                          |
+--------------------------+--------------------------+--------------------------+
| -   Voldemort            | -                        | -                        |
+--------------------------+--------------------------+--------------------------+
| -   Redis                | -   In memory            | -   No ACID              |
|                          |     non-relational       |                          |
|                          |     database             |                          |
|                          | -   Scale out seamlessly |                          |
|                          | -   Zero Down time       |                          |
|                          | -   Secure               |                          |
+--------------------------+--------------------------+--------------------------+
| -   Couchbase            | -   Key-value            | -   No join              |
|                          | -   Document(Json)       | -   No transection       |
|                          | -                        |                          |
+--------------------------+--------------------------+--------------------------+
| -   FatDB                | -   Tight intergration   | -                        |
|                          |     with SQL Server      |                          |
+--------------------------+--------------------------+--------------------------+
| -   Riak                 | -   Buck key together    | -   ACID                 |
|                          | -   Strongly consistent  | -   Join                 |
|                          | -   Non-key based query  |                          |
|                          |     use map reduce to    |                          |
|                          |     get the answer       |                          |
+--------------------------+--------------------------+--------------------------+
| -   ArangoDB             | -   Multi-model          | -                        |
|                          |     database:S upport    |                          |
|                          |     documents, graphs    |                          |
|                          |     and key-values data  |                          |
|                          |     model                |                          |
|                          | -   SQL-like             |                          |
|                          | -   Joins like operation |                          |
|                          | -   Transections         |                          |
+--------------------------+--------------------------+--------------------------+
| -   Aerospike            | -   Handle real time     | -   Join                 |
|                          |     data                 |                          |
|                          | -   ACID                 |                          |
|                          | -   Flash as storage     |                          |
|                          | -   Mainly key-value     |                          |
|                          | -   Map reduce           |                          |
+--------------------------+--------------------------+--------------------------+

-   Hadoop

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   GridGain             | -   In Memory data faric | -   history              |
|                          | -   Can act as a cache   |                          |
|                          |     layer to accelerate  |                          |
|                          |     Hadoop               |                          |
|                          | -   Realtime streaming   |                          |
|                          | -   Linearly scale out   |                          |
|                          | -   ACID transection     |                          |
+--------------------------+--------------------------+--------------------------+
| -   ScaleOut Software    | -   In memory storage    | -                        |
+--------------------------+--------------------------+--------------------------+
| -   Pivoutal GenFire XD  | -   Helps SQl to scale   | -   Transection and ACID |
|                          |     out using Hadoop     |                          |
|                          | -   High availability    |                          |
|                          | -   In memory            |                          |
|                          | -                        |                          |
+--------------------------+--------------------------+--------------------------+
| -   Sqrrl Enterprise     | -   Based on Apache      | -   disadvantages        |
|                          |     Accumulo             |     similar to Accumulo  |
|                          | -   Advantages similar   |                          |
|                          |     to Accumulo          |                          |
+--------------------------+--------------------------+--------------------------+
| -   LucidWorks Big Data  | -   A big data platform  | -                        |
|                          |     brings together      |                          |
|                          |     Hadoop solr and      |                          |
|                          |     etc.<span            |                          |
|                          |     class="Apple-convert |                          |
|                          | ed-space"> </span>       |                          |
+--------------------------+--------------------------+--------------------------+
| -   Trafodion            | -   SQL on Hbase         | -                        |
|                          | -   ACID Transection     |                          |
|                          | -   scaling              |                          |
+--------------------------+--------------------------+--------------------------+
| -   Splice Machine       | -   Full function SQL on | -                        |
|                          |     Hadoop               |                          |
|                          | -   Scale out            |                          |
|                          | -   Transection          |                          |
|                          | -   High concurrency     |                          |
|                          | -   Real time updates    |                          |
+--------------------------+--------------------------+--------------------------+
| -   Apache Tajo -        | -   Already described in | -   Already described in |
|     Pivaotal HD          |     Specialist analytic  |     Specialist analytic  |
+--------------------------+--------------------------+--------------------------+

\

-   Appliance

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   Oracle Big Data      | -   Cloudera Enterprise  | -   Integrated solution  |
|     Appliance            |     Technology software  | -   price                |
|                          | -   Oracle NoSQL         |                          |
|                          |     database             |                          |
|                          | -   Integrated solution  |                          |
+--------------------------+--------------------------+--------------------------+
| -   Oracle Exalytics     | -   In memory integrated | -   Integrated solution  |
|                          |     solution             | -   price                |
+--------------------------+--------------------------+--------------------------+
| -   Microsoft SQL Server | -   Integrated solution  | -   Integrated solution  |
|     PDW                  |                          |                          |
+--------------------------+--------------------------+--------------------------+
| -   SAP HANA             | -   In memory            | -   Increased disk seek  |
|                          | -   Column oriented<span |     time                 |
|                          |     class="Apple-convert | -   Insertion costs more |
|                          | ed-space"> </span>       |                          |
|                          | -   Relational databse   |                          |
+--------------------------+--------------------------+--------------------------+
| -   IBM Pure Data        | -   Integrated solution  | -   Integrated solution  |
+--------------------------+--------------------------+--------------------------+
| -   Oracle Exadata       | -   Integrated solution  | -   Integrated solution  |
|                          | -   flash                |                          |
+--------------------------+--------------------------+--------------------------+

-   Graph

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   infiniteGraph        | -   Distributed graph    | -   Does not support map |
|                          |     database             |     reduce               |
|                          | -   graph specific       | -   Does not support     |
|                          |     queries              |     data compression     |
|                          | -   Policy-driven        | -   Eventual consistency |
|                          |     consistent           |                          |
|                          | -   Data visualization   |                          |
|                          |     is integrated        |                          |
+--------------------------+--------------------------+--------------------------+
| -   HypergraphDB         | -   Graph oriented<span  | -   Does not support map |
|                          |     class="Apple-convert |     reduce               |
|                          | ed-space"> </span>       |                          |
|                          | -   graph specific       |                          |
|                          |     queries              |                          |
|                          | -   Transection          |                          |
+--------------------------+--------------------------+--------------------------+
| -   Allegrograph         | -   ACID transection     | -   Does not support map |
|                          | -   Automatic indexing   |     reduce               |
|                          | -   SOLR and MongoDb are |                          |
|                          |     integreted           |                          |
|                          | -   Secure               |                          |
|                          | -   Sharding             |                          |
+--------------------------+--------------------------+--------------------------+
| -   Giraph               | -   Data analysis tool   | -                        |
|                          |     on graph data        |                          |
|                          | -   Apache               |                          |
|                          | -   Used by Facebook     |                          |
|                          | -   Runs as map reduce   |                          |
|                          |     jobs                 |                          |
+--------------------------+--------------------------+--------------------------+
| -   SPARQLBASE           | -   Graph databse        | -                        |
|                          | -   In memory            |                          |
|                          | -   Uses HDFC to store   |                          |
|                          |     data                 |                          |
+--------------------------+--------------------------+--------------------------+
| -   Trinity              | -   Embed or distributed | -   Not mature           |
|                          |     graph storage        |                          |
|                          | -   In memory            |                          |
|                          | -   Data compressed      |                          |
+--------------------------+--------------------------+--------------------------+
| -   Titan                | -   Distributed graph    | -                        |
|                          |     database             |                          |
|                          | -   Support Transection  |                          |
|                          |     and eventual         |                          |
|                          |     consistency          |                          |
|                          | -   Can use Cassandra,   |                          |
|                          |     HBse or BerkeleyDB   |                          |
|                          |     to store data.       |                          |
|                          | -   Support geo, numeric |                          |
|                          |     and text search      |                          |
|                          | -   Map reduce           |                          |
+--------------------------+--------------------------+--------------------------+
| -   Objectivity:         | -   Graph NoSQL database | -                        |
|                          | -   Good at exploring    |                          |
|                          |     relationships in     |                          |
|                          |     data.                |                          |
|                          | -   Suits for areas like |                          |
|                          |     social networks.     |                          |
+--------------------------+--------------------------+--------------------------+
| -   Stardog              | -   Graph database       | -                        |
|                          | -   ACiD                 |                          |
+--------------------------+--------------------------+--------------------------+
| -   FlockDB<span         | -   Graph database       | -   Fewer function cause |
|     class="Apple-convert | -   Twitter uses it to   |     it’s simpler(maybe   |
| ed-space"> </span>       |     store social graphs  |     it’s an advantage)   |
|                          | -   Designs for websites |                          |
+--------------------------+--------------------------+--------------------------+
| -   GrapheneDB           | -   Cloud hosting Neo4j  | -   Same as Neo4j        |
+--------------------------+--------------------------+--------------------------+
| -   Sparksee             | -   Data compression(use | -                        |
|                          |     bitmap to represent  |                          |
|                          |     data)                |                          |
+--------------------------+--------------------------+--------------------------+
| -   Neo4j                | -   High Availability    | -   Does not support map |
|                          | -   Data compression     |     reduce               |
|                          | -   Fully ACID           | -   Has Max size value   |
|                          | -                        |     limitation           |
+--------------------------+--------------------------+--------------------------+
| -   CortexDB             | -   Multiple data model: | -                        |
|                          |     key-value, graph,    |                          |
|                          |     multi value column   |                          |
|                          | -   Distributed          |                          |
+--------------------------+--------------------------+--------------------------+

-   Data Caching

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   MemCachier           | -   In memory scalable   | -   No ACID              |
|                          |     key value pair cache |                          |
|                          | -   Better reliability   |                          |
|                          |     and usability than   |                          |
|                          |     memcached            |                          |
+--------------------------+--------------------------+--------------------------+
| -   Redis                | -   In memory            | -   No ACID              |
|                          |     non-relational       |                          |
|                          |     database             |                          |
|                          | -   Scale out seamlessly |                          |
|                          | -   Zero Down time       |                          |
|                          | -   Secure               |                          |
|                          | -   Persistent           |                          |
+--------------------------+--------------------------+--------------------------+
| -   Redis Labs Memcached | -   Cloud hosting        | -   Similar as Memcached |
|     Cloud                |     Memcached            |                          |
|                          | -   Similar as Memcached |                          |
+--------------------------+--------------------------+--------------------------+
| -   IronCache            | -   Key value cache      | -   No ACID              |
|                          | -   Cloud service        |                          |
|                          | -   Can persist the data |                          |
+--------------------------+--------------------------+--------------------------+
| -   AWS ElastiCache      | -   You can choose from  | -   Disadvantages are    |
|                          |     two in memory cache  |     similar to Redis and |
|                          |     options: Redos or    |     Memcached            |
|                          |     Memcached            |                          |
|                          | -   The advantages are   |                          |
|                          |     similar to those two |                          |
+--------------------------+--------------------------+--------------------------+
| -   BigMemory            | -   In memory data store | -                        |
|                          | -   Supports SQL<span    |                          |
|                          |     class="Apple-convert |                          |
|                          | ed-space"> </span>       |                          |
|                          | -   Runs Ehcache         |                          |
+--------------------------+--------------------------+--------------------------+
| -   Ehcache              | -   Im memory data store | -                        |
|                          | -   Schema less          |                          |
|                          | -   ACID                 |                          |
|                          | -   Sharding and         |                          |
|                          |     replication          |                          |
+--------------------------+--------------------------+--------------------------+
| -   InfiniSpan           | -   In memory key value  | -                        |
|                          |     data store           |                          |
|                          | -   Support Map reduce   |                          |
|                          | -   Support data         |                          |
|                          |     compression          |                          |
|                          | -   Support full text    |                          |
|                          |     search, and graph    |                          |
|                          |     data                 |                          |
|                          | -   Persistent           |                          |
|                          | -   ACID transection     |                          |
+--------------------------+--------------------------+--------------------------+
| -   RedHat JBoss Data    | -   In memory            | -                        |
|     Grid                 |     distributed caching  |                          |
|                          | -   Support map reduce   |                          |
|                          | -   Supports replication |                          |
|                          | -   Transection          |                          |
|                          | -   Redhat support       |                          |
+--------------------------+--------------------------+--------------------------+
| -   Memcached            | -   In memory key value  | -   Value is limited to  |
|                          |     pair cache           |     1MB                  |
|                          | -   Simpler than Redis   |                          |
|                          |     makes it easier to   |                          |
|                          |     scale out            |                          |
|                          | -   ACID                 |                          |
+--------------------------+--------------------------+--------------------------+

\

-   Document

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| -   Informix             | -   Real time processing | -   Comercial            |
|                          | -   Availability: zero   |                          |
|                          |     down time            |                          |
|                          | -   Supports SQL, JSON,  |                          |
|                          |     and even             |                          |
|                          |     time/special data    |                          |
|                          | -   Support Rest API     |                          |
+--------------------------+--------------------------+--------------------------+
| -   JumboDB              | -   Supports indexing on | -   No sharding and      |
|                          |     Json                 |     replication yet      |
|                          | -   Supports data        | -   Immaturity           |
|                          |     compression          | -   Join                 |
|                          | -   Supports complex     | -   No ACID Transection  |
|                          |     data model           |                          |
+--------------------------+--------------------------+--------------------------+
| -   RethinkDB            | -   Use Json as storage  | -   No Join              |
|                          | -   Supports complex     | -   No ACID Transection  |
|                          |     data model           |                          |
|                          | -   Sharding and         |                          |
|                          |     replication          |                          |
|                          | -   Fault tolerance      |                          |
|                          | -   MapReduce            |                          |
|                          | -   Schema-less          |                          |
+--------------------------+--------------------------+--------------------------+
| -   CouchDB              | -   JSON as storage      | -   No ACID Transection  |
|                          | -   Supports features    | -   No join              |
|                          |     that important to    |                          |
|                          |     web development such |                          |
|                          |     as real time change  |                          |
|                          |     notification         |                          |
|                          | -   Supports complex     |                          |
|                          |     data model           |                          |
|                          | -   MapReduce            |                          |
|                          | -   Eventual consistency |                          |
|                          | -   Schema-less          |                          |
+--------------------------+--------------------------+--------------------------+
| -   RavenDB              | -   Schema-less          | -                        |
|                          | -   Data compression     |                          |
|                          | -   ACID                 |                          |
|                          | -   MapReduce            |                          |
+--------------------------+--------------------------+--------------------------+
| -   TokuMX               | -   A high performance   | -   No ACID Transection  |
|                          |     distribution of      |                          |
|                          |     MongoDB              |                          |
|                          | -   Better caching       |                          |
|                          |     strategy             |                          |
|                          | -   Optimized IO         |                          |
|                          | -   Supports             |                          |
|                          |     document-level       |                          |
|                          |     locking allows       |                          |
|                          |     better concurrency   |                          |
+--------------------------+--------------------------+--------------------------+
| -   MongoDB              | -   Use Json as storage  | -   No ACID              |
|                          | -   Supports complex     | -   No Join              |
|                          |     data model           |                          |
|                          | -   Supports immediate   |                          |
|                          |     and strong           |                          |
|                          |     consistency          |                          |
|                          | -   Supports Sharding    |                          |
|                          |     and replication      |                          |
|                          | -   Schema-less          |                          |
+--------------------------+--------------------------+--------------------------+
| -   Compose              | -   Cloud hosting        | -   Similar as mongo db  |
|                          |     mongodb              |                          |
|                          | -   Similar as mongodb   |                          |
+--------------------------+--------------------------+--------------------------+
| -   Iris Couch           | -   Cloud hosting        | -   Similar as CouchDB   |
|                          |     CouchDB              |                          |
|                          | -   Similar as CouchDB   |                          |
+--------------------------+--------------------------+--------------------------+
| -   MongoLab             | -   Cloud hosting        | -   Similar as mongo db  |
|                          |     mongodb              |                          |
|                          | -   Similar as mongodb   |                          |
+--------------------------+--------------------------+--------------------------+
| -   Object Rocket        | -   Cloud hosting        | -   Similar as mongodb   |
|                          |     mongodb and redis    |                          |
|                          | -   Similar as mongodb   |                          |
+--------------------------+--------------------------+--------------------------+
| -   Azure DocumentDB     | -   Use Json as storage  | -   No Join              |
|                          | -   Supports complex     |                          |
|                          |     data model           |                          |
|                          | -   Schema-free          |                          |
|                          | -   Supports different   |                          |
|                          |     level of consistency |                          |
|                          | -   Transection          |                          |
+--------------------------+--------------------------+--------------------------+
| -   Cloudant             | -   Use Json as storage  | -   No ACID              |
|                          | -   Supports complex     |                          |
|                          |     data model           |                          |
|                          | -   Schema-free          |                          |
|                          | -   Supports Full-text   |                          |
|                          |     search               |                          |
|                          | -   Supports sptial      |                          |
|                          |     indexes              |                          |
|                          | -   Data compression     |                          |
+--------------------------+--------------------------+--------------------------+

\

