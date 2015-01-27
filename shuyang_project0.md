Project0
Shuyang Yao

Some reference information and table structue are lost when I tried to convert the my original file into this md file, please refer the original pdf file(https://github.com/coderYao/CPS516/blob/master/shuyang_project0.pdf)if you find something weird....

-   General Purpose:

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| Lotus Notes:             | Better security control  | It’s not very flexible   |
|                          | than its competitor      | in term of using because |
|                          |                          | it’s a little bit too    |
|                          | Supports more platforms  | secure                   |
|                          | than its competitor      |                          |
|                          |                          | \                        |
|                          | Support hardware as well |                          |
|                          | as software              |                          |
|                          | virtualization           |                          |
+--------------------------+--------------------------+--------------------------+
| Actian Versant           | It’s Object Oriented!    | Lack of solid            |
|                          | It’s simple and straight | theoretical basis.       |
|                          | forward to build complex |                          |
|                          | data models which are    | API is language          |
|                          | hierarchical.            | dependent                |
|                          |                          |                          |
|                          | No need to use a query   | Schema change may need a |
|                          | language                 | system-wide compile(not  |
|                          |                          | in Versant’s case)       |
|                          | No primary keys          |                          |
|                          |                          |                          |
|                          | Make developer’s life    |                          |
|                          | easier by allowing       |                          |
|                          | database to process      |                          |
|                          | complex objects models   |                          |
|                          | without writing          |                          |
|                          | mappings.                |                          |
|                          |                          |                          |
|                          | Allows you to change     |                          |
|                          | database schema while    |                          |
|                          | your service is on-line. |                          |
|                          |                          |                          |
|                          | Good Scalability         |                          |
|                          |                          |                          |
|                          | Full support for         |                          |
|                          | transactions, logging    |                          |
|                          | and locking.             |                          |
+--------------------------+--------------------------+--------------------------+
| InterSystems Cache       | A fully persistent       | \                        |
|                          | database with high       |                          |
|                          | throughput even          |                          |
|                          | comparing with in-memory |                          |
|                          | database                 |                          |
|                          |                          |                          |
|                          | Good scalability and     |                          |
|                          | performance when hosted  |                          |
|                          | on inexpensive machines. |                          |
+--------------------------+--------------------------+--------------------------+
| McObject:                | Memory data base with    | Lack of solid            |
|                          | good scalability.        | theoretical basis.       |
|                          |                          |                          |
|                          | ACID-Compliant           | API is language          |
|                          |                          | dependent                |
|                          | It’s Object Oriented!    |                          |
|                          | It’s simple and straight | Schema change may need a |
|                          | forward to build complex | system-wide compile(not  |
|                          | data models which are    | in Versant’s case)       |
|                          | hierarchical.            |                          |
|                          |                          |                          |
|                          | No need to use a query   |                          |
|                          | language                 |                          |
|                          |                          |                          |
|                          | No primary keys          |                          |
+--------------------------+--------------------------+--------------------------+
| ObjectStore:             | It’s Object Oriented!    | Lack of solid            |
|                          | It’s simple and straight | theoretical basis.       |
|                          | forward to build complex |                          |
|                          | data models which are    | API is language          |
|                          | hierarchical.            | dependent                |
|                          |                          |                          |
|                          | No need to use a query   | Schema change may need a |
|                          | language                 | system-wide compile(not  |
|                          |                          | in Versant’s case)       |
|                          | No primary keys          |                          |
+--------------------------+--------------------------+--------------------------+
| WakandaDB:               | Everything(schema,       | Open Source and not      |
|                          | server-side processing,  | mature                   |
|                          | querying) can all be     |                          |
|                          | done in JavaScript       |                          |
|                          |                          |                          |
|                          | Open Source              |                          |
+--------------------------+--------------------------+--------------------------+
| IBM IMS:                 | It’s a full function     | Developers may need to   |
|                          | database                 | write more code.         |
|                          |                          |                          |
|                          | Optimized for high       |                          |
|                          | transection rates.       |                          |
|                          |                          |                          |
|                          | High Availability        |                          |
|                          |                          |                          |
|                          | \                        |                          |
+--------------------------+--------------------------+--------------------------+
| Adabas                   | Is able to work close    | No access control in     |
|                          | with previously existing | term of native network   |
|                          | database system          | encryption               |
+--------------------------+--------------------------+--------------------------+
| UniVerse:                | Multi-valued database    | The fact that it does    |
|                          |                          | not adhere to 1FN can be |
|                          | High Availability        | abused                   |
|                          |                          |                          |
|                          | Good Scalability         |                          |
|                          |                          |                          |
|                          | Intuitive database       |                          |
|                          | design                   |                          |
|                          |                          |                          |
|                          | High Performance         |                          |
|                          |                          |                          |
|                          | Does not constrain by    |                          |
|                          | 1st Normal Form          |                          |
+--------------------------+--------------------------+--------------------------+
| UniData                  | Secure                   | Similar to UniVerse      |
|                          |                          |                          |
|                          | Similar to UniVerse      |                          |
+--------------------------+--------------------------+--------------------------+
| Documentation xDB        | XML-based Database       | Not ACID-compliant       |
|                          |                          |                          |
|                          | Allows the schema to be  |                          |
|                          | easily modified.         |                          |
|                          |                          |                          |
|                          | Flexible schema compared |                          |
|                          | to relational database   |                          |
|                          |                          |                          |
|                          | EMC\^2’s                 |                          |
|                          | disaster-recovery        |                          |
|                          | options                  |                          |
+--------------------------+--------------------------+--------------------------+
| Tamino XML Server        | XML-based Database       | Not ACID-compliant like  |
|                          | advantage described in   | many other document      |
|                          | Documentation xDB        | based database           |
+--------------------------+--------------------------+--------------------------+
| Ipedo XML Database       | XML-based Database       | Not ACID-compliant like  |
|                          | advantage described in   | many other document      |
|                          | Documentation xDB        | based database           |
+--------------------------+--------------------------+--------------------------+
| OrientDB:                | Document oriented        | Not Mature, API changes  |
|                          | database with graph      | over time.               |
|                          | database feature         |                          |
|                          |                          |                          |
|                          | Open Source              |                          |
|                          |                          |                          |
|                          | Can be queried using SQL |                          |
|                          |                          |                          |
|                          | AICD                     |                          |
+--------------------------+--------------------------+--------------------------+
| SQLite                   | Easy to use              | Doesn’t scale very well  |
|                          |                          |                          |
|                          | Consumes less resources  |                          |
+--------------------------+--------------------------+--------------------------+
| Firebird                 | Free open source         | Not very scalable in     |
|                          |                          | term of horizontal       |
|                          | Relational database      | scaling                  |
|                          |                          |                          |
|                          | Well established and     | Difficult to model       |
|                          | tested based on solid    | complex data model       |
|                          | theoretical foundation   | because it is table      |
|                          |                          | based                    |
|                          | ACID                     |                          |
|                          |                          |                          |
|                          | SQL as access language   |                          |
|                          |                          |                          |
|                          | Join!                    |                          |
|                          |                          |                          |
|                          | Large Throughput         |                          |
+--------------------------+--------------------------+--------------------------+
| SAP Sybase ASE:          | Relational database      | Relational database      |
|                          | advantages as described  | disadvantages described  |
|                          | in Firebird              | in Firebird              |
+--------------------------+--------------------------+--------------------------+
| SAP SQL Anywhere         | Relational database      | Relational database      |
|                          | advantages as described  | disadvantages described  |
|                          | in Firebird              | in Firebird              |
|                          |                          |                          |
|                          | Embed: consume less      |                          |
|                          | resources.               |                          |
|                          |                          |                          |
|                          | \                        |                          |
+--------------------------+--------------------------+--------------------------+
| Postgres-XL:             | ACID                     | Too complex for simple   |
|                          |                          | stuff                    |
|                          | Open Source              |                          |
|                          |                          |                          |
|                          | Cluster-wide Consistency |                          |
|                          |                          |                          |
|                          | Secure                   |                          |
|                          |                          |                          |
|                          | SQL                      |                          |
|                          |                          |                          |
|                          | Horizontal scaling       |                          |
|                          |                          |                          |
|                          | Rich feature set.        |                          |
+--------------------------+--------------------------+--------------------------+
| Pecona                   | Same as MySql            | Same as MySql            |
+--------------------------+--------------------------+--------------------------+
| MySQL                    | Relational database      | Not very Scalable        |
|                          | advantages as described  |                          |
|                          | in Firebird              |                          |
|                          |                          |                          |
|                          | \                        |                          |
+--------------------------+--------------------------+--------------------------+
| Oracle Database          | Relational database      | Price                    |
|                          | advantages as described  |                          |
|                          | in Firebird              | Relational database      |
|                          |                          | disadvantages as         |
|                          | Commercial               | described in Firebird    |
+--------------------------+--------------------------+--------------------------+
| IBM DB2                  | Relational database      | Price                    |
|                          | advantages as described  |                          |
|                          | in Firebird              | Relational database      |
|                          |                          | disadvantages as         |
|                          | Commercial               | described in Firebird    |
+--------------------------+--------------------------+--------------------------+

\

-   Specialist analytic

+--------------------------+--------------------------+--------------------------+
| System                   | Pros                     | Cons                     |
+--------------------------+--------------------------+--------------------------+
| Google BigQuery          | Allows users to use      | Not able to do complex   |
|                          | SQL-like queries to      | data processing.         |
|                          | query massive datasets   |                          |
|                          |                          | You can’t update your    |
|                          | Rest API                 | data, only appending is  |
|                          |                          | allowed.                 |
|                          | Google’s infrastructure  |                          |
|                          | makes the operation fast | No large Join.           |
|                          | and economic.            |                          |
|                          |                          |                          |
|                          | Makes ad-hoc and         |                          |
|                          | trial-and-error          |                          |
|                          | interactive query on     |                          |
|                          | large dataset possible   |                          |
+--------------------------+--------------------------+--------------------------+
| InfluxDB                 | Open Source              | Maturity                 |
|                          |                          |                          |
|                          | SQL-like language        |                          |
|                          |                          |                          |
|                          | Native HTTP API          |                          |
|                          |                          |                          |
|                          | Can process big amount   |                          |
|                          | of data.                 |                          |
|                          |                          |                          |
|                          | Focus on time series.    |                          |
+--------------------------+--------------------------+--------------------------+
| 1010data                 | Interactive analytical   | Price.                   |
|                          | service.                 |                          |
|                          |                          | Should support more      |
|                          | A rich set of analytic   | complex database         |
|                          | functions are            | operations.              |
|                          | integrated.              |                          |
|                          |                          |                          |
|                          | Suit for very large data |                          |
|                          | set.                     |                          |
|                          |                          |                          |
|                          | Decent performance with  |                          |
|                          | high scalability.        |                          |
+--------------------------+--------------------------+--------------------------+
| BitYota:                 | Data warehouse as a      | \                        |
|                          | service                  |                          |
|                          |                          |                          |
|                          | SQL                      |                          |
|                          |                          |                          |
|                          | Real time data analysis  |                          |
+--------------------------+--------------------------+--------------------------+
| AWS RedShift             | Scaling is easy          | Because RedShift does    |
|                          |                          | not maintain the         |
|                          | You can use SQL to query | uniqueness of data,      |
|                          |                          | programmer are           |
|                          | Can work seamlessly with | responsible for their    |
|                          | other AWS services       | data integrity.          |
+--------------------------+--------------------------+--------------------------+
| SpaceCurve:              | Focus mainly on spatial  | Query: Some              |
|                          | data.                    | patent-pending           |
|                          |                          | strategies that optimize |
|                          | Good at real-time        | quires                   |
|                          | location analysis        |                          |
|                          |                          | View: Algorithm that     |
|                          |                          | make updating views more |
|                          |                          | efficient                |
|                          |                          |                          |
|                          |                          | Supports serializable    |
|                          |                          | concurrent transection   |
+--------------------------+--------------------------+--------------------------+
| LogicBlox:               | Query: Some              | \                        |
|                          | patent-pending           |                          |
|                          | strategies that optimize |                          |
|                          | quires                   |                          |
|                          |                          |                          |
|                          | View: Algorithm that     |                          |
|                          | make updating views more |                          |
|                          | efficient                |                          |
|                          |                          |                          |
|                          | Supports serializable    |                          |
|                          | concurrent transection   |                          |
+--------------------------+--------------------------+--------------------------+
| MonetDB:                 | Column oriented store:   | Increased disk seek time |
|                          |                          |                          |
|                          | Good at OLAP scenario    | Insertion costs more     |
|                          |                          |                          |
|                          | Higly Compressed         |                          |
+--------------------------+--------------------------+--------------------------+
| Pivotal GreenPlum:       | Supports both row and    | Column oriented store    |
|                          | column-oriented storage  | disadvantage             |
|                          |                          |                          |
|                          | Highly scalable          | Increased disk seek time |
|                          |                          |                          |
|                          |                          | Insertion costs more     |
|                          |                          |                          |
|                          |                          | \                        |
+--------------------------+--------------------------+--------------------------+
| HP Verica                | Column Oriented          | Immaturity               |
|                          |                          |                          |
|                          | Highly compressed        | Increased disk seek time |
|                          |                          |                          |
|                          | Good at log parsing      | Insertion costs more     |
+--------------------------+--------------------------+--------------------------+
| SAP Sybase IQ            | Column Oriented          | Increased disk seek time |
|                          |                          |                          |
|                          |                          | Insertion costs more     |
+--------------------------+--------------------------+--------------------------+
| ParStream:               | Real time analysis       | \                        |
|                          |                          |                          |
|                          | Focus on IOT(Internet of |                          |
|                          | Things) data             |                          |
+--------------------------+--------------------------+--------------------------+
| IBM InfoSphere           | Real-time analytic       | Rapid deployment         |
|                          | platform                 | analysis                 |
|                          |                          |                          |
|                          | Merge diverse data       | Column-oriented database |
|                          |                          |                          |
|                          |                          | In memory                |
|                          |                          |                          |
|                          |                          | Highly compressed        |
+--------------------------+--------------------------+--------------------------+
| Kx Systems:              | Column store database    | Column store database    |
|                          | advantages described in  | disadvantages described  |
|                          | MonetDB                  | in MonetDB               |
+--------------------------+--------------------------+--------------------------+
| LucidDB:                 | Column store database    | Column store database    |
|                          | advantages described in  | disadvantages described  |
| \                        | MonetDB                  | in MonetDB               |
|                          |                          |                          |
|                          | Open Source              |                          |
|                          |                          |                          |
|                          | Bitmap indexing          |                          |
|                          |                          |                          |
|                          | Hash join/aggregation    |                          |
|                          |                          |                          |
|                          | Multiversioning          |                          |
+--------------------------+--------------------------+--------------------------+
| Kognitio:                | In memory                | \                        |
|                          |                          |                          |
|                          | Support SQL              |                          |
|                          |                          |                          |
|                          | integrated with HADOOP   |                          |
+--------------------------+--------------------------+--------------------------+
| Actian Vector            | A high performance       | \                        |
|                          | analytic frame built on  |                          |
|                          | Hadoop                   |                          |
|                          |                          |                          |
|                          | Developer can use SQL to |                          |
|                          | interact with the system |                          |
+--------------------------+--------------------------+--------------------------+
| MetaMarkets Druid:       | A distributed real-time  | Column-oriented          |
|                          | data store               | storage’s disadvantage   |
|                          |                          |                          |
|                          | Real time ingestion      |                          |
|                          |                          |                          |
|                          | Column-oriented          |                          |
|                          | storage’s advantage      |                          |
|                          |                          |                          |
|                          | Bitmap indexing          |                          |
|                          |                          |                          |
|                          | Fault tolerance          |                          |
+--------------------------+--------------------------+--------------------------+
| Teradata                 | A decent data warehouse  | Price                    |
|                          | system                   |                          |
|                          |                          |                          |
|                          | Developers can choose to |                          |
|                          | store the data either    |                          |
|                          | based on row or column   |                          |
+--------------------------+--------------------------+--------------------------+
| SQream                   | Scalable SQL data base   | Column oriented storage  |
|                          |                          | disadvantages            |
|                          | GPU based database       |                          |
|                          | brings high parallel     |                          |
|                          | processing ability       |                          |
|                          |                          |                          |
|                          | Column oriented storage  |                          |
|                          | advantages               |                          |
+--------------------------+--------------------------+--------------------------+
| RainStor                 | Can work with different  | \                        |
|                          | data types               |                          |
+--------------------------+--------------------------+--------------------------+
| HPCC                     | Introduced a new         | Still growing.           |
|                          | programming language:    |                          |
|                          | ECL                      |                          |
|                          |                          |                          |
|                          | It is more complex than  |                          |
|                          | a key-value pair         |                          |
|                          | storage.                 |                          |
|                          |                          |                          |
|                          | High availability,       |                          |
|                          | scalability and          |                          |
|                          | consistent               |                          |
+--------------------------+--------------------------+--------------------------+
| Teradata Aster:          | Allows users to write    | \                        |
|                          | map reduce code that     |                          |
|                          | manipulate relational    |                          |
|                          | data base data.          |                          |
|                          |                          |                          |
|                          | Graph analytics engine   |                          |
|                          |                          |                          |
|                          | Support massive parallel |                          |
|                          | processing               |                          |
+--------------------------+--------------------------+--------------------------+
| SciDB                    | Array data model         | Focus mainly on          |
|                          |                          | Mathematic operations    |
|                          | Supports complex         |                          |
|                          | mathematic processing on |                          |
|                          | the arrays               |                          |
|                          |                          |                          |
|                          | Can model uncertainty    |                          |
+--------------------------+--------------------------+--------------------------+
| Hadapt                   | Brings SQL to Hadoop,    | No transections          |
|                          | which allows users to    |                          |
|                          | write SQL to query on    |                          |
|                          | massive amount of data   |                          |
|                          |                          |                          |
|                          | Uses a hybrid storage    |                          |
|                          | engine which stores      |                          |
|                          | structured data in a     |                          |
|                          | traditional relational   |                          |
|                          | database while           |                          |
|                          | unstructured data in     |                          |
|                          | HDFS.                    |                          |
+--------------------------+--------------------------+--------------------------+
| JethroData               | Like Hadapt, it builds a | No transections          |
|                          | layer on top of Hadoop   |                          |
|                          | that allows user to      |                          |
|                          | write SQL on Hadoop      |                          |
|                          |                          |                          |
|                          | Unique index strategy    |                          |
|                          |                          |                          |
|                          | Scalability that comes   |                          |
|                          | with HDFS                |                          |
+--------------------------+--------------------------+--------------------------+
| CitusDB:                 | SQL on Hadoop            | No transections          |
|                          |                          |                          |
|                          | Also suppor              |                          |
|                          | semi-structured data     |                          |
|                          |                          |                          |
|                          | Optimized specially for  |                          |
|                          | time-series data.        |                          |
+--------------------------+--------------------------+--------------------------+
| Impala:                  | SQL on Hadoop            | No transections          |
|                          |                          |                          |
|                          | It’s supported by        | Data need to be stored   |
|                          | Cloudera                 | in a specific data       |
|                          |                          | format                   |
+--------------------------+--------------------------+--------------------------+
| IBM Big SQL              | SQL on Hadoop            | No transections          |
+--------------------------+--------------------------+--------------------------+
| Presto                   | Sql on Hadoop            | No transections          |
|                          |                          |                          |
|                          | Can query data from      |                          |
|                          | different source and     |                          |
|                          | bring them together      |                          |
+--------------------------+--------------------------+--------------------------+
| Apache Drill:            | SQL on Hadoop            | No transections          |
|                          |                          |                          |
|                          | Apache license           |                          |
|                          |                          |                          |
|                          | Can work with            |                          |
|                          | semi-structured or       |                          |
|                          | nested data              |                          |
|                          |                          |                          |
|                          | Low latency              |                          |
+--------------------------+--------------------------+--------------------------+
| Apache Hive:             | Data warehouse built on  | No update and delete     |
|                          | Hadoop                   | operation                |
|                          |                          |                          |
|                          | Use a SQL like language  | No access control        |
|                          |                          |                          |
|                          | Bitmap index             | The overhead brought by  |
|                          |                          | Map Reduce make it a     |
|                          | Supports different       | little bit slow          |
|                          | storage type.            |                          |
|                          |                          |                          |
|                          | Data are compressed      |                          |
|                          |                          |                          |
|                          | \                        |                          |
+--------------------------+--------------------------+--------------------------+
| Apache Tajo              | Fully distributed SQL    | No transections          |
|                          |                          |                          |
|                          | Various query            |                          |
|                          | optimization             |                          |
|                          |                          |                          |
|                          | Supports ANSI/ISO SQL    |                          |
|                          |                          |                          |
|                          | Has a shell              |                          |
+--------------------------+--------------------------+--------------------------+

\

\

-   Big Tables

+--------------------------------------+--------------------------------------+
| System                               | -   Pros                             |
|                                      | -   Cons                             |
+--------------------------------------+--------------------------------------+
| -   Google Cloud Datastore           | -   No schema is needed, Aims at     |
|                                      |     storing non-relational data      |
|                                      | -   Write scale and read scale.      |
|                                      | -   Supports transection             |
|                                      | -   No database layer caching        |
|                                      | -   No Join                          |
|                                      | -   Filter results using a subquery  |
|                                      |     is not supported                 |
+--------------------------------------+--------------------------------------+
| -   Google App Engine Datastore      | -   Key-value pair store makes it    |
|                                      |     more flexible                    |
|                                      | -   Does not support ACID            |
|                                      |     transactions                     |
|                                      | -   No join                          |
+--------------------------------------+--------------------------------------+
| -   Cassandra.io                     | -   Linear scalability(All nodes are |
|                                      |     identical)                       |
|                                      | -   Fault-tolerance on inexpensive   |
|                                      |     hardware                         |
|                                      | -   The language it uses(CQL3) is    |
|                                      |     very similar to SQL              |
|                                      | -   Constant-time writes             |
|                                      | -   Integrated with Hadoop           |
|                                      | -   No Join                          |
|                                      | -   Does not support ACID            |
+--------------------------------------+--------------------------------------+
| -   Accumulo                         | -   Wode Column Store DB similar to  |
|                                      |     Cassandra and HBase              |
|                                      | -   Better Performance(can scan 800k |
|                                      |     entries per second per node)     |
|                                      |     compare to HBase                 |
|                                      | -   Provides cell-level security     |
|                                      | -                                    |
+--------------------------------------+--------------------------------------+
| -   Hbase                            | -   Works hand in hand with Hadoop   |
|                                      | -   Specially optimized for real     |
|                                      |     time analysis                    |
|                                      | -   Also linear scalability          |
|                                      | -   Consistent reads and writes      |
|                                      | -   Row level Atomic                 |
|                                      | -   No strict ACID                   |
|                                      | -   Because of its master and slave  |
|                                      |     architecture, Hbase has the      |
|                                      |     problem of single point failure  |
|                                      | -   No join                          |
+--------------------------------------+--------------------------------------+
| -   HyperTable                       | -   Implements using c++             |
|                                      | -   Runs on haddop                   |
|                                      | -   SQL like language                |
|                                      | -   Faster and smaller than HBase    |
|                                      | -                                    |
+--------------------------------------+--------------------------------------+
| -   DataStax Enterprise              | -   Built on Cassandra               |
|                                      | -   Comercial                        |
|                                      | -   Similar to Cassandra             |
|                                      | -   Similar to Cassandra             |
+--------------------------------------+--------------------------------------+

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
|                          | -   ACID                 |                          |
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
|                          |     Hadoop solr and etc. |                          |
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
|                          | -   Column oriented      |     time                 |
|                          | -   Relational databse   | -   Insertion costs more |
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
| -   HypergraphDB         | -   Graph oriented       | -   Does not support map |
|                          | -   graph specific       |     reduce               |
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
| -   FlockDB              | -   Graph database       | -   Fewer function cause |
|                          | -   Twitter uses it to   |     it’s simpler(maybe   |
|                          |     store social graphs  |     it’s an advantage)   |
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
|                          | -   Supports SQL         |                          |
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



To be continued...

Refrence:
  Comparative Analysis of Microsoft Exchange and Lotus Notes http://www.brighthub.com/computing/windows-platform/articles/52715.aspx
  Versant Object Database http://www.actian.com/products/operational-databases/versant/

  InterSystems Caché Benchmark http://www.intersystems.com/assets/Cache_benchmark-1c69bf617b51d5a2dee145442deaa371.pdf
  http://wakandadb.org/
  http://en.wikipedia.org/wiki/IBM_Information_Management_System
  http://www.itqlick.com/adabas/feedback
  http://www.rocketsoftware.com/products/rocket-universe
  http://stackoverflow.com/questions/4219624/pros-and-cons-of-multi-value-databases
  http://www.orientechnologies.com/orientdb/
  https://www.mail-archive.com/orient-database@googlegroups.com/msg03928.html
  Firebrid.org
  www.sap.com
  www.influxdb.net
  www.bityota.com
  AWS RedShift
  www.spacecurve.com/
  Column Oriented Database Vs Row Oriented Databases 
  http://www.pivotal.io/
  http://www.sap.com/
  https://www.parstream.com/
  Kx.com
  Luciddb.com
  Kognitio.com
  http://druid.io/blog/2012/10/24/introducing-druid.html
  Vertica vs Aster Data vs Greenplum vs Netezza vs Teradata from stackoverflow
  site.teradata.com
  http://hpccsystems.com/
  Teradata Aster gets graph database, HDFS-compatible file store http://www.zdnet.com/article/teradata-aster-gets-graph-database-hdfs-compatible-file-store/
  Sicdb.org
  SQL on Hadoop Landscape and Considerations
  www.jethrodata.com
  www.citusdata.com/
  http://www.cloudera.com/content/cloudera/en/products-and-services/cdh/impala.html
  8 SQL-on-Hadoop frameworks worth checking out
  http://www-01.ibm.com/software/data/what-is/big-sql.html
  http://drill.apache.org/
  https://hive.apache.org/
  Apache Hive Review http://www.gise.cse.iitb.ac.in/wiki/images/2/26/Hive.pdf
  http://tajo.apache.org/
  StackOverflow: GoogleApps Datastore Cons and Pros
  https://cloud.google.com/datastore/docs
  StackOverfolw: GAE DataStore vs Google Cloud SQL for Enterprise Managment Systems
  Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs OrientDB vs Aerospike vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris comparison by Kristof Kovacs
  http://cassandra.apache.org/
  http://apache-accumulo.1065345.n5.nabble.com/How-does-Accumulo-compare-to-HBase-td10464.html
  Database Options: Beyond RDBMS http://www.hcltech.com/blogs/engineering-rd-services/database-options-beyond-rdbms
  HBase Architecture Analysis, CYANNY
  http://hypertable.org/
  http://en.wikipedia.org/wiki/DataStax
  http://aws.amazon.com/dynamodb
  http://www.slideshare.net/saniyakhalsa/dynamo-db-pros-and-cons
  http://aws.amazon.com/simpledb/
  http://aws.amazon.com/dynamodb/faqs/
  https://wiki.openstack.org/wiki/MagnetoDB
  https://redislabs.com/redis-comparison
  https://redislabs.com/redis-comparison
  http://aws.amazon.com/elasticache/
  http://www.redisgreen.net/
  http://objectrocket.com/redis
  http://hyperdex.org/
  https://github.com/google/leveldb
  http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html
  http://www.oracle.com/us/products/database/nosql/overview/index.html
  https://redislabs.com/redis-comparison
  wikipedia
  http://basho.com/riak/
  https://www.arangodb.com/
  http://www.aerospike.com/docs/architecture/
  http://www.gridgain.com/products/in-memory-data-fabric/features/
  http://www.scaleoutsoftware.com/
  http://www.pivotal.io/big-data/pivotal-gemfire-xd
  http://lucidworks.com/product
  https://wiki.trafodion.org
  http://www.splicemachine.com/
  https://go.oracle.com/
  https://go.oracle.com/
  http://hana.sap.com/
  http://vschart.com/compare/infinitegraph/vs/neo4j
  http://www.hypergraphdb.org/
  http://franz.com/agraph/allegrograph/
  Scaling Apache Giraph to a trillion edges
  http://sparqlcity.com/
  http://research.microsoft.com/en-us/projects/trinity/
  thinkaurelius.github.io/titan/
  www.objectivity.com
  https://github.com/twitter/flockdb
  http://sparsity-technologies.com/#sparksee
  http://neo4j.com/
  http://www.odbms.org/
  https://www.memcachier.com/
  https://redislabs.com/memcached-cloud
  http://www.iron.io/cache
  http://terracotta.org/
  http://ehcache.org/
  http://infinispan.org/about/
  http://www.redhat.com/en/technologies/jboss-middleware/data-grid
  http://memcached.org/
  http://www-01.ibm.com/software/data/informix/
  https://github.com/comsysto/jumbodb
  http://rethinkdb.com/
  http://docs.couchdb.org/en/latest/intro/why.html
  http://ravendb.net/
  http://www.tokutek.com/tokumx-for-mongodb/

