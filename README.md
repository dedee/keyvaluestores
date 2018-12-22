# Key/Value Stores

Summary of key value stores out there.


CDB

    http://cr.yp.to/cdb.html
 

Sparkey

    https://github.com/spotify/sparkey

    Von Spotify Entwicklern nebenbei implementiert. Nicht mehr viel Action.

    Immer zwei Files. Index und Daten.

    CDB bis ca 4 GB gut. Sparkey addressiert größere Files.

 

LevelDB

    Made by some Googlers

    https://github.com/google/leveldb

 

PalDB

    LinkedIn

    https://github.com/linkedin/PalDB

 

MPH Table - MinimalPerfectHash Java

    https://github.com/indeedeng/mph-table

    https://engineering.indeedblog.com/blog/2018/02/indeed-mph/

    Einige gradle dependencies. Leider auch native und keine Windows DLL.

 

DiscoDB

    https://github.com/discoproject/discodb

 

JSON Stores / NoSQL

===================

 

UnQLite

    C++

    https://unqlite.org/

    Embedded one C++ File. Low memory.

 

RocksDB

    https://rocksdb.org/

    Facebook Opensource.

    GPL and Apache2

    Seems to have encryption provider API

 

SQLite4 LSM

    Embedded key/value DB like BerkeleyDB, LevelDB, KyotoCabinet

    https://sqlite.org/src4/doc/trunk/www/lsmusr.wiki

 

kyotocabinet

    Kyoto Cabinet is a library of routines for managing a database.

    https://fallabs.com/kyotocabinet/

 

    Has compression (zlib) API which also offers RC4 encryption too.

 

    GPL and commercial license.

 

    Von last.fm gibt es besseren Java Layer:

    https://github.com/lastfm/lastcommons-kyoto

 

faster

    https://github.com/Microsoft/FASTER

 

 

sled

    https://crates.io/crates/sled
