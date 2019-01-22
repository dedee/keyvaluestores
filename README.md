# Key/Value Stores, JSON, NoSQL

Summary of key value stores out there.

## Java

### PalDB
<https://github.com/linkedin/PalDB>

Made by LinkedIn. Pure Java. Write once store. Uses single DB file.
Looks good 1st but no commits since 4 years.

### Map DB
<https://github.com/jankotek/mapdb>

Nice key value store written in Kotlin

### JSON DB
<http://jsondb.io>

Small memory footprint, runs embedded within your Java program. Encryption support. Con: All data in memory.

### MPH Table - MinimalPerfectHash Java

<https://github.com/indeedeng/mph-table>
<https://engineering.indeedblog.com/blog/2018/02/indeed-mph/>

Looks promising. But unfortunately a lot of dependencies. Also it requires
some mmap JNI library which is not available for all platforms. Windows
possible at all?

### SG-CDB
<https://github.com/malyn/sg-cdb>

Java implementation of D. Bernsteins CDB algorithm. Well coded, but inactive since 7 years.

### Sleepycat cdb-java
<https://github.com/sleepy-cat/cdb-java>

Another Java implementation of CDB.

### Xodus ###
<https://github.com/JetBrains/xodus>

A Jetbrains embedded transactional database written in Java and Kotlin.
https://github.com/JetBrains/xodus/tree/master/entity-store


## C/C++

### CDB
<http://cr.yp.to/cdb.html>

### Sparkey
<https://github.com/spotify/sparkey>

Made by spotify engineers as fun project. No commits anymore.
Always index and data file. Addresses large files.

### LevelDB
<https://github.com/google/leveldb>

Made by some Googlers. Actively maintained. 

### DiscoDB
<https://github.com/discoproject/discodb>

Discodb is comprised of a low-level data structure implemented in C with a OO C++ API.
 
### UnQLite
<https://unqlite.org/>

Embedded one C++ File. Low memory.

### RocksDB
<https://rocksdb.org/>

Facebook Opensource. GPL and Apache2
Seems to have encryption provider API

### SQLite4 LSM
<https://sqlite.org/src4/doc/trunk/www/lsmusr.wiki>

Embedded key/value DB like BerkeleyDB, LevelDB, KyotoCabinet

### kyotocabinet
<https://fallabs.com/kyotocabinet/>

Kyoto Cabinet is a library of routines for managing a database.
Has compression (zlib) API which also offers RC4 encryption too.
GPL and commercial license.
Von last.fm gibt es besseren Java Layer:
https://github.com/lastfm/lastcommons-kyoto

### faster
<https://github.com/Microsoft/FASTER>

C/C# implementation. Concurrent key-value store + cache that is designed for point lookups and heavy updates.


## RUST

### sled
<https://crates.io/crates/sled>


