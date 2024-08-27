edis is a free and open-source (BSD licensed) in-memory data structure store that functions as a database, cache, message broker, and streaming engine. It offers various data structures, including strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams. Redis supports features such as built-in replication, Lua scripting, LRU eviction, transactions, and several levels of on-disk persistence. It also ensures high availability through Redis Sentinel and automatic partitioning via Redis Cluster.

You can perform atomic operations on these data types, such as appending to a string, incrementing a hash value, pushing elements to a list, calculating set intersections, unions, and differences, or retrieving the highest-ranking member in a sorted set.

Redis operates with an in-memory dataset to deliver optimal performance. Depending on your requirements, Redis can persist data by either periodically saving the dataset to disk or by logging each command to a disk-based log. If persistent storage isn't needed, you can disable it entirely to use Redis as a feature-rich, networked, in-memory cache.

Redis supports asynchronous replication, enabling fast non-blocking synchronization and automatic reconnection with partial resynchronization during network splits.

Additionally, Redis includes features such as:

Transactions
Pub/Sub messaging
Lua scripting
Keys with limited time-to-live (TTL)
LRU key eviction
Automatic failover
Redis can be used with most programming languages.

Written in ANSI C, Redis is compatible with most POSIX systems, including Linux, *BSD, and macOS, without requiring external dependencies. Although Redis is primarily developed and tested on Linux and macOS—making Linux the recommended platform for deployment—it may also run on Solaris-based systems like SmartOS, albeit with best-effort support. Official Windows builds are not supported.
