# MongoDB Interview Questions & Answers

## Questions

| No. | Questions                                                                                                                                                                                                         |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Behavioural Questions**                                                                                                                                                                                         |
| 1   | [What are some of the advantages of MongoDB?](#what-are-some-of-the-advantages-of-mongodb)                                                                                                                        |
| 2   | [When to use MongoDB?](#when-to-use-mongodb)                                                                                                                                                                      |
| 3   | [What are the data types in MongoDB?](#what-are-the-data-types-in-mongodb)                                                                                                                                        |
| 4   | [How to perform queries in MongoDB?](#how-to-perform-queries-in-mongodb)                                                                                                                                          |
| 5   | [How do you Delete a Document?](#how-do-you-delete-a-document)                                                                                                                                                    |
| 6   | [How do you Update a Document?](#how-do-you-update-a-document)                                                                                                                                                    |
| 7   | [How to add data in MongoDB?](#how-to-add-data-in-mongodb)                                                                                                                                                        |
| 8   | [What are some features of MongoDB?](#what-are-some-features-of-mongodb)                                                                                                                                          |
| 9   | [How does Scale-Out occur in MongoDB?](#how-does-scale-out-occur-in-mongodb)                                                                                                                                      |
| 10  | [What is the Mongo Shell?](#what-is-the-mongo-shell)                                                                                                                                                              |
| 11  | [What are Databases in MongoDB?](#what-are-databases-in-mongodb)                                                                                                                                                  |
| 12  | [What is a Collection in MongoDB?](#what-is-a-collection-in-mongodb)                                                                                                                                              |
| 13  | [What is a Document in MongoDB?](#what-is-a-document-in-mongodb)                                                                                                                                                  |
| 14  | [How is Querying done in MongoDB?](#how-is-querying-done-in-mongodb)                                                                                                                                              |
| 15  | [Explain the SET Modifier in MongoDB?](#explain-the-set-modifier-in-mongodb)                                                                                                                                      |
| 16  | [Explain the process of Sharding.](#explain-the-process-of-sharding)                                                                                                                                              |
| 17  | [What are Geospatial Indexes in MongoDB?](#what-are-geospatial-indexes-in-mongodb)                                                                                                                                |
| 18  | [Explain the term “Indexing” in MongoDB.](#explain-the-term-indexing-in-mongodb)                                                                                                                                  |
| 19  | [What do you mean by Transactions?](#what-do-you-mean-by-transactions)                                                                                                                                            |
| 20  | [What are MongoDB Charts?](#what-are-mongodb-charts)                                                                                                                                                              |
| 21  | [What is the Aggregation Framework in MongoDB?](#what-is-the-aggregation-framework-in-mongodb)                                                                                                                    |
| 22  | [Explain the concept of pipeline in the MongoDB aggregation framework.](#explain-the-concept-of-pipeline-in-the-mongodb-aggregation-framework)                                                                    |
| 23  | [What is a Replica Set in MongoDB?](#what-is-a-replica-set-in-mongodb)                                                                                                                                            |
| 24  | [Explain the Replication Architecture in MongoDB.](#explain-the-replication-architecture-in-mongodb)                                                                                                              |
| 25  | [What are some utilities for backup and restore in MongoDB?](#what-are-some-utilities-for-backup-and-restore-in-mongodb)                                                                                          |
| 26  | [What exactly is sharding in MongoDB?](#what-exactly-is-sharding-in-mongodb)                                                                                                                                      |
| 27  | [What factors should be considered in MongoDB’s schema development process?](#what-factors-should-be-considered-in-mongodbs-schema-development-process)                                                           |
| 28  | [What is the composition of ObjectId?](#what-is-the-composition-of-objectid)                                                                                                                                      |
| 29  | [What are indexes in MongoDB?](#what-are-indexes-in-mongodb)                                                                                                                                                      |
| 30  | [What are the multiple languages supported by MongoDB?](#what-are-the-multiple-languages-supported-by-mongodb)                                                                                                    |
| 31  | [What are the data models of MongoDB?](#what-are-the-data-models-of-mongodb)                                                                                                                                      |
| 32  | [What is a profiler's role in MongoDB?](#what-is-a-profilers-role-in-mongodb)                                                                                                                                     |
| 33  | [What is MongoDB and how does it differ from traditional relational databases?](#what-is-mongodb-and-how-does-it-differ-from-traditional-relational-databases)                                                    |
| 34  | [Explain BSON in MongoDB.](#explain-bson-in-mongodb)                                                                                                                                                              |
| 35  | [What is a collection in MongoDB?](#what-is-a-collection-in-mongodb)                                                                                                                                              |
| 36  | [Explain the structure of a MongoDB document.](#explain-the-structure-of-a-mongodb-document)                                                                                                                      |
| 37  | [What is a primary key in MongoDB?](#what-is-a-primary-key-in-mongodb)                                                                                                                                            |
| 38  | [How do you find documents in MongoDB?](#how-do-you-find-documents-in-mongodb)                                                                                                                                    |
| 39  | [What is an index in MongoDB and why is it important?](#what-is-an-index-in-mongodb-and-why-is-it-important)                                                                                                      |
| 40  | [What is the aggregation framework in MongoDB?](#what-is-the-aggregation-framework-in-mongodb)                                                                                                                    |
| 41  | [What is the role of the \_id field in a MongoDB document and can it be customized?](#what-is-the-role-of-the-_id-field-in-a-mongodb-document-and-can-it-be-customized)                                           |
| 42  | [How do you delete documents in MongoDB?](#how-do-you-delete-documents-in-mongodb)                                                                                                                                |
| 43  | [Explain the difference between findOne() and find() in MongoDB.](#explain-the-difference-between-findone-and-find-in-mongodb)                                                                                    |
| 44  | [What is a cursor in MongoDB and how is it used?](#what-is-a-cursor-in-mongodb-and-how-is-it-used)                                                                                                                |
| 45  | [How can you limit the number of documents returned in a MongoDB query?](#how-can-you-limit-the-number-of-documents-returned-in-a-mongodb-query)                                                                  |
| 46  | [What is aggregation in MongoDB and why is it useful?](#what-is-aggregation-in-mongodb-and-why-is-it-useful)                                                                                                      |
| 47  | [How do you perform a case-insensitive search in MongoDB?](#how-do-you-perform-a-case-insensitive-search-in-mongodb)                                                                                              |
| 48  | [What is the $push operator in MongoDB and how does it work?](#what-is-the-push-operator-in-mongodb-and-how-does-it-work)                                                                                         |
| 49  | [Explain the concept of replication in MongoDB.](#explain-the-concept-of-replication-in-mongodb)                                                                                                                  |
| 50  | [What is a capped collection in MongoDB and when would you use it?](#what-is-a-capped-collection-in-mongodb-and-when-would-you-use-it)                                                                            |
| 51  | [Explain the concept of write concern in MongoDB.](#explain-the-concept-of-write-concern-in-mongodb)                                                                                                              |
| 52  | [How do you perform a regular expression-based search in MongoDB?](#how-do-you-perform-a-regular-expression-based-search-in-mongodb)                                                                              |
| 53  | [What is the $addToSet operator in MongoDB and how does it differ from $push?](#what-is-the-addtoset-operator-in-mongodb-and-how-does-it-differ-from-push)                                                        |
| 54  | [How can you drop a collection in MongoDB?](#how-can-you-drop-a-collection-in-mongodb)                                                                                                                            |
| 55  | [What is the default port number for MongoDB and how can you change it?](#what-is-the-default-port-number-for-mongodb-and-how-can-you-change-it)                                                                  |
| 56  | [Explain the difference between the update() and updateOne() methods in MongoDB.](#explain-the-difference-between-the-update-and-updateone-methods-in-mongodb)                                                    |
| 57  | [What is the significance of the ObjectId data type in MongoDB?](#what-is-the-significance-of-the-objectid-data-type-in-mongodb)                                                                                  |
| 58  | [How do you create a backup of a MongoDB database?](#how-do-you-create-a-backup-of-a-mongodb-database)                                                                                                            |
| 59  | [Explain the difference between replica sets and sharding in MongoDB.](#explain-the-difference-between-replica-sets-and-sharding-in-mongodb)                                                                      |
| 60  | [How do you create an index in MongoDB?](#how-do-you-create-an-index-in-mongodb)                                                                                                                                  |
| 61  | [What are the different types of indexes in MongoDB?](#what-are-the-different-types-of-indexes-in-mongodb)                                                                                                        |
| 62  | [How do you perform text searches in MongoDB?](#how-do-you-perform-text-searches-in-mongodb)                                                                                                                      |
| 63  | [Explain the concept of write concern in MongoDB.](#explain-the-concept-of-write-concern-in-mongodb)                                                                                                              |
| 64  | [What is map-reduce in MongoDB and when would you use it?](#what-is-map-reduce-in-mongodb-and-when-would-you-use-it)                                                                                              |
| 65  | [How does MongoDB handle transactions?](#how-does-mongodb-handle-transactions)                                                                                                                                    |
| 66  | [What is the aggregation pipeline in MongoDB and how does it work?](#what-is-the-aggregation-pipeline-in-mongodb-and-how-does-it-work)                                                                            |
| 67  | [What is the role of the MongoDB WiredTiger cache and how does it affect performance?](#what-is-the-role-of-the-mongodb-wiredtiger-cache-and-how-does-it-affect-performance)                                      |
| 68  | [How do you handle schema changes in MongoDB?](#how-do-you-handle-schema-changes-in-mongodb)                                                                                                                      |
| 69  | [What is a compound index and when should you use one?](#what-is-a-compound-index-and-when-should-you-use-one)                                                                                                    |
| 70  | [Explain the concept of read preferences in MongoDB.](#explain-the-concept-of-read-preferences-in-mongodb)                                                                                                        |
| 71  | [How can you improve query performance by using covered queries?](#how-can-you-improve-query-performance-by-using-covered-queries)                                                                                |
| 72  | [What is the purpose of the $lookup stage in the aggregation pipeline?](#what-is-the-purpose-of-the-lookup-stage-in-the-aggregation-pipeline)                                                                     |
| 73  | [How does MongoDB handle duplicate documents and how can you remove them?](#how-does-mongodb-handle-duplicate-documents-and-how-can-you-remove-them)                                                              |
| 74  | [Explain the role of the Oplog in MongoDB replication.](#explain-the-role-of-the-oplog-in-mongodb-replication)                                                                                                    |
| 75  | [How can you secure your MongoDB installation against unauthorized access?](#how-can-you-secure-your-mongodb-installation-against-unauthorized-access)                                                            |
| 76  | [What is the purpose of the mongod process in MongoDB and how do you start it?](#what-is-the-purpose-of-the-mongod-process-in-mongodb-and-how-do-you-start-it)                                                    |
| 77  | [How can you optimize the performance of MongoDB queries with proper indexing?](#how-can-you-optimize-the-performance-of-mongodb-queries-with-proper-indexing)                                                    |
| 78  | [Explain the concept of journaling in MongoDB.](#explain-the-concept-of-journaling-in-mongodb)                                                                                                                    |
| 79  | [What is the difference between a compound index and a multikey index in MongoDB?](#what-is-the-difference-between-a-compound-index-and-a-multikey-index-in-mongodb)                                              |
| 80  | [How do you handle data modeling for a many-to-many relationship in MongoDB?](#how-do-you-handle-data-modeling-for-a-many-to-many-relationship-in-mongodb)                                                        |
| 81  | [How can you set up user authentication for a MongoDB database?](#how-can-you-set-up-user-authentication-for-a-mongodb-database)                                                                                  |
| 82  | [What is the role of the dbStats command in MongoDB?](#what-is-the-role-of-the-dbstats-command-in-mongodb)                                                                                                        |
| 83  | [How does MongoDB ensure data consistency in a replica set?](#how-does-mongodb-ensure-data-consistency-in-a-replica-set)                                                                                          |
| 84  | [What is the use of the $expr operator in MongoDB aggregation?](#what-is-the-use-of-the-expr-operator-in-mongodb-aggregation)                                                                                     |
| 85  | [Explain how to enable auditing in MongoDB.](#explain-how-to-enable-auditing-in-mongodb)                                                                                                                          |
| 86  | [Explain the concept of document validation in MongoDB.](#explain-the-concept-of-document-validation-in-mongodb)                                                                                                  |
| 87  | [What are change streams in MongoDB and how can they be used?](#what-are-change-streams-in-mongodb-and-how-can-they-be-used)                                                                                      |
| 88  | [How do you enable authentication and authorization in MongoDB?](#how-do-you-enable-authentication-and-authorization-in-mongodb)                                                                                  |
| 89  | [What are geospatial indexes and how do they work in MongoDB?](#what-are-geospatial-indexes-and-how-do-they-work-in-mongodb)                                                                                      |
| 90  | [What is the GridFS in MongoDB?](#what-is-the-gridfs-in-mongodb)                                                                                                                                                  |
| 91  | [How does MongoDB handle data consistency in a distributed environment?](#how-does-mongodb-handle-data-consistency-in-a-distributed-environment)                                                                  |
| 92  | [Explain the advantages and disadvantages of using MongoDB as a database for real-time applications.](#explain-the-advantages-and-disadvantages-of-using-mongodb-as-a-database-for-real-time-applications)        |
| 93  | [How can you achieve data encryption at rest in MongoDB?](#how-can-you-achieve-data-encryption-at-rest-in-mongodb)                                                                                                |
| 94  | [What is a covered query in MongoDB?](#what-is-a-covered-query-in-mongodb)                                                                                                                                        |
| 95  | [What is the significance of the explain method in MongoDB queries?](#what-is-the-significance-of-the-explain-method-in-mongodb-queries)                                                                          |
| 96  | [What is MongoDB?](#what-is-mongodb)                                                                                                                                                                              |
| 97  | [What are the features of MongoDB?](#what-are-the-features-of-mongodb)                                                                                                                                            |
| 98  | [What type of NoSQL database is MongoDB?](#what-type-of-nosql-database-is-mongodb)                                                                                                                                |
| 99  | [Explain Namespace?](#explain-namespace)                                                                                                                                                                          |
| 100 | [Differentiate MongoDB and MySQL?](#differentiate-mongodb-and-mysql)                                                                                                                                              |
| 101 | [Explain Indexes in MongoDB?](#explain-indexes-in-mongodb)                                                                                                                                                        |
| 102 | [Why is MongoDB the best NoSQL database?](#why-is-mongodb-the-best-nosql-database)                                                                                                                                |
| 103 | [Explain the significance of the covered query?](#explain-the-significance-of-the-covered-query)                                                                                                                  |
| 104 | [What is a replica set?](#what-is-a-replica-set)                                                                                                                                                                  |
| 105 | [Differentiate MongoDB and Cassandra?](#differentiate-mongodb-and-cassandra)                                                                                                                                      |
| 106 | [Explain the primary and secondary replica set?](#explain-the-primary-and-secondary-replica-set)                                                                                                                  |
| 107 | [Which languages can we use with MongoDB?](#which-languages-can-we-use-with-mongodb)                                                                                                                              |
| 108 | [Explain Storage Encryption?](#explain-storage-encryption)                                                                                                                                                        |
| 109 | [Explain Primary and Secondary Replica Sets?](#explain-primary-and-secondary-replica-sets)                                                                                                                        |
| 110 | [What is the importance of GridFS and Journaling?](#what-is-the-importance-of-gridfs-and-journaling)                                                                                                              |
| 111 | [How to do locking or transactions in MongoDB?](#how-to-do-locking-or-transactions-in-mongodb)                                                                                                                    |
| 112 | [How to do Journaling in MongoDB?](#how-to-do-journaling-in-mongodb)                                                                                                                                              |
| 113 | [How does MongoDB provide concurrency?](#how-does-mongodb-provide-concurrency)                                                                                                                                    |
| 114 | [Explain Sharding and Aggregation in MongoDB?](#explain-sharding-and-aggregation-in-mongodb)                                                                                                                      |
| 115 | [What is the importance of the profiler in MongoDB?](#what-is-the-importance-of-the-profiler-in-mongodb)                                                                                                          |
| 116 | [Define Collection?](#define-collection)                                                                                                                                                                          |
| 117 | [Explain Aggregation Pipeline?](#explain-aggregation-pipeline)                                                                                                                                                    |
| 118 | [Explain MapReduce?](#explain-mapreduce)                                                                                                                                                                          |
| 119 | [Explain Splitting?](#explain-splitting)                                                                                                                                                                          |
| 120 | [What is the purpose of the save() method?](#what-is-the-purpose-of-the-save-method)                                                                                                                              |
| 121 | [What is the use of MongoDB?](#what-is-the-use-of-mongodb)                                                                                                                                                        |
| 122 | [What is the purpose of the DB command?](#what-is-the-purpose-of-the-db-command)                                                                                                                                  |
| 123 | [What are the restrictions of the MongoDB 32-bit versions?](#what-are-the-restrictions-of-the-mongodb-32-bit-versions)                                                                                            |
| 124 | [When should we normalize the data in MongoDB?](#when-should-we-normalize-the-data-in-mongodb)                                                                                                                    |
| 125 | [How do we perform sorting and Explain Project in MongoDB?](#how-do-we-perform-sorting-and-explain-project-in-mongodb)                                                                                            |
| 126 | [How can MongoDB simulate subquery or join?](#how-can-mongodb-simulate-subquery-or-join)                                                                                                                          |
| 128 | [Define oplog (operational log)?](#define-oplog-operational-log)                                                                                                                                                  |
| 129 | [How do we create a database in MongoDB?](#how-do-we-create-a-database-in-mongodb)                                                                                                                                |
| 130 | [What is the syntax of the skip() method?](#what-is-the-syntax-of-the-skip-method)                                                                                                                                |
| 131 | [How do we delete everything from the MongoDB database?](#how-do-we-delete-everything-from-the-mongodb-database)                                                                                                  |
| 132 | [Which command do we use for creating the backup of the database?](#which-command-do-we-use-for-creating-the-backup-of-the-database)                                                                              |
| 133 | [Which command do we use for restoring the backup?](#which-command-do-we-use-for-restoring-the-backup)                                                                                                            |
| 134 | [Explain the importance of the dot notation?](#explain-the-importance-of-the-dot-notation)                                                                                                                        |
| 135 | [What is the syntax of the limit() and sort() method?](#what-is-the-syntax-of-the-limit-and-sort-method)                                                                                                          |
| 136 | [What do you know about NoSQL databases? What are the various types of NoSQL databases?](#what-do-you-know-about-nosql-databases-what-are-the-various-types-of-nosql-databases)                                   |
| 137 | [Which command do we use for dropping a database?](#which-command-do-we-use-for-dropping-a-database)                                                                                                              |
| 138 | [Explain MongoDB Projection?](#explain-mongodb-projection)                                                                                                                                                        |
| 139 | [Why do we use the pretty() method?](#why-do-we-use-the-pretty-method)                                                                                                                                            |
| 140 | [How do we remove a document from the collection?](#how-do-we-remove-a-document-from-the-collection)                                                                                                              |
| 141 | [What are the points we should consider while creating a schema in MongoDB?](#what-are-the-points-we-should-consider-while-creating-a-schema-in-mongodb)                                                          |
| 142 | [What does ObjectId contain?](#what-does-objectid-contain)                                                                                                                                                        |
| 143 | [How do we use the select \* group by MongoDB aggregation?](#how-do-we-use-the-select-group-by-mongodb-aggregation)                                                                                               |
| 144 | [Explain Vertical Scaling and Horizontal Scaling?](#explain-vertical-scaling-and-horizontal-scaling)                                                                                                              |
| 145 | [What are the elements of the Sharded Cluster?](#what-are-the-elements-of-the-sharded-cluster)                                                                                                                    |
| 146 | [What are the substitutes for MongoDB?](#what-are-the-substitutes-for-mongodb)                                                                                                                                    |
| 147 | [How can we handle old files in the moveChunk directory?](#how-can-we-handle-old-files-in-the-movechunk-directory)                                                                                                |
| 148 | [What is a Storage Engine?](#what-is-a-storage-engine)                                                                                                                                                            |
| 149 | [Does MongoDB require plenty of RAM?](#does-mongodb-require-plenty-of-ram)                                                                                                                                        |
| 150 | [Differentiate MongoDB and CouchDB?](#differentiate-mongodb-and-couchdb)                                                                                                                                          |
| 151 | [Explain Capped Collection?](#explain-capped-collection)                                                                                                                                                          |
| 152 | [How do we perform the Join operations in MongoDB?](#how-do-we-perform-the-join-operations-in-mongodb)                                                                                                            |
| 153 | [What are the storage engines used by MongoDB?](#what-are-the-storage-engines-used-by-mongodb)                                                                                                                    |
| 154 | [How do we configure the cache size in MongoDB?](#how-do-we-configure-the-cache-size-in-mongodb)                                                                                                                  |
| 155 | [How do we control the MongoDB Performance?](#how-do-we-control-the-mongodb-performance)                                                                                                                          |
| 156 | [What are the aggregate functions of MongoDB?](#what-are-the-aggregate-functions-of-mongodb)                                                                                                                      |
| 157 | [What are the CRUD operations of MongoDB?](#what-are-the-crud-operations-of-mongodb)                                                                                                                              |
| 158 | [What are the datatypes of MongoDB?](#what-are-the-datatypes-of-mongodb)                                                                                                                                          |
| 159 | [Is it required to invoke “get last error” for making a write durable?](#is-it-required-to-invoke-get-last-error-for-making-a-write-durable)                                                                      |
| 160 | [What happens when the Shard is slow or down while querying?](#what-happens-when-the-shard-is-slow-or-down-while-querying)                                                                                        |
| 161 | [How do we use a primary key in MongoDB?](#how-do-we-use-a-primary-key-in-mongodb)                                                                                                                                |
| 162 | [How do we see the connections utilized by MongoDB?](#how-do-we-see-the-connections-utilized-by-mongodb)                                                                                                          |
| 163 | [When a “moveChunk” fails, is it required to clean up partly moved docs?](#when-a-movechunk-fails-is-it-required-to-clean-up-partly-moved-docs)                                                                   |
| 164 | [Explain how to start the MongoDB Instance or Server?](#explain-how-to-start-the-mongodb-instance-or-server)                                                                                                      |
| 165 | [Differences between MongoDB and RDBMS?](#differences-between-mongodb-and-rdbms)                                                                                                                                  |
| 166 | [How do applications access the real-time data modifications in MongoDB?](#how-do-applications-access-the-real-time-data-modifications-in-mongodb)                                                                |
| 167 | [What are the different kinds of Indexes in MongoDB?](#what-are-the-different-kinds-of-indexes-in-mongodb)                                                                                                        |
| 168 | [Define BSON?](#define-bson)                                                                                                                                                                                      |
| 169 | [How does MongoDB store the data?](#how-does-mongodb-store-the-data)                                                                                                                                              |
| 170 | [Does MongoDB support ACID Transaction? Define ACID Transaction?](#does-mongodb-support-acid-transaction-define-acid-transaction)                                                                                 |
| 171 | [Explain Composing elements or Structure of ObjectID in MongoDB?](#explain-composing-elements-or-structure-of-objectid-in-mongodb)                                                                                |
| 172 | [How do we find array elements with multiple criteria?](#how-do-we-find-array-elements-with-multiple-criteria)                                                                                                    |
| 173 | [How can we sort the user-defined function?](#how-can-we-sort-the-user-defined-function)                                                                                                                          |
| 174 | [To what extent does the data expand to multi-slice?](#to-what-extent-does-the-data-expand-to-multi-slice)                                                                                                        |
| 175 | [How do we retrieve MongoDB databases in Javascript Array?](#how-do-we-retrieve-mongodb-databases-in-javascript-array)                                                                                            |
| 176 | [How do we update the object in the Nested Array?](#how-do-we-update-the-object-in-the-nested-array)                                                                                                              |
| 177 | [How do we retrieve a particular embedded document in a MongoDB collection?](#how-do-we-retrieve-a-particular-embedded-document-in-a-mongodb-collection)                                                          |
| 178 | [How do we query a nested Join?](#how-do-we-query-a-nested-join)                                                                                                                                                  |
| 179 | [Can we run more than one Javascript Operation in one MongoDB instance?](#can-we-run-more-than-one-javascript-operation-in-one-mongodb-instance)                                                                  |
| 180 | [What do you understand by NoSQL databases? Is MongoDB a NoSQL database? explain?](#what-do-you-understand-by-nosql-databases-is-mongodb-a-nosql-database-explain)                                                |
| 181 | [Which are the different languages supported by MongoDB?](#which-are-the-different-languages-supported-by-mongodb)                                                                                                |
| 182 | [What are the different types of NoSQL databases? Give some example.](#what-are-the-different-types-of-nosql-databases-give-some-example)                                                                         |
| 183 | [Is MongoDB better than other SQL databases? If yes then how?](#is-mongodb-better-than-other-sql-databases-if-yes-then-how)                                                                                       |
| 184 | [What type of DBMS is MongoDB?](#what-type-of-dbms-is-mongodb)                                                                                                                                                    |
| 185 | [What is the difference between MongoDB and MySQL?](#what-is-the-difference-between-mongodb-and-mysql)                                                                                                            |
| 186 | [Why MongoDB is known as best NoSQL database?](#why-mongodb-is-known-as-best-nosql-database)                                                                                                                      |
| 187 | [Does MongoDB support primary-key, foreign-key relationship?](#does-mongodb-support-primary-key-foreign-key-relationship)                                                                                         |
| 188 | [Can you achieve primary key - foreign key relationships in MongoDB?](#can-you-achieve-primary-key-foreign-key-relationships-in-mongodb)                                                                          |
| 189 | [Does MongoDB need a lot of RAM?](#does-mongodb-need-a-lot-of-ram)                                                                                                                                                |
| 190 | [Explain the structure of ObjectID in MongoDB.](#explain-the-structure-of-objectid-in-mongodb)                                                                                                                    |
| 191 | [Is it true that MongoDB uses BSON to represent document structure?](#is-it-true-that-mongodb-uses-bson-to-represent-document-structure)                                                                          |
| 192 | [What are Indexes in MongoDB?](#what-are-indexes-in-mongodb)                                                                                                                                                      |
| 193 | [By default, which index is created by MongoDB for every collection?](#by-default-which-index-is-created-by-mongodb-for-every-collection)                                                                         |
| 194 | [What is a Namespace in MongoDB?](#what-is-a-namespace-in-mongodb)                                                                                                                                                |
| 195 | [Can journaling features be used to perform safe hot backups?](#can-journaling-features-be-used-to-perform-safe-hot-backups)                                                                                      |
| 196 | [Why does Profiler use in MongoDB?](#why-does-profiler-use-in-mongodb)                                                                                                                                            |
| 197 | [If you remove an object attribute, is it deleted from the database?](#if-you-remove-an-object-attribute-is-it-deleted-from-the-database)                                                                         |
| 198 | [In which language MongoDB is written?](#in-which-language-mongodb-is-written)                                                                                                                                    |
| 199 | [Does MongoDB need a lot space of Random Access Memory (RAM)?](#does-mongodb-need-a-lot-space-of-random-access-memory-ram)                                                                                        |
| 200 | [What language you can use with MongoDB?](#what-language-you-can-use-with-mongodb)                                                                                                                                |
| 201 | [Does MongoDB database have tables for storing records?](#does-mongodb-database-have-tables-for-storing-records)                                                                                                  |
| 202 | [Do the MongoDB databases have schema?](#do-the-mongodb-databases-have-schema)                                                                                                                                    |
| 204 | [What is the method to configure the cache size in MongoDB?](#what-is-the-method-to-configure-the-cache-size-in-mongodb)                                                                                          |
| 205 | [How to do Transaction/locking in MongoDB?](#how-to-do-transaction-locking-in-mongodb)                                                                                                                            |
| 206 | [Why 32 bit version of MongoDB are not preferred?](#why-32-bit-version-of-mongodb-are-not-preferred)                                                                                                              |
| 207 | [Is it possible to remove old files in the moveChunk directory?](#is-it-possible-to-remove-old-files-in-the-movechunk-directory)                                                                                  |
| 208 | [What will have to do if a shard is down or slow and you do a query?](#what-will-have-to-do-if-a-shard-is-down-or-slow-and-you-do-a-query)                                                                        |
| 209 | [Explain the covered query in MongoDB.](#explain-the-covered-query-in-mongodb)                                                                                                                                    |
| 210 | [What is the importance of covered query?](#what-is-the-importance-of-covered-query)                                                                                                                              |
| 211 | [What is sharding in MongoDB?](#what-is-sharding-in-mongodb)                                                                                                                                                      |
| 212 | [What is replica set in MongoDB?](#what-is-replica-set-in-mongodb)                                                                                                                                                |
| 213 | [What is primary and secondary replica set in MongoDB?](#what-is-primary-and-secondary-replica-set-in-mongodb)                                                                                                    |
| 214 | [By default, which replica sets are used to write data?](#by-default-which-replica-sets-are-used-to-write-data)                                                                                                   |
| 215 | [What is CRUD in MongoDB?](#what-is-crud-in-mongodb)                                                                                                                                                              |
| 216 | [In which format MongoDB represents document structure?](#in-which-format-mongodb-represents-document-structure)                                                                                                  |
| 217 | [What will happen when you remove a document from database in MongoDB? Does MongoDB remove it from disk?](#what-will-happen-when-you-remove-a-document-from-database-in-mongodb-does-mongodb-remove-it-from-disk) |
| 218 | [Why are MongoDB data files large in size?](#why-are-mongodb-data-files-large-in-size)                                                                                                                            |
| 219 | [What is a storage engine in MongoDB?](#what-is-a-storage-engine-in-mongodb)                                                                                                                                      |
| 220 | [Which are the storage engines used by MongoDB?](#which-are-the-storage-engines-used-by-mongodb)                                                                                                                  |
| 221 | [What is the usage of profiler in MongoDB?](#what-is-the-usage-of-profiler-in-mongodb)                                                                                                                            |
| 222 | [Is it possible to configure the cache size for MMAPv1 in MongoDB?](#is-it-possible-to-configure-the-cache-size-for-mmapv1-in-mongodb)                                                                            |
| 223 | [How to configure the cache size for WiredTiger in MongoDB?](#how-to-configure-the-cache-size-for-wiredtiger-in-mongodb)                                                                                          |
| 224 | [How does MongoDB provide concurrency?](#how-does-mongodb-provide-concurrency)                                                                                                                                    |
| 225 | [What is the difference between MongoDB and Redis database?](#what-is-the-difference-between-mongodb-and-redis-database)                                                                                          |
| 226 | [What is the difference between MongoDB and CouchDB?](#what-is-the-difference-between-mongodb-and-couchdb)                                                                                                        |
| 227 | [What is the difference between MongoDB and Cassandra?](#what-is-the-difference-between-mongodb-and-cassandra)                                                                                                    |
| 228 | [Is there any need to create database command in MongoDB?](#is-there-any-need-to-create-database-command-in-mongodb)                                                                                              |

1. ### What are some of the advantages of MongoDB?

Some advantages of MongoDB are as follows:

- MongoDB supports field, range-based, string pattern matching type queries. for searching the data in the database
- MongoDB support primary and secondary index on any fields
- MongoDB basically uses JavaScript objects in place of procedures
- MongoDB uses a dynamic database schema
- MongoDB is very easy to scale up or down
- MongoDB has inbuilt support for data partitioning (Sharding).

**[⬆ Back to Top](#questions)**

2. ### When to use MongoDB?

You should use MongoDB when you are building internet and business applications that need to evolve quickly and scale elegantly. MongoDB is popular with developers of all kinds who are building scalable applications using agile methodologies.
MongoDB is a great choice if one needs to:

- Support a rapid iterative development.
- Scale to high levels of read and write traffic - MongoDB supports horizontal scaling through Sharding, distributing data across several machines, and facilitating high throughput operations with large sets of data.
- Scale your data repository to a massive size.
- Evolve the type of deployment as the business changes.
- Store, manage and search data with text, geospatial, or time-series dimensions.

**[⬆ Back to Top](#questions)**

3. ### What are the data types in MongoDB?

MongoDB supports a wide range of data types as values in documents. Documents in MongoDB are similar to objects in JavaScript. Along with JSON’s essential key/value–pair nature, MongoDB adds support for a number of additional data types. The common data types in MongoDB are:

- Null

```bash
{"x" : null}
```

- Boolean

```bash
{"x" : true}
```

- Number

```bash
{"x" : 4}
```

- String

```bash
{"x" : "foobar"}
```

- Date

```bash
{"x" : new Date()}
```

- Regular expression

```bash
{"x" : /foobar/i}
```

- Array

```bash
{"x" : ["a", "b", "c"]}
```

- Embedded document

```bash
{"x" : {"foo" : "bar"}}
```

- Object ID

```bash
{"x" : ObjectId()}
```

- Binary Data
  Binary data is a string of arbitrary bytes.
- Code

```bash
{"x" : function() { /* ... */ }}
```

**[⬆ Back to Top](#questions)**

4. ### How to perform queries in MongoDB?

The `find` method is used to perform queries in MongoDB. Querying returns a subset of documents in a collection, from no documents at all to the entire collection. Which documents get returned is determined by the first argument to find, which is a document specifying the query criteria.

Example:

```bash
> db.users.find({"age" : 24})
```

**[⬆ Back to Top](#questions)**

5. ### How do you Delete a Document?

The CRUD API in MongoDB provides deleteOne and deleteMany for this purpose. Both of these methods take a filter document as their first parameter. The filter specifies a set of criteria to match against in removing documents.

For example:

```bash
> db.books.deleteOne({"_id" : 3})
```

**[⬆ Back to Top](#questions)**

6. ### How do you Update a Document?

Once a document is stored in the database, it can be changed using one of several update methods: updateOne, updateMany, and replaceOne. updateOne and updateMany each takes a filter document as their first parameter and a modifier document, which describes changes to make, as the second parameter. replaceOne also takes a filter as the first parameter, but as the second parameter replaceOne expects a document with which it will replace the document matching the filter.

For example, in order to replace a document:

```bash
{
   "_id" : ObjectId("4b2b9f67a1f631733d917a7a"),
   "name" : "alice",
   "friends" : 24,
   "enemies" : 2
}
```

**[⬆ Back to Top](#questions)**

7. ### How to add data in MongoDB?

The basic method for adding data to MongoDB is “inserts”. To insert a single document, use the collection’s insertOne method:

```bash
> db.books.insertOne({"title" : "Start With Why"})
```

**[⬆ Back to Top](#questions)**

8. ### What are some features of MongoDB?

- Indexing: It supports generic secondary indexes and provides unique, compound, geospatial, and full-text indexing capabilities as well.
- Aggregation: It provides an aggregation framework based on the concept of data processing pipelines.
- Special collection and index types: It supports time-to-live (TTL) collections for data that should expire at a certain time
- File storage: It supports an easy-to-use protocol for storing large files and file metadata.
- Sharding: Sharding is the process of splitting data up across machines.

**[⬆ Back to Top](#questions)**

9. ### How does Scale-Out occur in MongoDB?

The document-oriented data model of MongoDB makes it easier to split data across multiple servers. Balancing and loading data across a cluster is done by MongoDB. It then redistributes documents automatically.

The mongos acts as a query router, providing an interface between client applications and the sharded cluster.

Config servers store metadata and configuration settings for the cluster. MongoDB uses the config servers to manage distributed locks. Each sharded cluster must have its own config servers.

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/202/original/Mongos.jpg?1616050215" alt="Alt Text" width="650" height="500" />

**[⬆ Back to Top](#questions)**

1.  ### What is the Mongo Shell?

It is a JavaScript shell that allows interaction with a MongoDB instance from the command line. With that one can perform administrative functions, inspecting an instance, or exploring MongoDB.

To start the shell, run the mongo executable:

```cmd
$ mongod
$ mongo
MongoDB shell version: 4.2.0
connecting to: test
>
```

The shell is a full-featured JavaScript interpreter, capable of running arbitrary JavaScript programs. Let’s see how basic math works on this:

```cmd
> x = 100;
200
> x / 5;
20
```

**[⬆ Back to Top](#questions)**

11. ### What are Databases in MongoDB?

MongoDB groups collections into databases. MongoDB can host several databases, each grouping together collections.
Some reserved database names are as follows:
admin
local
config

**[⬆ Back to Top](#questions)**

12. ### What is a Collection in MongoDB?

A collection in MongoDB is a group of documents. If a document is the MongoDB analog of a row in a relational database, then a collection can be thought of as the analog to a table.
Documents within a single collection can have any number of different “shapes.”, i.e. collections have dynamic schemas.
For example, both of the following documents could be stored in a single collection:

```bash
{"greeting" : "Hello world!", "views": 3}
{"signoff": "Good bye"}
```

**[⬆ Back to Top](#questions)**

13. ### What is a Document in MongoDB?

A Document in MongoDB is an ordered set of keys with associated values. It is represented by a map, hash, or dictionary. In JavaScript, documents are represented as objects:

```bash
{"greeting" : "Hello world!"}
```

Complex documents will contain multiple key/value pairs:

```bash
{"greeting" : "Hello world!", "views" : 3}
```

**[⬆ Back to Top](#questions)**

14. ### How is Querying done in MongoDB?

The `find` method is used to perform queries in MongoDB. Querying returns a subset of documents in a collection, from no documents at all to the entire collection. Which documents get returned is determined by the first argument to find, which is a document specifying the query criteria.

For example: If we have a string we want to match, such as a "username" key with the value "alice", we use that key/value pair instead:

```bash
> db.users.find({"username" : "alice"})
```

**[⬆ Back to Top](#questions)**

15. ### Explain the SET Modifier in MongoDB?

If the value of a field does not yet exist, the "$set" sets the value. This can be useful for updating schemas or adding user-defined keys.

Example:

```javascript
> db.users.findOne()
{
   "_id" : ObjectId("4b253b067525f35f94b60a31"),
   "name" : "alice",
   "age" : 23,
   "sex" : "female",
   "location" : "India"
}
```

To add a field to this, we use “$set”:

```javascript
> db.users.updateOne({"_id" :
ObjectId("4b253b067525f35f94b60a31")},
... {"$set" : {"favorite book" : "Start with Why"}})
```

**[⬆ Back to Top](#questions)**

16. ### Explain the process of Sharding.

Sharding is the process of splitting data up across machines. We also use the term “partitioning” sometimes to describe this concept. We can store more data and handle more load without requiring larger or more powerful machines, by putting a subset of data on each machine.
In the figure below, RS0 and RS1 are shards. MongoDB’s sharding allows you to create a cluster of many machines (shards) and break up a collection across them, putting a subset of data on each shard. This allows your application to grow beyond the resource limits of a standalone server or replica set.

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/204/original/sharded_client_connection.jpg?1616054864" alt="Alt Text" width="650" height="500" />

Sharded Client Connection

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/206/original/Non_sharded_client_connection.jpg?1616054947" alt="Alt Text" width="400" height="300" />

Non Sharded Client Connection

**[⬆ Back to Top](#questions)**

1.  ### What are Geospatial Indexes in MongoDB?

MongoDB has two types of geospatial indexes: 2dsphere and 2d. 2dsphere indexes work with spherical geometries that model the surface of the earth based on the WGS84 datum. This datum model the surface of the earth as an oblate spheroid, meaning that there is some flattening at the poles. Distance calculations using 2sphere indexes, therefore, take the shape of the earth into account and provide a more accurate treatment of distance between, for example, two cities, than do 2d indexes. Use 2d indexes for points stored on a two-dimensional plane.

2dsphere allows you to specify geometries for points, lines, and polygons in the GeoJSON format. A point is given by a two-element array, representing [longitude, latitude]:

```cmd
{
   "name" : "New York City",
   "loc" : {
       "type" : "Point",
       "coordinates" : [50, 2]
   }
}
```

A line is given by an array of points:

```cmd
{
   "name" : "Hudson River",
   "loc" : {
       "type" : "LineString",
       "coordinates" : [[0,1], [0,2], [1,2]]
   }
}
```

**[⬆ Back to Top](#questions)**

18. ### Explain the term “Indexing” in MongoDB.

In MongoDB, indexes help in efficiently resolving queries. What an Index does is that it stores a small part of the data set in a form that is easy to traverse. The index stores the value of the specific field or set of fields, ordered by the value of the field as specified in the index.
MongoDB’s indexes work almost identically to typical relational database indexes.

Indexes look at an ordered list with references to the content. These in turn allow MongoDB to query orders of magnitude faster. To create an index, use the `createIndex` collection method.

For example:

```javascript
> db.users.find({"username": "user101"}).explain("executionStats")
```

Here, `executionStats` mode helps us understand the effect of using an index to satisfy queries.

**[⬆ Back to Top](#questions)**

19. ### What do you mean by Transactions?

A transaction is a logical unit of processing in a database that includes one or more database operations, which can be read or write operations. Transactions provide a useful feature in MongoDB to ensure consistency.

MongoDB provides two APIs to use transactions.

- **Core API**: It is a similar syntax to relational databases (e.g., start_transaction and commit_transaction)
- **Call-back API**: This is the recommended approach to using transactions. It starts a transaction, executes the specified operations, and commits (or aborts on the error). It also automatically incorporates error handling logic for "TransientTransactionError" and"UnknownTransactionCommitResult".

**[⬆ Back to Top](#questions)**

20. ### What are MongoDB Charts?

MongoDB Charts is a new, integrated tool in MongoDB for data visualization.

MongoDB Charts offers the best way to create visualizations using data from a MongoDB database.
It allows users to perform quick data representation from a database without writing code in a programming language such as Java or Python.

The two different implementations of MongoDB Charts are:

- MongoDB Charts PaaS (Platform as a Service)
- MongoDB Charts Server

**[⬆ Back to Top](#questions)**

21. ### What is the Aggregation Framework in MongoDB?

- The aggregation framework is a set of analytics tools within MongoDB that allow you to do analytics on documents in one or more collections.
- The aggregation framework is based on the concept of a pipeline. With an aggregation pipeline, we take input from a MongoDB collection and pass the documents from that collection through one or more stages, each of which performs a different operation on its inputs (See figure below). Each stage takes as input whatever the stage before it produced as output. The inputs and outputs for all stages are documents—a stream of documents.

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/208/original/aggregation-framework.jpg?1616058137" alt="Alt Text" width="650" height="400" />

**[⬆ Back to Top](#questions)**

22. ### Explain the concept of pipeline in the MongoDB aggregation framework

An individual stage of an aggregation pipeline is a data processing unit. It takes in a stream of input documents one at a time, processes each document one at a time, and produces an output stream of documents one at a time (see figure below).

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/209/original/mongodb_aggregation_pipeline.jpg?1616058315" alt="Alt Text" width="650" height="400" />

**[⬆ Back to Top](#questions)**

23. ### What is a Replica Set in MongoDB?

To keep identical copies of your data on multiple servers, we use replication. It is recommended for all production deployments. Use replication to keep your application running and your data safe, even if something happens to one or more of your servers.

Such replication can be created by a replica set with MongoDB. A replica set is a group of servers with one primary, the server taking writes, and multiple secondaries, servers that keep copies of the primary’s data. If the primary crashes, the secondaries can elect a new primary from amongst themselves.

24. ### Explain the Replication Architecture in MongoDB.

The following diagram depicts the architecture diagram of a simple replica set cluster with only three server nodes – one primary node and two secondary nodes:

<img src="https://s3.ap-south-1.amazonaws.com/myinterviewtrainer-domestic/public_assets/assets/000/000/210/original/replication_architecture.jpg?1616058517" alt="Alt Text" width="650" height="400" />

- In the preceding model, the PRIMARY database is the only active replica set member that receives write operations from database clients. The PRIMARY database saves data changes in the Oplog. Changes saved in the Oplog are sequential—that is, saved in the order that they are received and executed.
- The SECONDARY database is querying the PRIMARY database for new changes in the Oplog. If there are any changes, then Oplog entries are copied from PRIMARY to SECONDARY as soon as they are created on the PRIMARY node.
- Then, the SECONDARY database applies changes from the Oplog to its own datafiles. Oplog entries are applied in the same order they were inserted in the log. As a result, datafiles on SECONDARY are kept in sync with changes on PRIMARY.
- Usually, SECONDARY databases copy data changes directly from PRIMARY. Sometimes a SECONDARY database can replicate data from another SECONDARY. This type of replication is called Chained Replication because it is a two-step replication process. Chained replication is useful in certain replication topologies, and it is enabled by default in MongoDB.

**[⬆ Back to Top](#questions)**

25. ### What are some utilities for backup and restore in MongoDB?

The mongo shell does not include functions for exporting, importing, backup, or restore. However, MongoDB has created methods for accomplishing this, so that no scripting work or complex GUIs are needed. For this, several utility scripts are provided that can be used to get data in or out of the database in bulk. These utility scripts are:

- mongoimport
- mongoexport
- mongodump
- mongorestore
- **[⬆ Back to Top](#questions)**

26. ### What exactly is sharding in MongoDB?

Sharding is the process of storing data records across many devices. It is a MongoDB strategy to meet data growth demands. It refers to the horizontal division of material in a database or search engine. Each partition is known as a shard or database shard.

**[⬆ Back to Top](#questions)**

27. ### What factors should be considered in MongoDB’s schema development process?

While developing a schema, one must consider the following:

Create your schema according to user needs.
If you use many objects together, combine them into a single document. Separate them if necessary.
In the schema, perform sophisticated aggregation.

**[⬆ Back to Top](#questions)**

28. ### What is the composition of Objecld?

Objectld is composed of the following:

Timestamp
Client machine ID
Client process ID
3 byte incremented counter

**[⬆ Back to Top](#questions)**

29. ### What are indexes in MongoDB?

Indexes are special structures in MongoDB that hold a subset of the data set in an easy-to-search format. The index maintains the value of a given field or collection of fields, ordered by the value of the field provided in the index.

**[⬆ Back to Top](#questions)**

30. ### What are the multiple languages supported by MongoDB?

MongoDB officially supports the following languages: C, C++, C#, Java, Node.js, Perl, PHP, Python, Ruby, Scala, Go, and Erlang. We can use MongoDB with any of the languages mentioned above. There are several other community-supported drivers available, but MongoDB provides the ones described above.

**[⬆ Back to Top](#questions)**

31. ### What are the data models of MongoDB?

There are two types of data models in MongoDB. They are embedded and normalized data models. The structure of documents has an impact on data modeling. In MongoDB, related data can be incorporated into a single document structure (embedded data model). The relationship between data is stored through references from one document to another. It's known as the normalized data model.

**[⬆ Back to Top](#questions)**

32. ### What is a profiler's role in MongoDB?

MongoDB includes a database profiler that displays information about the performance of each database activity. You can use this profiler to discover queries (and write operations) that are taking longer than they should and use that information to determine when an index is required.

**[⬆ Back to Top](#questions)**

33. ### What is MongoDB and how does it differ from traditional relational databases?

MongoDB is a NoSQL, document-oriented database that stores data in a flexible, JSON-like format called BSON (binary JSON). Unlike traditional relational databases, it does not require a predefined schema, allowing for dynamic and hierarchical data storage. It is also designed to scale horizontally, making it suitable for handling large volumes of unstructured or semi-structured data.

**[⬆ Back to Top](#questions)**

34. ### Explain BSON in MongoDB.

BSON, short for Binary JSON, is a binary-encoded serialization format that MongoDB utilizes to store documents in collections and facilitate data exchange. While it is similar to JSON in terms

One of the key extensions BSON offers over JSON is the support for additional data types. For instance, whereas JSON only supports text and numbers directly, BSON introduces types like Date, Binary data (such as images or encrypted content), and ObjectId (used for unique document identifiers), among others. These extended data types are critical for applications that require the storage of complex and varied data structures.

Furthermore, BSON's binary nature significantly enhances MongoDB's performance. The storage and retrieval of data are optimized, allowing for faster access to documents. This is particularly beneficial in environments where rapid processing of large volumes of data is essential.

**[⬆ Back to Top](#questions)**

35. ### What is a collection in MongoDB?

In MongoDB, a collection represents a grouping of MongoDB documents that are typically related to each other in some way. Analogous to a table in a traditional relational database management system, collections serve as the primary organizational structure for data in MongoDB. However, unlike tables in relational databases, collections in MongoDB offer a high degree of flexibility due to their lack of a fixed schema.

This schema-less nature means that within a single collection, documents can have different fields. For example, one document in a collection could contain ten fields, while another document in the same collection might contain only five fields or might contain a completely different set of fields. This flexibility allows developers to work with more varied data structures and to iterate more rapidly on their applications without needing to modify a rigid database schema each time the data structure changes.

**[⬆ Back to Top](#questions)**

36. ### Explain the structure of a MongoDB document.

A MongoDB document is structured as a BSON (Binary JSON) object, which is a binary representation of JSON-like documents. Like JSON, BSON supports the embedding of key-value pairs but with some extensions. Each key in a document is a field name, and the value associated with that key can be of various data types such as string, integer, boolean, array, another document (object), or even a BSON-specific type like ObjectId, Date, and Binary data.

One of the powerful features of MongoDB documents is the ability to nest documents within documents. This structure allows for a highly flexible and hierarchical organization of data, which can be particularly useful for representing complex relationships and data models.

**[⬆ Back to Top](#questions)**

37. ### What is a primary key in MongoDB?

In MongoDB, the primary key serves as a unique identifier for each document within a collection, ensuring the distinguishability of each document. Unlike some databases where you may need to explicitly define the primary key, MongoDB automatically generates an "\_id" field for each document if it is not provided. This "\_id" field is indexed, guaranteeing quick data retrieval using the primary key.

The default "\_id" field uses ObjectId, a 12-byte BSON type, combining the timestamp, machine identifier, process ID, and a sequence number to ensure uniqueness across a distributed system. This design choice caters to scalability and fast generation of unique identifiers in distributed environments.

Although MongoDB automatically generates an "\_id" field, developers have the flexibility to assign custom values to this field, provided they uphold the uniqueness constraint. This allows the integration of MongoDB into systems with existing identification schemes or the use of more domain-specific identifiers.

**[⬆ Back to Top](#questions)**

38. ### How do you find documents in MongoDB?

Finding documents in MongoDB is primarily achieved through the find() method, a versatile and powerful function that allows for both simple and complex queries against the documents in a collection.

For a simple use case, to retrieve all documents in a collection, you execute db.collectionName.find({}). This command queries without any filter, denoted by the empty braces {}, and returns all documents within collectionName.

**[⬆ Back to Top](#questions)**

39. ### What is an index in MongoDB and why is it important?

An index in MongoDB is a data structure that improves the speed of data retrieval operations on a collection. It works similarly to an index in a book, allowing MongoDB to quickly locate and access specific data without scanning the entire collection. Indexes are crucial for optimizing query performance.

**[⬆ Back to Top](#questions)**

40. ### What is the aggregation framework in MongoDB?

The aggregation framework in MongoDB is an advanced, functional feature designed to process data and aggregate information from documents within a collection. This feature leverages a staged, pipeline model which allows you to transform and combine data in multiple steps, each building upon the last, to achieve complex data processing and aggregation results.

**[⬆ Back to Top](#questions)**

41. ### What is the role of the \_id field in a MongoDB document and can it be customized?

The "\_id" field is the primary key in a MongoDB document that uniquely identifies each document within a collection. While MongoDB auto-generates "\_id" values, you can also customize this field if you need specific values or want to use a different field as the primary key.

**[⬆ Back to Top](#questions)**

42. ### How do you delete documents in MongoDB?

You can delete documents in MongoDB using the deleteOne() or deleteMany() methods, depending on whether you want to delete a single document or multiple documents that match specific criteria.

**[⬆ Back to Top](#questions)**

43. ### Explain the difference between findOne() and find() in MongoDB.

In MongoDB, both findOne() and find() methods are used to retrieve documents from a collection, but they differ in their operation, return types, and intended use cases.

**findOne():**

The findOne() method searches for the first document that matches the query criteria and returns it as a single document object. This method is particularly useful when you are looking for a specific document or know that your query criteria match a unique document in the collection.
If findOne() does not find any matching document, it returns null, indicating that no document meets the search criteria.
Given its nature of returning a single document, findOne() is suited for queries where you expect a single result, such as retrieving a user profile based on a unique username or ID.

**find():**

Conversely, the find() method retrieves all documents that match the query criteria and returns a cursor to these documents. This cursor is an iterable object that lazily fetches the documents in batches as you iterate over it. This method is ideal for queries where multiple documents may meet the criteria, and you wish to process or display these documents.
If find() finds no matching documents, it returns an empty cursor, effectively behaving as if querying an empty collection.
Since find() returns a cursor, it is commonly used with cursor methods like .limit(), .sort(), and .toArray() to refine the results, manage large sets of results, and convert the results to an array, respectively.

**[⬆ Back to Top](#questions)**

44. ### What is a cursor in MongoDB and how is it used?

In MongoDB, a cursor is a powerful concept and tool that serves as an iterator to navigate through the results of a query. When a find() operation executes, instead of immediately returning all matched documents, MongoDB provides a cursor to these results. This cursor points to the query results in a manner that allows for efficient retrieval and manipulation of data, one document at a time or in batches.

Cursors are particularly useful for handling large datasets that might be too memory-intensive to load and process all at once. With cursors, MongoDB fetches documents in manageable batches, reducing the load on both the database and application memory.

**[⬆ Back to Top](#questions)**

45. ### How can you limit the number of documents returned in a MongoDB query?

In MongoDB, controlling the number of documents returned by a query is straightforward and efficient with the use of the limit() method. This method takes an integer value as an argument, which specifies the maximum number of documents that should be returned from a query. It’s particularly useful in scenarios where you need to paginate results or simply prevent overloading your application with too much data at once.

**Syntax:**

db.collection.find(query).limit(number)

Here,

- db.collection is the path to your collection.
- find(query) is your search criteria. If you want all documents, you can use an empty object {}.
- limit(number) specifies the maximum number of documents to return.

**[⬆ Back to Top](#questions)**

46. ### What is aggregation in MongoDB and why is it useful?

Aggregation in MongoDB is a robust process designed for data analysis and transformation within collections. It involves consolidating data from multiple documents to perform complex groupings, calculations, and generate aggregated results. This capability is essential for transforming document-shaped data structures into a summarized form, making it easier to understand trends, patterns, and anomalies in your data.

The aggregation framework in MongoDB operates through a pipeline mechanism, where data passes through multiple stages of transformation. Each stage in the pipeline processes the data as it flows through, performing operations such as filtering, grouping, sorting, and combining data, as well as other sophisticated calculations and data transformations. This pipeline architecture not only ensures flexibility in how operations are composed but also efficiency in processing large volumes of data.

**Why Aggregation is Useful:**

**Data Summarization:** Aggregation is invaluable for summarizing data, such as calculating sums, averages, and other statistical measures across large datasets. For instance, businesses might use aggregation to aggregate sales data to find total sales per region or to calculate average sales per product.

**Transforming Data:** It allows for the transformation of data into a structure that is more conducive to the specific requirements of an application or analysis. This could involve reshaping data, enriching documents with computed fields, or filtering out unnecessary data.

**Complex Analytics:** The aggregation framework enables complex analytical operations that can rival those of traditional relational databases. This includes the ability to join documents, perform cross-collection queries, and create complex hierarchical data structures.

**Performance Optimization:** By leveraging the aggregation pipeline, MongoDB can optimize query performance, especially when operating on indexes and when processing is distributed across multiple nodes in a cluster. This makes aggregation an efficient choice even for data-intensive operations.

**[⬆ Back to Top](#questions)**

47. ### How do you perform a case-insensitive search in MongoDB?

To perform a case-insensitive search, use regular expressions with the $regex operator and set the $options to "i", indicating case-insensitive matching. For example,

`db.collectionName.find({ field: { $regex: "searchTerm", $options: "i" } }).`

**[⬆ Back to Top](#questions)**

48. ### What is the $push operator in MongoDB and how does it work?

The $push operator in MongoDB is used to add elements to an array field within a document. It appends the specified value(s) to the array. For example:

`db.collectionName.update({ _id: ObjectId("documentId") }, { $push: { fieldName: valueToPush } }).`

**[⬆ Back to Top](#questions)**

49. ### Explain the concept of replication in MongoDB.

Replication in MongoDB is a method used to ensure the robustness and reliability of data by creating multiple copies of that data across different database servers or instances, collectively known as replicas. The primary mechanism through which MongoDB achieves replication is through a configuration called a replica set.

A replica set is a group of MongoDB servers that maintain the same data set, providing redundancy and high fault tolerance. Within a replica set, one server takes the role of the primary node, and the remaining servers are designated as secondary nodes. The primary node receives all write operations. Meanwhile, the secondary nodes replicate the data from the primary node and can serve read operations, thereby distributing the data access load and ensuring the system's scalability and performance.

**[⬆ Back to Top](#questions)**

50. ### What is a capped collection in MongoDB and when would you use it?

Capped Collections in MongoDB represent a special type of data storage with a fixed size. Once the allocated space is filled, the collection behaves like a circular buffer, automatically overwriting the oldest documents with new ones. This functionality is intrinsic to capped collections and does not require any additional data management logic in your application code.

Capped collections are particularly suited for scenarios where data volume management and retrieval speed are critical, but where historical data has diminishing value over time. Common applications include

- **Logging:** Ideal for log data where only recent entries are of interest. Capped collections can efficiently store logs by automatically purging the oldest entries, thus maintaining a manageable dataset size.
- **Caching:** Serve as a simple, performance-optimized caching mechanism where older entries naturally make way for newer ones once the collection reaches its size limit.
- **Real-time Analytics and Monitoring:** Useful for storing data points for recent activities, allowing for efficient queries on recent data for dashboarding or monitoring purposes.

**[⬆ Back to Top](#questions)**

51. ### Explain the concept of write concern in MongoDB.

Write Concern in MongoDB is a critical feature that enables clients to customize the level of assurance and acknowledgment they receive for write operations (inserts, updates, deletions) to the database. It’s a mechanism that allows the tuning of consistency and durability guarantees against the performance overhead inherent in distributed systems.

Write concern can be configured at different levels, including per-operation, per-connection, or as a default setting for the database. Here's an example of specifying a write concern for an insert operation:

```javascript
db.collection.insert(
  { item: 'product', qty: 100 },
  { writeConcern: { w: 'majority', j: true, wtimeout: 5000 } }
);
```

**[⬆ Back to Top](#questions)**

52. ### How do you perform a regular expression-based search in MongoDB?

You can use the $regex operator in MongoDB to perform regular expression-based searches. For example:

**db.collectionName.find({ field: { $regex: /pattern/ } }).**

**[⬆ Back to Top](#questions)**

53. ### What is the `$addToSet` operator in MongoDB and how does it differ from `$push`?

The $addToSet operator is utilized to add a value to an array field within a document, but only if the value does not already exist in the array, thereby preventing duplicate entries. This behavior ensures that the array remains a set, where each element is unique. It is particularly useful when maintaining lists that require uniqueness, such as tags, categories, or permissions.

**[⬆ Back to Top](#questions)**

54. ### How can you drop a collection in MongoDB?

You can drop a collection in MongoDB using the drop() method. For example:

**db.collectionName.drop().**

**[⬆ Back to Top](#questions)**

55. ### What is the default port number for MongoDB and how can you change it?

The default port number for MongoDB is 27017. You can change it by specifying a different port number in the MongoDB configuration file or using the **--port** option when starting the MongoDB server.

**[⬆ Back to Top](#questions)**

56. ### Explain the difference between the update() and updateOne() methods in MongoDB.

In MongoDB, updating documents is a common operation, and understanding the distinction between the update() and updateOne() methods is crucial for optimizing database interactions and ensuring the intended outcomes of update operations.

**update() Method:**

- The update() method is designed to update multiple documents within a collection that match the given query criteria. By default, without specifying any additional options, update() will only modify the first document that matches the criteria.

- To update all documents that match the criteria, you must explicitly set the { multi: true } option in the update call. This is an essential distinction because failing to set this option when intending to update multiple documents can lead to unexpected results.

**updateOne() Method:**

- On the other hand, updateOne() targets a more specific use case. This method updates only the first document that matches the specified criteria and then stops, regardless of how many documents actually match.
- updateOne() is inherently designed to be precise, ensuring that only a single document is modified during an operation. There is no need to specify a { multi: true } option because the method's behavior is to update a single document by design.

**[⬆ Back to Top](#questions)**

57. ### What is the significance of the ObjectId data type in MongoDB?

ObjectId is a BSON data type used extensively in MongoDB as a primary key for documents, known as the \_id field. It's designed to have a high probability of being unique across collections and even across different MongoDB clusters. Understanding its structure and significance is crucial for database modeling, data retrieval, and system design in MongoDB applications. An ObjectId is a 12-byte BSON type, ensuring a compact and efficient representation.

**Significance of ObjectId data type:**

- Uniqueness: The structure of ObjectIds ensures a high probability of uniqueness across documents, collections, and databases, mitigating the risk of collisions.
- Efficient Indexing: ObjectIds are automatically indexed, making retrieval operations using the \_id field fast and efficient.
- Implicit Time Ordering: The timestamp component enables users to derive the creation time of a document directly from its \_id, offering a helpful, built-in temporal sorting or filtering mechanism without additional fields or indexes.
- Scalability and Distributed Nature: Given its components (machine and process identifiers), the ObjectId generation process is well-suited for distributed environments, allowing various machines and processes to generate ids concurrently without central coordination

**[⬆ Back to Top](#questions)**

58. ### How do you create a backup of a MongoDB database?

You can create a backup of a MongoDB database using tools like **mongodump** or by taking file system-level backups. **mongodump** is a built-in MongoDB tool that creates a binary export of the database that can be restored using **mongorestore**.
File system-level backups involve copying the entire database directory while the database is in a consistent state.

**[⬆ Back to Top](#questions)**

59. ### Explain the difference between replica sets and sharding in MongoDB.

Replica sets are used for high availability and data redundancy. They consist of multiple MongoDB instances (nodes) where one node is the primary and others are secondary. Data is replicated from the primary to the secondary to ensure data durability and availability.

In contrast, sharding is used to horizontally partition data across multiple servers or shards. Each shard is essentially a separate MongoDB instance and data is distributed across these shards based on a shard key. Sharding helps to scale out the capacity and throughput of a MongoDB cluster while replica sets provide fault tolerance and data redundancy.

**[⬆ Back to Top](#questions)**

60. ### How do you create an index in MongoDB?

To create an index in MongoDB, use the **createIndex()** method. For example, to create a single-field ascending index on a collection called **myCollection** for a field named **myField**, you can run the following command in the MongoDB shell:

db.myCollection.createIndex({ myField: 1 })

**[⬆ Back to Top](#questions)**

61. ### What are the different types of indexes in MongoDB?

MongoDB supports various types of indexes, including:

- Single-field index: Index on a single field.
- Compound index: Index on multiple fields.
- Text index: Special index for text-based search.
- Geospatial index: Index for geospatial data.
- Hashed index: Index that hashes the indexed field's values.
- Wildcard index: Indexes arrays of objects with dynamic keys.
- TTL (time-to-live) index: Index that expires documents after a specified time.

**[⬆ Back to Top](#questions)**

62. ### How do you perform text searches in MongoDB?

MongoDB provides text search capabilities using the $text operator and text indexes. To perform a text search, you need to:

- Create a text index on one or more fields in your collection.
- Use the $text operator in your query to specify the search terms and the indexed fields to search against.
- Execute the query.

**For example:**

```shell
db.myCollection.createIndex({ content: "text" }) db.myCollection.find({ $text: { $search: "keyword" } })
```

**[⬆ Back to Top](#questions)**

63. ### Explain the concept of write concern in MongoDB.

Write concern in MongoDB determines the level of acknowledgment requested from MongoDB when performing write operations (e.g., insert, update, delete). It specifies how many replica nodes must acknowledge the write before MongoDB considers it successful. Write concern levels include:

- Unacknowledged: MongoDB doesn't wait for acknowledgment.
- Acknowledged: MongoDB waits for acknowledgment from the primary node.
- Majority: MongoDB waits for acknowledgment from the majority of replica set members, ensuring data durability.

Choosing the appropriate write concern level balances performance and data safety based on your application's needs.

**[⬆ Back to Top](#questions)**

64. ### What is map-reduce in MongoDB and when would you use it?

Map-reduce is a data processing paradigm used in MongoDB to perform complex data transformations and aggregations. It involves two main stages:

- Map: In this stage, you define a JavaScript function (the map function) that processes each document in a collection and emits key-value pairs as output.
- Reduce: In this stage, you define another JavaScript function (the reduce function) that takes the emitted key-value pairs from the map stage and performs further aggregation or calculations.
- Map-reduce is used when you need to perform operations that are not easily achievable using the aggregation framework or other query methods. It's particularly useful for batch processing and complex data analysis tasks.v

**[⬆ Back to Top](#questions)**

65. ### How does MongoDB handle transactions?

MongoDB introduced multi-document transactions in version 4.0. Transactions allow you to perform multiple operations on multiple documents within one or more collections in an all-or-nothing manner, ensuring data consistency.

To use transactions in MongoDB, you need to start a session and explicitly start a transaction within that session using the **startSession()** method. You can then execute multiple operations within the transaction. If all operations succeed, you commit the transaction using **commitTransaction()**. If any operation fails, you can roll back the entire transaction using **abortTransaction()**.

**[⬆ Back to Top](#questions)**

66. ### What is the aggregation pipeline in MongoDB and how does it work?

The aggregation pipeline is a powerful feature for data transformation and aggregation in MongoDB. It consists of a sequence of stages, where each stage performs a specific operation on the input documents and passes the results to the next stage. Stages can include `$match`, `$group`, `$sort`, `$project`, and more.

Documents flow through the pipeline, and at each stage, you can apply various operations to filter, reshape, group, and aggregate data. The output of one stage becomes the input for the next stage. This allows for complex data processing without the need to write custom JavaScript functions like in map-reduce.

**[⬆ Back to Top](#questions)**

67. ### What is the role of the MongoDB WiredTiger cache and how does it affect performance?

WiredTiger has been the default storage engine for MongoDB since version 3.2. It includes a cache mechanism that stores frequently used data and indexes in memory. This cache, known as the WiredTiger cache, significantly improves read performance by reducing disk I/O.

The size of the WiredTiger cache can greatly impact performance. If the cache is too small, MongoDB may need to read data from disk frequently, which can slow down operations. If it's too large, it can lead to memory contention issues.

**[⬆ Back to Top](#questions)**

68. ### How do you handle schema changes in MongoDB?

MongoDB is schema-flexible, which means you can change the structure of documents in a collection without affecting existing documents. However, you may need to handle schema changes in your application code to accommodate new fields or data structures.

Strategies for handling schema changes include:

- Use versioning: Add version numbers to your documents to identify their schema and write code that can handle documents with different versions.
- Migrate data: For significant schema changes, consider data migration scripts to update existing documents to the new schema.
- Use schema validation: Starting from MongoDB 3.6, you can enforce a schema using JSON Schema validation.

**[⬆ Back to Top](#questions)**

69. ### What is a compound index and when should you use one?

A compound index in MongoDB involves indexing multiple fields together. You should use a compound index when your queries involve multiple fields in the **filter, sort, or projection** stages.

Compound indexes are efficient for queries that filter on multiple criteria or perform sorting on multiple fields. They can significantly improve query performance for such use cases.

**[⬆ Back to Top](#questions)**

70. ### Explain the concept of read preferences in MongoDB.

Read preferences in MongoDB determine from which members of a replica set a client can read data. MongoDB provides several read preference modes including:

- Primary: Reads are only permitted from the primary node for maximum consistency.
- primaryPreferred: Reads from the primary are preferred, but if it's unavailable, reads from secondary nodes are allowed.
- Secondary: Reads are only allowed from secondary nodes for load balancing or read scaling.
- secondaryPreferred: Reads from secondary nodes are preferred, but if none are available, a primary is acceptable.
- Nearest: Reads from the nearest replica set member based on network latency.

**[⬆ Back to Top](#questions)**

71. ### How can you improve query performance by using covered queries?

Covered queries are highly performant because they retrieve data directly from indexes without needing to access the actual documents. To improve query performance using covered queries, follow these steps:

- Create appropriate indexes that cover the query fields.
- Ensure that the query only requests the fields that are part of the index.
- Execute the query using projection to limit the retrieved fields to those specified in the index.
  This reduces the amount of data that needs to be read from disk and transferred over the network, resulting in faster query execution.

**[⬆ Back to Top](#questions)**

72. ### What is the purpose of the $lookup stage in the aggregation pipeline?

The **$lookup** stage in the aggregation pipeline allows you to perform a left outer join between documents from two collections. It's useful when you need to combine data from multiple collections based on a common field.

The **$lookup** stage can merge documents from the source collection with documents from a target collection, creating a new document that combines fields from both collections.

**[⬆ Back to Top](#questions)**

73. ### How does MongoDB handle duplicate documents and how can you remove them?

MongoDB does not enforce unique constraints on documents by default. However, you can manually handle duplicate documents by using the **unique** index constraint on one or more fields. To remove duplicates, follow these steps:

Create a unique index on the field(s) where you want to enforce uniqueness.
Use the **deleteMany()** method with a query to delete duplicate documents.
You can also use aggregation to identify and remove duplicates by grouping documents based on the unique field(s) and selecting one document from each group to keep.

**[⬆ Back to Top](#questions)**

74. ### Explain the role of the Oplog in MongoDB replication.

The Oplog (short for "operations log") is a special capped collection in MongoDB that records all write operations that modify data in a replica set's primary node. It serves as a replication mechanism, allowing secondary nodes to replicate changes from the primary. Secondary nodes continually tail the Oplog to stay up-to-date with the primary data.

**[⬆ Back to Top](#questions)**

75. ### How can you secure your MongoDB installation against unauthorized access?

To secure a MongoDB installation, you can take several measures:

- Enable authentication and create user roles with appropriate permissions.
- Configure network security by binding MongoDB to specific IP addresses and using firewalls.
- Enable SSL/TLS encryption for data in transit.
- Implement access control and authorization using role-based access control (RBAC).
- Regularly update MongoDB to the latest secure version to patch known vulnerabilities.
- Use strong, unique passwords for MongoDB users.
- Limit physical access to MongoDB servers.

**[⬆ Back to Top](#questions)**

76. ### What is the purpose of the mongod process in MongoDB and how do you start it?

The **mongod** process is the primary daemon that runs the MongoDB server. It's responsible for handling database operations, managing data storage, and serving client requests. To start the **mongod** process, you typically run it from the command line with options specifying the configuration file, data directory, and other settings.

**For example:**
mongod --config /etc/mongod.conf

The **mongod** process listens for incoming client connections on the default port 27017.

**[⬆ Back to Top](#questions)**

77. ### How can you optimize the performance of MongoDB queries with proper indexing?

To optimize query performance in MongoDB, you should:

Create indexes on fields used in query filters and sorting.
Use the **$hint** operator to specify which index to use, if necessary.
Avoid unnecessary indexes that consume resources.
Monitor and analyze query performance using tools like the **explain** method.
Keep indexes compact and well-maintained to avoid performance degradation.

**[⬆ Back to Top](#questions)**

78. ### Explain the concept of journaling in MongoDB.

Journaling in MongoDB is a feature that ensures data durability and recoverability in the event of unexpected server crashes or power failures. MongoDB maintains a write-ahead log (WAL) or journal on disk.

Before a write operation is considered committed, it must be written to both memory and the journal. This allows MongoDB to recover uncommitted data from the journal in case of a crash, ensuring that no data is lost.

**[⬆ Back to Top](#questions)**

79. ### What is the difference between a compound index and a multikey index in MongoDB?

**Compound index:** A compound index in MongoDB involves indexing multiple fields together within a single document. It's used to improve query performance for queries that filter or sort on multiple fields together. It's created by specifying multiple fields in a single index definition.

**Multikey index:** A multikey index, on the other hand, is used to index arrays of values within a single field. It allows you to index multiple values within an array, creating separate index entries for each element in the array. Multikey indexes are used for queries that involve array fields, enabling efficient querying of documents based on elements within arrays.

**[⬆ Back to Top](#questions)**

80. ### How do you handle data modeling for a many-to-many relationship in MongoDB?

In MongoDB, you can model a many-to-many relationship using either the **embedded** or **referenced** approach:

**Embedded:** In this approach, you embed an array of references to documents from one collection within documents in another collection. This approach is suitable when the number of referenced documents is relatively small and doesn't frequently change.

**Referenced:** In this approach, you create separate collections for each entity in the many-to-many relationship and use references (usually \_id values) to link documents across collections. This approach is more suitable when the many-to-many relationship involves a large number of documents or when the relationships are dynamic.

**[⬆ Back to Top](#questions)**

81. ### How can you set up user authentication for a MongoDB database?

To set up user authentication in MongoDB, follow these steps:

Start the **mongod** process with the **--auth** option to enable authentication.
Create an admin user who has privileges to manage users and roles.
Create additional users with specific roles and permissions for your databases.
Configure authentication mechanisms such as SCRAM-SHA-1 or x.509 certificates.
Restart MongoDB with authentication enabled.
Connect to MongoDB using the **mongo** shell with the **-u** and **-p** options to provide authentication credentials.

**[⬆ Back to Top](#questions)**

82. ### What is the role of the dbStats command in MongoDB?

The **dbStats** command in MongoDB provides statistics about a specific database including information about its storage utilization, the number of objects (documents and indexes), average object size, and more. It's useful for monitoring database health and performance. Running **db.stats()** in the **mongo** shell returns a JSON document with these statistics.

**[⬆ Back to Top](#questions)**

83. ### How does MongoDB ensure data consistency in a replica set?

MongoDB ensures data consistency in a replica set through a process known as **replication**. When a write operation occurs on the primary node, it's recorded in the primary's Oplog (operations log). Secondary nodes continuously replicate these write operations by applying them in the same order as they occurred on the primary. This process ensures that secondary nodes eventually become consistent with the primary.

MongoDB uses a consensus algorithm to ensure that write operations are acknowledged only when a majority of nodes in the replica set have successfully replicated the data. This guarantees data consistency and durability.

**[⬆ Back to Top](#questions)**

84. ### What is the use of the $expr operator in MongoDB aggregation?

The `$expr` operator in MongoDB aggregation allows you to use aggregation expressions within a `$match` stage. This is useful when you need to perform complex comparisons or operations on fields that involve aggregation functions, variables, or other expressions. The `$expr` operator lets you evaluate expressions and filter documents based on the results.

**[⬆ Back to Top](#questions)**

85. ### Explain how to enable auditing in MongoDB.

To enable auditing in MongoDB and track database activities, follow these steps:

Start MongoDB with the **--auditDestination** option to specify where audit logs should be written (e.g., to a file or syslog).
Configure the level of auditing by setting the **auditFormat** and **auditFilter** options in the MongoDB configuration file.
Optionally, define specific auditing rules to track particular events or operations.
Restart MongoDB to apply the auditing settings.
MongoDB will now generate audit logs based on the configured settings, recording various database activities.

**[⬆ Back to Top](#questions)**

86. ### Explain the concept of document validation in MongoDB.

Document validation in MongoDB represents a powerful feature to enforce data quality and integrity directly at the database level. By defining a set of rules and criteria that documents must adhere to before they can be inserted or updated within a collection, MongoDB ensures that only data which fits the established schema and business logic is allowed. This proactive approach to data management helps in reducing errors and inconsistencies, promoting a robust and reliable data store.

Validation rules in MongoDB are expressed using the JSON schema standard, a collaborative and open specification for defining the structure, content, and constraints of JSON documents. This schema is applied at the collection level, and it can be configured to trigger during insert and update operations, including bulk operations.

**[⬆ Back to Top](#questions)**

87. ### What are change streams in MongoDB and how can they be used?

Change streams in MongoDB are a powerful feature enabling applications to access real-time data changes without the complexity of polling or other less efficient mechanisms. Built on the robust replication capabilities of MongoDB, change streams leverage the oplog (operations log) — a special capped collection that records all operations affecting the database's data. By opening a change stream, applications can receive a live feed of data changes, with the ability to filter and pinpoint exactly the types of changes they're interested in.

To initiate a change stream, use the watch() method on a collection, database, or deployment level. This method returns a cursor that applications can iterate over to retrieve change events in real time. You can specify filters as part of the watch() method to narrow down the events you are interested in, such as changes to specific documents or changes of specific types (e.g., updates only).

**[⬆ Back to Top](#questions)**

88. ### How do you enable authentication and authorization in MongoDB?

Authentication in MongoDB is a security measure designed to confirm the identity of users or applications attempting access. It's the first line of defense, ensuring that only known and authorized entities can connect to your MongoDB environment. Here's how you can enable and configure authentication:

**Choose an Authentication Mechanism:** MongoDB supports several authentication mechanisms, including SCRAM (Salted Challenge Response Authentication Mechanism), x.509 certificate authentication, and LDAP (Lightweight Directory Access Protocol). The choice depends on your security requirements and infrastructure setup.

- SCRAM: The default and most commonly used mechanism, providing password-based authentication.
- x.509 Certificate Authentication: Utilizes client certificates to authenticate, offering a higher security standard suitable for environments with stringent compliance requirements.
- LDAP: Integrates MongoDB authentication with existing LDAP-based authentication systems, simplifying user management in large organizations.

**Configure the MongoDB Server:** To enable authentication, edit the MongoDB configuration file (mongod.conf) to include the security section with authentication enabled:

security:

authorization: "enabled"

For x.509 certificate authentication, additional configuration to specify the CA file and enabling SSL/TLS might be required.

**Restart MongoDB:** With the changes made, restart the MongoDB instance to apply the new security configurations.

**Setting Up Authorization:**

MongoDB manages authorization through Role-Based Access Control (RBAC), allowing fine-grained control over the actions that authenticated users or applications can perform. Here’s how to establish authorization:

- Pre-defined Roles: MongoDB comes with a set of built-in roles suitable for common use cases, such as read, readWrite, and dbAdmin, among others. These roles can be directly assigned to users.
- Create Custom Roles: For more specific control, you can create custom roles with precisely defined privileges. This involves specifying the resources (databases, collections) and the actions (insert, find, delete) the role can perform.
- Assign Roles to Users: Once roles are defined, they can be assigned to users. Roles can be assigned globally or scoped to specific databases, providing flexibility in how access controls are applied.

**[⬆ Back to Top](#questions)**

89. ### What are geospatial indexes and how do they work in MongoDB?

Geospatial indexes are a specialized type of index in MongoDB designed to efficiently query data based on geographical locations. By indexing geospatial data, such as coordinates or shapes, MongoDB can perform complex geospatial queries that would otherwise be computationally intensive and time-consuming.

When a geospatial index is created on a collection, MongoDB uses special data structures to store the indexed geospatial data efficiently. These indexes allow MongoDB to quickly prune the search space when performing queries, such as locating all points within a specific distance from a given location or finding all locations within a polygonal area.

**[⬆ Back to Top](#questions)**

90. ### What is the GridFS in MongoDB?

GridFS stands as MongoDB's answer to overcoming the BSON document size limit, currently set at 16MB. Designed to store and efficiently retrieve large binary files such as images, video files, audio files, and PDFs, GridFS ensures that operations on large files are not only possible but also optimized for performance.

GridFS achieves its functionality by splitting files into smaller parts, known as "chunks," and storing each chunk as a separate document. This chunking mechanism allows GridFS to handle files much larger than the BSON document size limit by avoiding the need to load entire files into memory for operations, thereby significantly reducing memory usage and enhancing performance.

**[⬆ Back to Top](#questions)**

91. ### How does MongoDB handle data consistency in a distributed environment?

MongoDB employs a sophisticated architecture designed to balance data consistency, availability, and partition tolerance - the three vertices of the CAP theorem. In distributed systems, these principles guide the design and operational behavior, with data consistency being paramount for ensuring that all clients view the same data, despite the inherent challenges of network partitions and node failures.

**[⬆ Back to Top](#questions)**

92. ### Explain the advantages and disadvantages of using MongoDB as a database for real-time applications.

**Advantages of using MongDB as a database:**

- Flexible Schema Design: MongoDB doesn't enforce a rigid schema, unlike traditional relational databases. This flexibility allows developers to store documents in a collection with varied structures, making it simpler to iterate on the development as application requirements evolve.
- Horizontal Scalability: It is built with scalability in mind. MongoDB can handle increasing loads by adding more servers (sharding), making it suitable for applications expecting significant growth.
- Geospatial Support: MongoDB provides comprehensive support for geospatial queries and indexing, enabling the development of location-based services with ease.
- Real-Time Capabilities: With features like Change Streams, MongoDB can push real-time updates to the application when data changes in the database. This is particularly useful for applications requiring immediate data freshness like live content updates, monitoring dashboards, etc.

**Disadvantages of using MongDB as a database:**

- Schema Design Considerations: While flexibility is an advantage, it also requires developers to be more mindful of their collection schema design to ensure efficiency and performance. Improper schema design can lead to increased complexity and degraded performance as the application scales.
- Complexity in Transactions: While MongoDB added support for multi-document transactions in version 4.0, handling transactions across multiple documents or collections can introduce additional complexity compared with traditional ACID transactions in SQL databases.
- Learning Curve: For those accustomed to SQL databases, the transition to MongoDB's document model and understanding best practices for schema design, indexing, and querying can present a learning curve.

**[⬆ Back to Top](#questions)**

93. ### How can you achieve data encryption at rest in MongoDB?

Data encryption at rest is essential for safeguarding sensitive data by ensuring it is unreadable if unauthorized access to the physical storage is gained. MongoDB supports various methods to achieve this, catering to diverse security requirements and deployment scenarios.

Using the Underlying File System or Hardware:

- Self-Encrypting Drives (SEDs): These are hard drives that automatically and transparently encrypt data as it is written onto the disk and decrypt data when read from the disk. SEDs manage encryption keys internally and can be a straightforward, performant option for encryption at rest.

- File-Level Encryption: This involves encrypting files at the file system level using tools or features provided by the operating system, such as EFS (Encrypting File System) in Windows or dm-crypt in Linux. This method allows for granular control over which files are encrypted and can be used with MongoDB without requiring any specific configuration in the database itself.

**[⬆ Back to Top](#questions)**

94. ### What is a covered query in MongoDB?

A covered query in MongoDB is a query where all the fields needed for the query are present in an index. In other words, MongoDB can satisfy the query solely by scanning the index and doesn't need to access the actual documents in the collection. Covered queries are highly efficient because they minimize disk I/O and can significantly improve query performance.

**[⬆ Back to Top](#questions)**

95. ### What is the significance of the explain method in MongoDB queries?

The explain method in MongoDB provides information about how MongoDB executes a query. It offers insights into the query execution plan, index usage, and the number of documents examined.

By analyzing the output of the explain method, you can optimize query performance by ensuring that the appropriate indexes are used and identifying potential bottlenecks in query execution.

**[⬆ Back to Top](#questions)**

96. ### What is MongoDB?

MongoDB is a cross-platform document-based database. Categorized as a NoSQL database, MongoDB avoids the conventional table-oriented relational database structure in support of the JSON-like documents with the dynamic schemas, making the data integration in specific kinds of applications quicker and simpler.

MongoDB was developed by a software company “10gen”, in October 2007 as an element of the planned platform as the service product. After that, the company was shifted to a freeware deployment model in 2009, providing sales assistance and other services.

**[⬆ Back to Top](#questions)**

97. ### What are the features of MongoDB?

Following are the important features of MongoDB:

- A compliant data model in the format of documents.
- Agile and extremely scalable database.
- Quicker than traditional databases.
- Demonstrative query language.

**[⬆ Back to Top](#questions)**

98. ### What type of NoSQL database is MongoDB?

MongoDB is a document-oriented database. It stores the data in the form of the BSON structure-oriented databases. We store these documents in a collection.

**[⬆ Back to Top](#questions)**

99. ### Explain Namespace?

A namespace is the series of the collection name and database name.

**[⬆ Back to Top](#questions)**

100. ### Differentiate MongoDB and MySQL?

Despite MySQL and MongoDB being freeware and open source databases, there are several differences between them in terms of a data relationship, transaction, performance speed, querying data, schema design, normalization, etc. The comparison between MongoDB and MySQL is similar to the comparison between Non-relational and Relational databases.

**[⬆ Back to Top](#questions)**

101. ### Explain Indexes in MongoDB?

In MongoDB, we use Indexes for executing the queries efficiently; without using Indexes, MongoDB should carry out a collection scan, i.e., scan all the documents of a collection, for selecting the documents which match the query statement. If a suitable index is available for a query, MongoDB will use an index for restricting the number of documents it should examine.

**[⬆ Back to Top](#questions)**

102. ### Why is MongoDB the best NoSQL database?

MongoDB is the best NoSQL database due to the following features:

- High Performance
- High Availability
- Easily Scalable
- Rich Query Language
- Document Oriented

**[⬆ Back to Top](#questions)**

103. ### Explain the significance of the covered query?

A covered query makes the query implementation quicker as we store the indexes in the RAM or consecutively located on the disk. It makes query execution quicker. The covered query covers all the fields in the index, MongoDB matches the query condition along with returning the result fields.

**[⬆ Back to Top](#questions)**

104. ### What is a replica set?

We can specify the replica as a set of the mongo instances which host a similar data set. In the replica set, one node will be primary, and another one will be secondary. We replicate all the data from the primary to the secondary nodes.

**[⬆ Back to Top](#questions)**

105. ### Differentiate MongoDB and Cassandra?

| MongoDB                                                  | Cassandra                                             |
| -------------------------------------------------------- | ----------------------------------------------------- |
| It is a cross-platform document-oriented database system | It is a high-performance distributed database system. |
| It is developed in C++                                   | It is developed in Java                               |
| It is simple to administer in the failure case           | It offers high availability                           |

**[⬆ Back to Top](#questions)**

106. ### Explain the primary and secondary replica set?

In MongoDB, primary nodes are the nodes that accept writing. Primary nodes are also called master nodes. Replication in MongoDB is a single master. Therefore, only one node will accept the write operations at once.

**[⬆ Back to Top](#questions)**

107. ### Which languages can we use with MongoDB?

At Present, MongoDB offers driver support to C++, Java, PHP, Perl, Python, Go, Scala, and Ruby.

**[⬆ Back to Top](#questions)**

108. ### Explain Storage Encryption?

Storage encryption encodes all the MongoDB data over the storage or over the operating systems for assuring that only authenticated processes will access the safeguarded data.

**[⬆ Back to Top](#questions)**

109. ### Explain Primary and Secondary Replica Sets?

Primary Replica Set receives all the write operations from the clients. Secondary replica sets replicate the primary replica sets and implement the operations for their datasets so that secondary datasets affect the primary datasets.

**[⬆ Back to Top](#questions)**

110. ### What is the importance of GridFS and Journaling?

GridFS: We use GridFS to retrieve and store large files like images, videos, and audio files.
Journaling: We use Journaling for secure backups in MongoDB.

**[⬆ Back to Top](#questions)**

111. ### How to do locking or transactions in MongoDB?

MongoDB does not use traditional locking with the reduction because it is high-speed, knowable, and light in the presentation. We can consider it as the MyISAM, MySQL auto entrust script. Through the simpler business sustain, we can enhance the performance, specifically in the structure with various servers.

**[⬆ Back to Top](#questions)**

112. ### How to do Journaling in MongoDB?

We save the write operations in the memory while journaling is taking place. The on-disk journal files are dependable for the reason that journal writers are usual. In the DB path, MongoDB designs a journal subdirectory.

**[⬆ Back to Top](#questions)**

113. ### How does MongoDB provide concurrency?

MongoDB utilizes the reader-writer locks, enabling concurrent readers to access any supply such as collection or database though it provides private access to individual writers.

**[⬆ Back to Top](#questions)**

114. ### Explain Sharding and Aggregation in MongoDB?

Aggregation: Aggregations are the activities that handle the data records and give the record results.
Sharding: Sharding means storing the data on multiple machines.

**[⬆ Back to Top](#questions)**

115. ### What is the importance of the profiler in MongoDB?

MongoDB contains the database profiler that shows the performance characteristics of every operation against the database. Through the profiler, we can identify the queries that are slower than they should be and use this data to determine when we require an index.

**[⬆ Back to Top](#questions)**

116. ### Define Collection?

The collection is a set of MongoDB documents.

**[⬆ Back to Top](#questions)**

117. ### Explain Aggregation Pipeline?

The aggregation Pipeline acts as a framework to perform aggregation tasks. We use this pipeline for transforming the documents into aggregated results.

**[⬆ Back to Top](#questions)**

118. ### Explain MapReduce?

MapReduce is a standard multi-phase data aggregation modality that we use to process the data quantities.

**[⬆ Back to Top](#questions)**

119. ### Explain Splitting?

Splitting is the background process that we use to store chunks from increasing too large.

**[⬆ Back to Top](#questions)**

120. ### What is the purpose of the save() method?

We use the save() method for replacing the existing documents with new documents.

**[⬆ Back to Top](#questions)**

121. ### What is the use of MongoDB?

- Generally, we use MongoDB as the main data store for the operational requirements with live needs. Generally, MongoDB is suitable for 80% of the applications which we develop today. MongoDB is simple to operate and extent in ways that are tough if they are not possible with the relational databases.
- MongoDB stands out in various use cases where the relational databases are not suitable, like applications with semi-structured, structured, along with the big scalability needs or the multi-datacenter deployments.
- MongoDB cannot be suitable for some applications. For instance, applications that need complex transactions and scan-based applications that access huge subsets of the data largely cannot be suitable for MongoDB.
- Some general uses of MongoDB comprise product catalogs, mobile apps, content management, real-time personalization, and applications providing individual views throughout several systems.

**[⬆ Back to Top](#questions)**

122. ### What is the purpose of the DB command?

We use the “DB” command to get the name of the presently selected database.

**[⬆ Back to Top](#questions)**

123. ### What are the restrictions of the MongoDB 32-bit versions?

When we run a 32-bit version of MongoDB, the total storage size of the server, containing indexes and data, is 2GB. Due to this reason, we will not deploy MongoDB to the production on the 32-bit machines. If we deploy a 64-bit version of MongoDB, there is no virtual restriction to the storage size. For the creation deployments, we strongly recommend 64-bit operating systems and builds.

**[⬆ Back to Top](#questions)**

124. ### When should we normalize the data in MongoDB?

It relies on our objectives. Normalization provides an updated effective data representation. Denormalisation makes data reading effective. Generally, we utilize embedded data models when:

- When we have “contains” relationships between the entities.
- When we have one-to-many relationships between the entities. In the relationships, “many” or the child documents display in the context of the parent documents.

Generally, we use normalized data models:

- When embedding results in duplication of the data yet they will not give enough read performance advantages to prevail the duplication implications.
- For representing more difficult many-to-many relationships.
- For modeling the big hierarchical data sets.

**[⬆ Back to Top](#questions)**

125. ### How do we perform sorting and Explain Project in MongoDB?

For finding any data in MongoDB, we use the find() method. The discovery () method returns the collection’s documents over which we invoked this method. We can use the “Where” clause in the MongoDB query in order to restrict the output by using MongoDB projection. Anytime we execute the find() method, MongoDB returns all the documents associated with a particular collection.

```shell
db.<collection_name>.find({ }, {<key_Name>:<Flag to display>})
```

**[⬆ Back to Top](#questions)**

126. ### How can MongoDB simulate subquery or join?

We have to find the best method for structuring the data in MongoDB for simulating what would be the simple subquery or join in SQL. For example, we have users and posts, with the users in one collection and posts in another collection. We have to find all the posts by the users whose city is “Hyderabad”.

128. ### Define oplog (operational log)?

An operational log (oplog) is a special kind of limited collection that stores a rolling record of all the operations which change the data we store in our databases. Primarily, it applies all the database operations over the primary and, after that, records these operations on the oplog of the primary. After that, the secondary members replicate and apply the operations in the asynchronous process.

**[⬆ Back to Top](#questions)**

129. ### How do we create a database in MongoDB?

When I want to create a database in MongoDB, I faced the following error:

```shell
 :~$mongo

MongoDB shell version:1.65

Connecting to: test

Error: Could not connect to the server

Exception: connect failed
```

The solution to the above error:

- cd/var1/lib1/MongoDB
- We remove the mongod. lock from the folder
- Sudo start MongoDB
- Mongo

**[⬆ Back to Top](#questions)**

130. ### What is the syntax of the skip() method?

skip() method syntax is:

```shell
db.COLLECTION_NAME.find().limit(NUMBER).skip(NUMBER)
```

**[⬆ Back to Top](#questions)**

131. ### How do we delete everything from the MongoDB database?

By using the following code, we can delete everything from the MongoDB database:

```shell
use [database];
db.dropDatabase();
Ruby code should be pretty similiar.
Also, from the command line:
mongo [Database] -eval "db.dropDatabase();"
use
[databaseName]
db.Drop+databasename();
drop colllection
use databaseName
db.collectionName.drop();
```

**[⬆ Back to Top](#questions)**

132. ### Which command do we use for creating the backup of the database?

We use the mongodump command for creating the database backup.

**[⬆ Back to Top](#questions)**

133. ### Which command do we use for restoring the backup?

We use mongorestore for restoring the backup.

**[⬆ Back to Top](#questions)**

134. ### Explain the importance of the dot notation?

In MongoDB, we use dot notation for accessing the array elements and the fields of an embedded document.

**[⬆ Back to Top](#questions)**

135. ### What is the syntax of the limit() and sort() method?

Syntax of the limit() method is:

```shell
>db.COLLECTION_NAME.find().limit(NUMBER)
```

Syntax of the sort() method is:

```shell
>db.COLLECTION_NAME.find().sort({KEY:1})
```

**[⬆ Back to Top](#questions)**

136. ### What do you know about NoSQL databases? What are the various types of NoSQL databases?

NoSQL refers to “Not Only SQL”. NoSQL is a kind of database that handles and sorts all kinds of structured, massive, and difficult data. It is a new method to think about databases. Kinds of NoSQL databases:

- Key-Value
- Graph
- Column Oriented
- Document Oriented

**[⬆ Back to Top](#questions)**

137. ### Which command do we use for dropping a database?

We use the “DB.drop database” command for dropping a database.

**[⬆ Back to Top](#questions)**

138. ### Explain MongoDB Projection

In MongoDB, we use Projection for selecting only the required data. It will not select the complete data of a document.

**[⬆ Back to Top](#questions)**

139. ### Why do we use the pretty() method?

We use the pretty() method for displaying the results in a formatted way.

**[⬆ Back to Top](#questions)**

140. ### How do we remove a document from the collection?

By using the remove() method, we remove a document from the collection.

**[⬆ Back to Top](#questions)**

141. ### What are the points we should consider while creating a schema in MongoDB?

We must consider the following points while creating a schema:

- Designing the Scheme based on the user requirements.
- Combining the objects into one document, if we have to use them jointly, or else, separate them.
- Perform joins while on write, and not while it is reading.
- For most general application scenarios, maximize the schema.
- Perform complex aggregations in the schema.

**[⬆ Back to Top](#questions)**

142. ### What does ObjectId contain?

ObjectId contains the following:

- Client machine ID
- Client process ID
- Byte incremented counter
- Timestamp

**[⬆ Back to Top](#questions)**

143. ### How do we use the select \* group by MongoDB aggregation?

For instance, if we have to select all the attributes and groups by name throughout the records. For example:

```cmd
{Name: George, x: 5, y: 3}
{Name: George, z: 9}
{Name: Rob, x: 12, y: 2}
```

We can do MongoDB aggregation as follows:

```shell
db.example.aggregate(
  {
    $group:{
      _id:'$name',
x: {$addToSet: "$x"    },
y: {$addToSet: "$y"    },
z: {$addToSet: "$z"    },
 }
}
)
```

**[⬆ Back to Top](#questions)**

144. ### Explain Vertical Scaling and Horizontal Scaling?

- Vertical Scaling: Vertical Scaling increases storage and CPU resources for expanding the capacity.
- Horizontal Scaling: Horizontal Scaling splits the datasets and circulates the data over multiple shards or servers.

**[⬆ Back to Top](#questions)**

145. ### What are the elements of the Sharded Cluster?

Following are the elements of the Sharded Cluster:

- Query routers
- Shards
- Config servers

**[⬆ Back to Top](#questions)**

146. ### What are the substitutes for MongoDB?

Following are the substitutes to MongoDB:

Hbase
CouchDB
Cassandra
Redis
Riak

**[⬆ Back to Top](#questions)**

147. ### How can we handle old files in the moveChunk directory?

In the course of general shard balancing operations, we make the old files as backups, and we can delete them when those operations are completed.

**[⬆ Back to Top](#questions)**

148. ### What is a Storage Engine?

Storage Engine is a component of the database that is accountable to manage how we store on the disk. For instance, one storage engine may provide better performance for the read-heavy workloads, and another one may support a great throughput for the write operations.

**[⬆ Back to Top](#questions)**

149. ### Does MongoDB require plenty of RAM?

No, MongoDB does not require plenty of RAM. It can run on a small amount of memory. MongoDB dynamically assigns and unassigns RAM according to the needs of other processes.

**[⬆ Back to Top](#questions)**

150.  ### Differentiate MongoDB and CouchDB?

| MongoDB                                  | CouchDB                                        |
| ---------------------------------------- | ---------------------------------------------- |
| MongoDB is quicker than CouchDB          | CouchDB is more secure than MongoDB            |
| Triggers do not exist in MongoDB.        | Triggers exist in CouchDB                      |
| MongoDB serializes the JSON Data to BSON | CouchDB does not store the data in JSON format |

**[⬆ Back to Top](#questions)**

151.  ### Explain Capped Collection?

In MongoDB, the Capped collection is a special kind of collection. This indicates that in this collection, we can restrict the collection size. Syntax of Capped Collection is as follows:

```shell
db.createCollection(<collection_name>, {capped: Boolean, autoIndexId: Boolean, size: Number, max : Number})
```

In the Capped Collection syntax, we have the following fields:

- Collection_Name: This field is the collection name that we create as the capped collection.
- Capped: Capped is a boolean field; it is true if we create a capped collection. By default, its value is false.
- auto indexed: It is a boolean flag that we use for auto-indexing. If this flag is true, indexes will be created automatically. If the flag is false, indexes will not be created automatically.
- Size: Size is the parameter that represents the maximum amount of documents in bytes. It is the required field in the context of capped collections.
- Max: Max is the parameter that represents the highest number of documents that permit the collection.

**[⬆ Back to Top](#questions)**

152. ### How do we perform the Join operations in MongoDB?

From MongoDB3.2, we can perform the Join operation. The new $lookup operator included with the aggregation pipeline is the same as the left outer join. Example:

```shell
{
   $lookup:
     {
       from: <collection to join>,
       localField: <field from the input documents>,
       foreignField: <field from the documents of the "from" collection>,
       as: <output array field>
     }
}
```

**[⬆ Back to Top](#questions)**

153. ### What are the storage engines used by MongoDB?

WiredTiger and MMAPv1 are the two storage engines used by MongoDB.

**[⬆ Back to Top](#questions)**

154. ### How do we configure the cache size in MongoDB?

In MongoDB, we cannot configure the cache. MongoDB utilizes the free spaces over the system automatically by using memory-mapped files.

**[⬆ Back to Top](#questions)**

155. ### How do we control the MongoDB Performance?

We can control the MongoDB Performance by:

- Locking the Performance
- Identifying the number of connections
- Database Profiling
- Full-time Diagnostic Data Capture

**[⬆ Back to Top](#questions)**

156. ### What are the aggregate functions of MongoDB?

Following are the aggregate functions of MongoDB:

- AVG
- Sum
- Min
- Max
- First
- Push
- addTo Set
- Last

**[⬆ Back to Top](#questions)**

157. ### What are the CRUD operations of MongoDB?

Following are the CRUD operations of MongoDB:

```shell
Create-db.collection.insert();

Read-db.collection.find();

Update-db.collection.update();

Delete-db.collection.remove();
```

**[⬆ Back to Top](#questions)**

158. ### What are the datatypes of MongoDB?

Following are the datatypes of MongoDB:

Integer
String
Boolean
Array
Double
Date
Timestamp
Regular Expression

**[⬆ Back to Top](#questions)**

159. ### Is it required to invoke “get last error” for making a write durable?

No, it is not required to invoke “get last error”. The server acts as if it has been invoked. “get last error” enables us to acquire confirmation that a write operation is committed. You will get the confirmation, yet the durability and safety of the writer are independent.

**[⬆ Back to Top](#questions)**

160. ### What happens when the Shard is slow or down while querying?

When the Shard is slow, the query returns an error until partial query options are fixed. When the shard is reacting slowly, MongoDB waits for it.

**[⬆ Back to Top](#questions)**

161. ### How do we use a primary key in MongoDB?

“\_id field” is reticent for a primary key in MongoDB. And it is a distinct value. If we do not set anything to the “\_id”, it will systematically fill it with the “MongoDB Id Object”. Yet, we can store any distinct information in that field.

**[⬆ Back to Top](#questions)**

162. ### How do we see the connections utilized by MongoDB?

For seeing the connections utilized by MongoDB, we use db_adminCommand(”connPoolStats”).

**[⬆ Back to Top](#questions)**

163. ### When a “moveChunk” fails, is it required to clean up partly moved docs?

No, it is not required to clean up the partly moved docs because chunk moves are deterministic and consistent. The move will try again, and when finished, data will be on the latest Shard.

**[⬆ Back to Top](#questions)**

164. ### Explain how to start the MongoDB Instance or Server?

We have to follow the below steps for starting the MongoDB Server:

- First, open the command prompt and execute the “mongod.exe” file.
- On the other hand, we move to the path where we installed MongoDB.
- Go to the bin folder, find the “mongod.exe” file, and double click the file for executing it.
- We can go to the folder, for instance, “C: MongoDB/bin” and type mongo for connecting MongoDB by using the Shell.

**[⬆ Back to Top](#questions)**

165. ### Differences between MongoDB and RDBMS

| Basis for Comparison      | MongoDB                                                                   | RDBMS                                                                         |
| ------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| Definition                | It is a non-relational database                                           | It is a relational database management system                                 |
| Working                   | It is a document-oriented database system through fields and documents    | It works over relationships among the tables, which use columns and rows      |
| Scalability               | It is horizontally and vertically scalable                                | It is vertically scalable                                                     |
| Performance               | Performance enhances with the rise in the processors                      | Performance enhances with the rise in the RAM capacity                        |
| Hierarchical Data Storage | It has a built-in provision to store the hierarchical data                | It is hard to store the hierarchical data                                     |
| Support to Joins          | It does not support difficulty Joins                                      | It supports complex joins                                                     |
| Query Language            | It uses BSON for database querying                                        | It uses SQL to query the database                                             |
| JavaScript Support        | It provides support to JavaScript-based clients for querying the database | It does not provide support to JavaScript-based clients to query the database |

**[⬆ Back to Top](#questions)**

166. ### How do applications access the real-time data modifications in MongoDB?

Applications access the real-time data modifications through the Change streams that serve as the subscriber for every collection operation like delete, insert, and update.

**[⬆ Back to Top](#questions)**

167. ### What are the different kinds of Indexes in MongoDB?

Following are the different kinds of Indexes in MongoDB:

Default: It is the “\_id” that MongoDB creates.
Compound: It is useful for multiple fields.
Multi-key: It indexes the array data.
Single field: It sorts and indexes over a single field.
Geospatial: It is useful for querying the location data.
Hashed: It indexes the hashes of the multiple fields.
MongoDB Interview Questions And Answers For Experienced

**[⬆ Back to Top](#questions)**

168. ### Define BSON?

Binary JSON or BSON is a binary-encoded format of the JSON. BSON extends the JSON and offers various data fields and types.

**[⬆ Back to Top](#questions)**

169. ### How does MongoDB store the data?

As it is a document-based database, MongoDB stores the documents in Binary Javascript Object Notation or BSON, which is a binary-encoded format of JSON.

**[⬆ Back to Top](#questions)**

170. ### Does MongoDB support ACID Transaction? Define ACID Transaction?

Yes, MongoDB supports ACID Transaction. ACID refers to Atomicity, Consistency, Isolation, and Durability. Transaction manager assures that we handle these attributes.

**[⬆ Back to Top](#questions)**

171. ### Explain Composing elements or Structure of ObjectID in MongoDB?

In MongoDB, ObjectID is associated with the “\_id” field, and MongoDB uses it as the default value of the “\_id” in the documents. For generating “ObjectID”, we use the following Syntax:

```shell
ObjectId([SomeHexaDecimalValue])
```

Example:

```shell
ObjectId() = newObjectId
```

ObjectID has the following methods:

- Str: This method provides the string representation of the object id.
- valueOf()- This method returns hexadecimal representation of the ObjectId.
- getTimeStamp()- This method returns timestamp of the ObjectId.
- toString()- This method returns the string representation of the ObjectId in “ObjectId(haxstring)”.

**[⬆ Back to Top](#questions)**

172. ### How do we find array elements with multiple criteria?

For example, if we have the below documents:

```shell
{ _id: 1, numbers: [1000, -1000]]
{ _id: 2, numbers: [500]]
```

When we execute the following command:

```bash
db.example.find( { numbers: { $elemMatch: { $gt: -10, $lt: 10 } } } );
```

**[⬆ Back to Top](#questions)**

173. ### How can we sort the user-defined function?

**For example, x and y are integers, and how do we calculate “x-y”?**

By executing the following code, we calculate x-y.

```shell
db.eval(function() {
return db.scratch.find().toArray().sort(function(doc1, doc2) {
return doc1.a – doc2.a
})
});

Versus the equivalent client-side sort:
db.scratch.find().toArray().sort(function(doc1, doc2) {
return doc1.a – doc2.b
});
```

By using the aggregation pipeline and “$orderby” operator, it is possible to sort.

**[⬆ Back to Top](#questions)**

174. ### To what extent does the data expand to multi-slice?

MongoDB shred stands on the collection. Therefore, we store all the substances in a mass or a lump. When we have an additional time slot, then we will have few slice data achievement options, yet when we have multiple lumps, data will be extended to numerous slices.

**[⬆ Back to Top](#questions)**

175. ### How do we retrieve MongoDB databases in Javascript Array?

In the MongoDB terminal, we can run “Show DBS” to retrieve the existing databases. To get the MongoDB databases programmatically, we execute the following code:

```shell
use admin
dbs = db.runCommand({listDatabases: 1})
dbNames = []
for (var i in dbs.databases) { dbNames.push(dbs.databases[i].name) }
Hopefully this will help someone else.
The below will create an array of the names of the database:
var connection = new Mongo();
var dbNames = connection.getDBNames();
```

**[⬆ Back to Top](#questions)**

176. ### How do we update the object in the Nested Array?

By executing the following code, we update the object:

```shell
Skip code block
{
“_id” : ObjectId(“4faaba123412d654fe83hg876”),
“user_id” : 123456,
“total” : 100,
“items” : [
{
“item_name” : “my_item_one”,
“price” : 20
},
{
“item_name” : “my_item_two”,
“price” : 50
},
{
“item_name” : “my_item_three”,
“price” : 30
}
]
}
```

**[⬆ Back to Top](#questions)**

177. ### How do we retrieve a particular embedded document in a MongoDB collection?

I have a collection that has an embedded document known as notes.

```shell
Skip code block
{
“_id” : ObjectId(“4f7ee46e08403d063ab0b4f9”),
“name” : “MongoDB”,
“notes” : [
{
“title” : “Hello MongoDB”,
“content” : “Hello MongoDB”
},
{
“title” : “ReplicaSet MongoDB”,
“content” : “ReplicaSet MongoDB”
}
]
}
```

**[⬆ Back to Top](#questions)**

178. ### How do we query a nested Join?

To query the nested join, we use “tested”. For example:

```shell
{“_id” : ObjectId( “abcd” ),
“className” : “com.myUser”,
“reg” : 12345,
“test” : [
{ “className” : “com.abc”,
“testid” : “pqrs” } ] }
```

**[⬆ Back to Top](#questions)**

179. ### Can we run more than one Javascript Operation in one MongoDB instance?

Yes, we can run multiple javascript operations in one MongoDB instance.

**[⬆ Back to Top](#questions)**

180. ### What do you understand by NoSQL databases? Is MongoDB a NoSQL database? explain.

At the present time, the internet is loaded with big data, big users, big complexity etc. and also becoming more complex day by day. NoSQL is answer of all these problems, It is not a traditional database management system, not even a relational database management system (RDBMS). NoSQL stands for "Not Only SQL". NoSQL is a type of database that can handle and sort all type of unstructured, messy and complicated data. It is just a new way to think about the database.

Yes. MongoDB is a NoSQL database.

**[⬆ Back to Top](#questions)**

181. ### Which are the different languages supported by MongoDB?

MonggoDB provides official driver support for C, C++, C#, Java, Node.js, Perl, PHP, Python, Ruby, Scala, Go and Erlang.

You can use MongoDB with any of the above languages. There are some other community supported drivers too but the above mentioned ones are officially provided by MongoDB.

**[⬆ Back to Top](#questions)**

182. ### What are the different types of NoSQL databases? Give some example.

NoSQL database can be classified as 4 basic types:

1.Key value store NoSQL database
2.Document store NoSQL database
3.Column store NoSQL database
4.Graph base NoSQL databse

There are many NoSQL databases. MongoDB, Cassandra, CouchBD, Hypertable, Redis, Riak, Neo4j, HBASE, Couchbase, MemcacheDB, Voldemort, RevenDB etc. are the examples of NoSQL databases.

**[⬆ Back to Top](#questions)**

183. ### Is MongoDB better than other SQL databases? If yes then how?

MongoDB is better than other SQL databases because it allows a highly flexible and scalable document structure.

For example:

One data document in MongoDB can have five columns and the other one in the same collection can have ten columns.
MongoDB database are faster than SQL databases due to efficient indexing and storage techniques.

**[⬆ Back to Top](#questions)**

184. ### What type of DBMS is MongoDB?

MongoDB is a document oriented DBMS

**[⬆ Back to Top](#questions)**

185. ### What is the difference between MongoDB and MySQL?

Although MongoDB and MySQL both are free and open source databases, there is a lot of difference between them in the term of data representation, relationship, transaction, querying data, schema design and definition, performance speed, normalization and many more. To compare MySQL with MongoDB is like a comparison between Relational and Non-relational databases.

**[⬆ Back to Top](#questions)**

186. ### Why MongoDB is known as best NoSQL database?

MongoDb is the best NoSQL database because, it is:

- Document Oriented

- Rich Query language

- High Performance

- Highly Available

- Easily Scalable

**[⬆ Back to Top](#questions)**

187. ### Does MongoDB support primary-key, foreign-key relationship?

No. By Default, MongoDB doesn't support primary key-foreign key relationship.

**[⬆ Back to Top](#questions)**

188. ### Can you achieve primary key - foreign key relationships in MongoDB?

We can achieve primary key-foreign key relationship by embedding one document inside another. For example: An address document can be embedded inside customer document.

**[⬆ Back to Top](#questions)**

189. ### Does MongoDB need a lot of RAM?

No. There is no need a lot of RAM to run MongoDB. It can be run even on a small amount of RAM because it dynamically allocates and de-allocates RAM according to the requirement of the processes.

**[⬆ Back to Top](#questions)**

190. ### Explain the structure of ObjectID in MongoDB.

ObjectID is a 12-byte BSON type. These are:

- 4 bytes value representing seconds
- 3 byte machine identifier
- 2 byte process id
- 3 byte counter

**[⬆ Back to Top](#questions)**

191. ### Is it true that MongoDB uses BSON to represent document structure?

Yes.

**[⬆ Back to Top](#questions)**

192. ### What are Indexes in MongoDB?

In MondoDB, Indexes are used to execute query efficiently. Without indexes, MongoDB must perform a collection scan, i.e. scan every document in a collection, to select those documents that match the query statement. If an appropriate index exists for a query, MongoDB can use the index to limit the number of documents it must inspect.

**[⬆ Back to Top](#questions)**

193. ### By default, which index is created by MongoDB for every collection?

By default, the_id collection is created for every collection by MongoDB.

**[⬆ Back to Top](#questions)**

194. ### What is a Namespace in MongoDB?

Namespace is a concatenation of the database name and the collection name. Collection, in which MongoDB stores BSON objects.

**[⬆ Back to Top](#questions)**

195. ### Can journaling features be used to perform safe hot backups?

Yes.

**[⬆ Back to Top](#questions)**

196. ### Why does Profiler use in MongoDB?

MongoDB uses a database profiler to perform characteristics of each operation against the database. You can use a profiler to find queries and write operations

**[⬆ Back to Top](#questions)**

197. ### If you remove an object attribute, is it deleted from the database?

Yes, it be. Remove the attribute and then re-save() the object.

**[⬆ Back to Top](#questions)**

198. ### In which language MongoDB is written?

MongoDB is written and implemented in C++.

**[⬆ Back to Top](#questions)**

199. ### Does MongoDB need a lot space of Random Access Memory (RAM)?

No. MongoDB can be run on small free space of RAM.

**[⬆ Back to Top](#questions)**

200. ### What language you can use with MongoDB?

MongoDB client drivers supports all the popular programming languages so there is no issue of language, you can use any language that you want.

**[⬆ Back to Top](#questions)**

201. ### Does MongoDB database have tables for storing records?

No. Instead of tables, MongoDB uses "Collections" to store data.

**[⬆ Back to Top](#questions)**

202. ### Do the MongoDB databases have schema?

Yes. MongoDB databases have dynamic schema. There is no need to define the structure to create collections.

**[⬆ Back to Top](#questions)**

204. ### What is the method to configure the cache size in MongoDB?

MongoDB's cache is not configurable. Actually MongoDb uses all the free spaces on the system automatically by way of memory mapped files.

**[⬆ Back to Top](#questions)**

205. ### How to do Transaction/locking in MongoDB?

MongoDB doesn't use traditional locking or complex transaction with Rollback. MongoDB is designed to be light weighted, fast and predictable to its performance. It keeps transaction support simple to enhance performance.

**[⬆ Back to Top](#questions)**

206. ### Why 32 bit version of MongoDB are not preferred ?

Because MongoDB uses memory mapped files so when you run a 32-bit build of MongoDB, the total storage size of server is 2 GB. But when you run a 64-bit build of MongoDB, this provides virtually unlimited storage size. So 64-bit is preferred over 32-bit.

**[⬆ Back to Top](#questions)**

207. ### Is it possible to remove old files in the moveChunk directory?

Yes, These files can be deleted once the operations are done because these files are made as backups during normal shard balancing operation. This is a manual cleanup process and necessary to free up space.

**[⬆ Back to Top](#questions)**

208. ### What will have to do if a shard is down or slow and you do a query?

If a shard is down and you even do query then your query will be returned with an error unless you set a partial query option. But if a shard is slow them Mongos will wait for them till response.

**[⬆ Back to Top](#questions)**

209. ### Explain the covered query in MongoDB.

A query is called covered query if satisfies the following two conditions:

- The fields used in the query are part of an index used in the query.
- The fields returned in the results are in the same index.

**[⬆ Back to Top](#questions)**

210. ### What is the importance of covered query?

Covered query makes the execution of the query faster because indexes are stored in RAM or sequentially located on disk. It makes the execution of the query faster.

Covered query makes the fields are covered in the index itself, MongoDB can match the query condition as well as return the result fields using the same index without looking inside the documents.

**[⬆ Back to Top](#questions)**

211. ### What is sharding in MongoDB?

In MongoDB, Sharding is a procedure of storing data records across multiple machines. It is a MongoDB approach to meet the demands of data growth. It creates horizontal partition of data in a database or search engine. Each partition is referred as shard or database shard.

**[⬆ Back to Top](#questions)**

212. ### What is replica set in MongoDB?

A replica can be specified as a group of mongo instances that host the same data set. In a replica set, one node is primary, and another is secondary. All data is replicated from primary to secondary nodes.

**[⬆ Back to Top](#questions)**

213. ### What is primary and secondary replica set in MongoDB?

In MongoDB, primary nodes are the node that can accept write. These are also known as master nodes. The replication in MongoDB is single master so, only one node can accept write operations at a time.

Secondary nodes are known as slave nodes. These are read only nodes that replicate from the primary.

**[⬆ Back to Top](#questions)**

214. ### By default, which replica sets are used to write data?

By default, MongoDB writes data only to the primary replica set.

**[⬆ Back to Top](#questions)**

215. ### What is CRUD in MongoDB?

MongoDB supports following CRUD operations:

Create
Read
Update
Delete

**[⬆ Back to Top](#questions)**

216. ### In which format MongoDB represents document structure?

MongoDB uses BSON to represent document structures.

**[⬆ Back to Top](#questions)**

217. ### What will happen when you remove a document from database in MongoDB? Does MongoDB remove it from disk?

Yes. If you remove a document from database, MongoDB will remove it from disk too.

**[⬆ Back to Top](#questions)**

218. ### Why are MongoDB data files large in size?

MongoDB doesn't follow file system fragmentation and pre allocates data files to reserve space while setting up the server. That's why MongoDB data files are large in size.

**[⬆ Back to Top](#questions)**

219. ### What is a storage engine in MongoDB?

A storage engine is the part of a database that is used to manage how data is stored on disk.

For example: one storage engine might offer better performance for read-heavy workloads, and another might support a higher-throughput for write operations.

**[⬆ Back to Top](#questions)**

220. ### Which are the storage engines used by MongoDB?

MMAPv1 and WiredTiger are two storage engine used by MongoDB.

**[⬆ Back to Top](#questions)**

221. ### What is the usage of profiler in MongoDB?

A database profiler is used to collect data about MongoDB write operations, cursors, database commands on a running mongod instance. You can enable profiling on a per-database or per-instance basis.

The database profiler writes all the data it collects to the system. profile collection, which is a capped collection.

**[⬆ Back to Top](#questions)**

222. ### Is it possible to configure the cache size for MMAPv1 in MongoDB?

No. it is not possible to configure the cache size for MMAPv1 because MMAPv1 does not allow configuring the cache size.

**[⬆ Back to Top](#questions)**

223. ### How to configure the cache size for WiredTiger in MongoDB?

For the WiredTiger storage engine, you can specify the maximum size of the cache that WiredTiger will use for all data. This can be done using storage.wiredTiger.engineConfig.cacheSizeGB option.

**[⬆ Back to Top](#questions)**

224. ### How does MongoDB provide concurrency?

MongoDB uses reader-writer locks for concurrency. Reader-writer locks allow concurrent readers shared access to a resource, such as a database or collection, but give exclusive access to a single write operation.

**[⬆ Back to Top](#questions)**

225. ### What is the difference between MongoDB and Redis database?

Difference between MongoDB and Redis:

- Redis is faster than MongoDB.
- Redis has a key-value storage whereas MongoDB has a document type storage.
- Redis is hard to code but MongoDB is easy.

**[⬆ Back to Top](#questions)**

226. ### What is the difference between MongoDB and CouchDB?

Difference between MongoDB and CouchDB:

MongoDB is faster than CouchDB while CouchDB is safer than MongoDB.
Triggers are not available in MongoDB while triggers are available in CouchDB.
MongoDB serializes JSON data to BSON while CouchDB doesn't store data in JSON format.
For more information: click here

**[⬆ Back to Top](#questions)**

227. ### What is the difference between MongoDB and Cassandra?

Difference between MongoDB and Cassandra:

MongoDB is cross-platform document-oriented database system while Cassandra is high performance distributed database system.
MongoDB is written in C++ while Cassandra is written in Java.
MongoDB is easy to administer in the case of failure while Cassandra provides high availability with no single point of failure.
For more information: click here

**[⬆ Back to Top](#questions)**

228. ### Is there any need to create database command in MongoDB?

You don't need to create a database manually in MongoDB because it creates automaically when you save the value into the defined collection at first time.

**[⬆ Back to Top](#questions)**
