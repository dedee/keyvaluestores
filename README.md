# Key/Value Stores, JSON, NoSQL

Summary of key value stores out there.

### CDB
<http://cr.yp.to/cdb.html>


### Sparkey
<https://github.com/spotify/sparkey>

Made by spotify engineers as fun project. No commits anymore.
Always index and data file. Addresses large files.

### LevelDB
<https://github.com/google/leveldb>

Made by some Googlers. Actively maintained. 

### PalDB
<https://github.com/linkedin/PalDB>

Made by LinkedIn. Pure Java. Write once store. Uses single DB file.
Looks good 1st but no commits since 4 years.

### MPH Table - MinimalPerfectHash Java

<https://github.com/indeedeng/mph-table>
<https://engineering.indeedblog.com/blog/2018/02/indeed-mph/>

Looks promising. But unfortunately a lot of dependencies. Also it requires
some mmap JNI library which is not available for all platforms. Windows
possible at all?

### DiscoDB
<https://github.com/discoproject/discodb>
 
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

### sled
<https://crates.io/crates/sled>

