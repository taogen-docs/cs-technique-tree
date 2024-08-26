# Java-based Technique Tree 

### CS Foundations

  - Data Structure and Algorithms
  - Computer Architecture
  - Operating System Concepts
  - Computer Networks
  - Database System Concepts

### Programming Languages 

  - Infrastructure
    - C
    - C++ (pronounced "cee plus plus")
    - Golang
    - Rust (/rʌst/)
    - Lua (pronounced "Loo-uh")
  - Application
    - Java (pronounced "/ˈdʒɑːvə/")
    - C# (pronounced "c sharp")
    - Visual Basic .NET
    - PHP
    - Ruby (/ˈruːbi/)
    - JavaScript
    - Kotlin (/ˈkɒtlɪn/)
    - Objective-C
    - Swift
  - Glue
    - Python (/ˈpaɪθɑːn/)
    - Perl (/pɜː(r)l/)
    - Groovy (/ˈɡruːvi/)
  - Specific Domain
    - SQL (pronounced "S-Q-L" /ˈɛs kjuː ˈɛl/ or "sequel" /ˈsiːkwəl/)
    - Shell (/ʃel/)
    - R

### Java Utility Libraries

Core / General-Purpose
- Google Guava
- Apache Commons Lang
- Hutool

Data Handling

- Math
  - Apache Commons Math
- Datetime
  - JodaTime
- Cryptographic 
  - Apache Commons Codec

Parser

- JSON
  - Google GSON
  - Jackson
  - org.json
  - XStream 
  - JSON-lib 
- XML
  - JDK JAXB
  - STaX
  - Xerces/Xerces2 
  - JAXP
  - Dom4j
  - Xstream
- HTML
  - Jsoup 

Chart, Report, Graph

- JFreeChart 
- JFreeReport 
- JGraphT

GUI / Windowing

- Swing
- SWT
- Eclipse RCP

IO and File Manipulation

- IO

  - apache commons IO

- Compress

  -  Apache Commons Compress

- Zip

  -  zip4j

- Office

  - [Apache POI](https://poi.apache.org/)
  - [EasyExcel](https://github.com/alibaba/easyexcel)

  - Docx4j 

- Image manipulation

  - AWT (javax.imageio, a built-in Java library)
  - [ImageJ](https://imagej.nih.gov/ij/)
  - OpenIMAJ
  - TwelveMonkeys
  - [imgscalr](https://github.com/rkalla/imgscalr)

- PDF manipulation

  -  [iText](https://itextpdf.com/en)
  -  Apache FOP

- File Conversion

  - [Open Office](https://www.openoffice.org/) (90+% perfect, Not Pure Java - Requires Open Office installed OpenOffice is a native Office suite which supports a Java API.)
  - [docs-to-pdf-converter](https://github.com/yeokm1/docs-to-pdf-converter) (open source)
  - [xdocreport](https://github.com/opensagres/xdocreport) (open source)
  - [Snowbound Imaging SDK](http://www.snowbound.com/format/word.html) (commercial)
  - [e-iceblue](https://www.e-iceblue.cn/) by 成都冰蓝 (commercial)
  - [aspose](https://www.aspose.com/) (commercial)
  - [PDFTron](https://www.pdftron.com/) (commercial)
  - [jOfficeConvert](https://www.qoppa.com/officeconvert/) (commercial)
  - [JODConverter](https://github.com/sbraconnier/jodconverter) 

Network

- HTTP Client
  - Java Built-in `HttpURLConnection`
  - Java 9 `HttpClient` API
  - Apache HttpComponents `HttpClient`
  - Unirest HTTP API
  - OkHttp
  - Spring REST Client
- Email
  - Spring framework
  - javax.mail
  - Apache Commons Email
- Socket
  - Netty
  - Apache MINA
- Serialization 
  - Google Protocol Buffers 

Development

- Dev
  - Lombok
- Static Analysis
  - Eclipse JDT
- Bytecode 
  - Javassist
  - CgLib
- Logging
  - java.util.logging (JUL). *If logging is unimportant, j.u.l is fine.*
  - Apache Log4j2
  - Logback 
  - SLF4J. (*SLF4J is a logging facade. SLF4J allows the end-user the liberty to choose the underlying logging framework.*)
  - Slf4j + Log4j
  - Scribe + Kafka
- Unit Testing
  - JUnit
  - Mockito

Messaging 

- JMS
- MQ

Embedded SQL Database

- H2
- HSQL
- Derby

NLP

- OpenNLP 
- Stanford Parser 

Schedule

- Spring
- quartz

Work Flow

- Activiti

### Java Data Access

- Cache
    - Guava Cache
    - Ehcache
    - Redis
    - Memcached
- JDBC Database Access
    - JDBC for PostgreSQL, MySQL, SQL Server, Oracle
      - Batch Operations, Transaction Management, Advanced Data Type, Store Procedure
- JDBC Connection Pools
  - Apache Commons DBCP
  - C3P0
  - HikariCP
  - Tomcat JDBC
  - Alibaba Druid
- JDBC Troubleshooting
  - P6spy

- Java NoSQL Access
  - Redis
    - Lettuce
    - Jedis
    - Redisson
    - Spring Data Redis
      - Redis support (RedisTemplate)
      - Redis Repositories
  - MongoDB
    - MongoDB Java Driver
    - Spring Data MongoDB
- Java Persistence Framework 
  - Spring `JdbcTemplate`. Using JdbcTemplate you are using a lower level access, with more flexibility, but probably also more boilerplate.
  - Spring Data JPA. JPA is database-agnostic, meaning that the same code can be used in a variety of databases with few (or no) modifications.
  - Spring Data JDBC. JDBC is database-dependent, which means that different scripts must be written for different databases.
  - JOOQ
  - JPA
  - MyBatis
  - Mybatis-Plus
  - Hibernate
  - paoding-rose-jade
- Java Search Engine Access
  - Elasticsearch
    - Java REST Client
      - Java Low Level REST Client
      - Java High Level REST Client
    - Java API (deprecated)
    - Spring Data Elasticserach
      - Elasticsearch Operations (`ElasticsearchRestTemplate`)
      - Elasticsearch Repositories

### Java Web Development

  - Web Protocols
    - HTTP
    - HTTPS
    - HTTP/2
  - Web Servers
    - Apache HTTP Server
    - Apache Tomcat
    - Nginx (pronounced "engine-x")
    - Caddy
    - WebLogic
    - Jetty
    - Resin web server
    - Microsoft IIS
    - JBoss
- Java Web
  - [Java Servlet](https://docs.oracle.com/javaee/5/tutorial/doc/bnafe.html)
  - Web pages / Template Engines
    - [JavaServer Pages (JSP)](https://docs.oracle.com/javaee/5/tutorial/doc/bnagx.html), [Apache FreeMarker](https://freemarker.apache.org/), [Thymeleaf](https://www.thymeleaf.org/)
    - [Apache Velocity](https://velocity.apache.org/), Groovy Template, JSF, Jade4j
  - Web Frameworks
    - [Spring Framework](https://spring.io/projects/spring-framework)
    - [Spring Boot](https://spring.io/projects/spring-boot)
    - [Spring Boot Admin](https://github.com/codecentric/spring-boot-admin)
    - [Spring Cloud](https://spring.io/projects/spring-cloud)
    - [Quarkus](https://quarkus.io/)
  - Security Frameworks
    - [Spring Security](https://spring.io/projects/spring-security)
    - [Apache Shiro](https://shiro.apache.org/)
  - API
    - Swagger UI
    - RESTful
    - GraphQL
- Component Libraries
  - Logging
    - Log4j
    - SLF4j
  - Job Scheduling
    - Quartz
    - Spring Scheduling Tasks
  - Workflow Engine
    - Activiti
    - Bonita, jBPM, Workflow Server, Camunda, Copper
  - Web Crawler
    - Jsoup
    - Crawler4j
    - WebMagic
    - Apache Nutch
  - Single Sign-on
    - Spring Boot and OAuth2
    - OAuth
    - OpenSSO
    - Apereo CAS

### Network Programming

  - TCP/IP
  - Network IO (BIO, NIO, AIO) 
  - Socket & SSL
  - Web Socket
      - Spring WebSockets support
  - NIO Frameworks
    - Netty
    - Apache Mina
  - Reactive Frameworks 
    - Eclipse Vert.x
  - RPC Frameworks
    - Web Service
    - Apache Thrift
    - gRPC

### Third Party Platforms

- WeChat official account
- Payment
  - WeChat Pay
  - Alipay
- Share SDK
  - Open QQ, Weixin, Weibo
  - Facebook, Twitter
- SMS
  - 创蓝, alisms
- Push
  - 个推, 极光, 腾讯推送
- Bot
  - Telegram
  - Slack
- Automation Workflow
  - Zapier

### Data Storage and Search

> Database Index & Cache Cluster & Search Engine

Database Systems

- Relational Databases
  - H2 Database
  - SQLite
  - MySQL (pronounced "My S-Q-L" or "my sequel")
  - MariaDB
  - PostgreSQL
  - SQL Server
  - Oracle
- Key-Value Databases
  - Redis
  - Memcached
- Document Databases
  - MongoDB
  - DynamoDB
  - Couchbase Server
  - Google Cloud Firestore
  - MongoDB Atlas
- Wide Column Databases
  - Cassandra
  - HBase
- Search Engines
  - Apache Lucene
  - Apache Solr
  - Elasticsearch
  - Algolia
  - Meilisearch
- Graph Databases
  - Neo4j
- Multi-model Database
  - Fauna DB

Other Data Storage

- Object Storage
  - MinIO
  - SeaweedFS
- Cache
  - Ehcache
  - Guava's Cache
  - Redis
  - Memcached

### Information Security

Web Security

- HTTPS, SSL
- Authentication and Authorization
  - OAuth2.0
  - JSON Web Token(JWT)
- Encryption
  - Jasypt-spring-boot

### Performance Optimization

> 有时候堆硬件比人工便宜。聘一个技术大佬，一年年薪估计要50万或者上百万。

Optimization Goals

- High Concurrency
  - Metrics
    - Throughput (High throughput)
    - Response Time (Low latency)
    - QPS (Query Per Second)
    - Concurrent Users Number
  - Solutions
    - Scale Up
    - Scale Out
  - Scenarios
    - CPU Intensive (Compute intensive)
    - IO Intensive
- High Performance
  - Factors
    - Resource Utilization
- High Availability
- High Scalability
  - Horizontal Scalability

- Big Data

Optimization Aspects

- Application Architecture
- Concurrency Performance
- Network and Disk IO Performance
- Data Cache and Storage Performance
- JVM Memory Optimization
- Database and SQL Optimization

### DevOps & SRE

  - DevOps Platform
      - [阿里云云效](https://www.aliyun.com/product/yunxiao)
  - Source Control Management
    - GitHub, GitLab
  - Cloud Continuous Integration (CI) Services
    - CircleCI
    - Codeship
    - Travis
    - Wercker
    - GitLab CI
    - GitHub Actions
  - Code Quality Analysis
    - SonarQube
  - CD Tools – Automate the Build
    - Jenkins
    - GitHub Webhooks
    - Script 
      - Bash Shell
      - Python
    - Red Hat Ansible
- Container
  - Docker
  - Kubernates
  - Minikube
  - k3s
  - Helm
- Monitor / Issue Tracking
  - Zabbix
  - Prometheus
  - Jira
  - Slack
- Repo Badges
  - Basic
    - Shields.io (license, maven, issues, starts, forks, pull requests)
  - Continuous Integration
    - Travis (build passing)
  - Code Quality
    - Codacy Grade (code quality)
    - SonarCloud (code smells, coverage, reliability)
  - Test Coverage
    - Codecov.io
  - Security Vulnerability Detection
    - Snyk.io
  - Team Work Analysis
    - Code Climate

### Test

  - UI Test
    - Selenium
    - Robot Framework
    - Protractor
  - Unit Test
    - JUnit
    - TestNG
    - Spock
- Mock Test
  - Mockito
  - PowerMock
- Service/Integration Test
  - JBehave, FitNesse, SoapUI, JMeter Performance Tests
- Performance Test
  - Jmeter

### Common Tools

  - Version Control
    - Git
    - SVN
  - Editor
    - Vim
    - Nano
    - Atom
    - Visual Studio Code
    - Sublime Text
    - Emacs
    - Notepad++
  - Web Browser DevTools
    - Chrome DevTools
    - Firefox Developer Tools
- Database Clients
  - Common
    - Navicat
    - Table Plus
    - Data Grip (auto-complete)
    - DBeaver (Free for basic usage and open source)
    - DB Visualizer
  - For MySQL
    - Navicat for MySQL
    - SQLyog
    - MySQL Workbench (free)
    - phpMyAdmin (free and open source)
    - HeidiSQL (free and open source)

### Java Tools

- Project Build
  - Maven
  - Maven Wrapper
  - Gradle
- Artifact Repository Management
  - Apache Archiva
  - JFrog Artifactory
  - Sonatype Nexus
- IDE
  - IntelliJ IDEA (pronounced "Intelli(gent) J(ava) idea")
  - Eclipse
- JVM Monitor / Application Performance Monitor
  - Java Mission Control (JMC, included in JDK/bin)
  - JConsole (included in JDK/bin). A tool for GC profiling.
  - VisualVM (included in JDK/bin, the VisualGC is a plugin for VisualVM)
  - Alibaba Arthas (open source by Alibaba)
  - Micrometer
  - Stagemonitor
  - Pinpoint
  - GCHisto. An offline GC analysis tool, but now it's unavailable.
- JVM Command-Line Utility
  - jps (included in JDK/bin, obtain jvm Process ID)
  - jstack (included in JDK/bin, obtain Java and native stack information)
  - jmap (included in JDK/bin, obtain memory map information, including a heap histogram)
  - jcmd (included in JDK/bin, to send diagnostic command requests to the JVM)
  - jstat (included in JDK/bin, obtain information about performance and resource consumption)
- JVM Profiling
  - JProfiler (commercial. features: live profiling, offline profiling, view HPROF snapshot)
  - Eclipse Memory Analyzer (MAT, free, to analyze heap dumps)
- Java Development tools
  - Hot Reload / Restart
    - JRebel
    - Spring Boot DevTools
  - Automate code
    - Lombok
    - MyBatis Generator

### Distributed System

Microservices

- Distributed Collaboration (Centralized Service, Service Registration and Discovery, Service Governance)
  - Spring Cloud
  - Apache Zookeeper (/ˈzuːˌkiːpə(r)/)
  - Apache Dubbo (/ˈdʌbəʊ/)
  - Nagios
  - Zabbix
  - Consul
  - Paxos
  - Raft
  - Apache Curator
- Distributed Messaging (Asynchronous Message Queuing)
  - RabbitMQ 
  - Apache Kafka (/ˈkæfkə/) (Logging, Async writing data to RDBMS)
  - Apache ActiveMQ
  - Amazon SQS
- RPC
  - gRPC
  - Apache Thrift

Distributed Data Storage and Search

- Database Cluster (Sharding, High Availability, Compatible with MySQL Protocol)
  - Mycat
  - TiDB
  - alibaba/cobar
- Distributed Database
  - Cassandra
  - Consensus
  - Bigtable
  - HBase
- Distributed Cache
  - Memcached
  - Redis
- Distributed Search Engine
  - Elasticsearch
- Distributed File Systems
  - HDFS
  - IPFS
  - FastDFS
- Big Data
  - Apache Hadoop (/həˈduːp/)

Distributed Computing

- MapReduce
- Kafka Streams
- Apache Spark
- Apache Storm
- Apache Samza
- TensorFlow
- Mesos
- Hadoop

Distributed DevOps

- Container
  - Docker (/ˈdɑːkər/)
  - Kubernates (/k(j)uːbəˈnɛtɪs/)
  - Helm
- Load Balancing
  - HAProxy
  - nginx
  - squid 
  - Keepalived

### Architecture & Design Patterns

  - Design Patterns

### Cloud Computing

  - Types of cloud computing
    - Public cloud
    - Private cloud
    - Hybrid cloud
  - Types of cloud services
    - FaaS (Function as a Service) / Serverless Computing
      - AWS Lambda (Event-driven Serverless Applications)
    - SaaS (Software as a Service)
    - PaaS (Platform as a Service)
    - IaaS (Infrastructure as a Service)
      - OpenStack
      - CloudStack
  - Virtualization
    - KVM/XEN
  - Container

### AI

  - Machine Learning
  - Deep Learning
  - Reinforcement Learning
  - Robotics
  - Computer Vision
  - Natural Language Processing (NLP)
  - Recommender Systems

### Big Data

  - Big Data Engineering
    - Hadoop
    - HDFS
    - Kafka
    - MapReduce
    - Apache Zookeeper
    - Hive
  - Big Data Analytics
    - Apache Storm
    - Apache Spark
    - Apache Kinesis
    - Apache Spark Streaming

### Game Development

### IoT

### Source Code

- Java Fundamentals
  - JDK JUC
  - JDK util (ArrayList, HashMap, LinkedHashMap, LinkedList, HashTable, HashSet)
  - JDK lang (String, Object, StringBuffer, StringBuilder, Integer)
  - HotSpot VM
  - Google Guava
  - Apache Commons
  - JUnit
  - Log4j
- Java Network
  - Netty
  - OkHttp
  - Apache Thrift
- Java Web
  - Tomcat
  - Spring Framework
- Others
  - Lucene
  - Elasticsearch


### References

[1] [A Thorough Introduction to Distributed Systems](https://www.freecodecamp.org/news/a-thorough-introduction-to-distributed-systems-3b91562c9b3c/)

[2] [What is cloud computing? A beginner’s guide](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/)

[3] [Big Data Learning Path for all Engineers and Data Scientists out there](https://www.analyticsvidhya.com/blog/2017/03/big-data-learning-path-for-all-engineers-and-data-scientists-out-there/)

[4] [repo-badges - GitHub](https://github.com/dwyl/repo-badges)

[5] [Hot topics in AI research - Medium](https://towardsdatascience.com/hot-topics-in-ai-research-4367bdd93564)

[6] [Artificial Intelligence - Research Areas - Tutorialspoint](https://www.tutorialspoint.com/artificial_intelligence/artificial_intelligence_research_areas.htm)

[7] [The Most Widely Used Java Libraries](https://www.programcreek.com/2011/08/the-most-widely-used-java-apis/)

[8] [20+ Essential Java Libraries and APIs Every Programmer Should Learn in 2021](https://medium.com/javarevisited/20-essential-java-libraries-and-apis-every-programmer-should-learn-5ccd41812fc7)

--END--

