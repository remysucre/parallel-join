## Notes

DuckDB's parallel hash aggregate [implementation](https://duckdb.org/2022/03/07/aggregate-hashtable.html) follows [@DBLP:conf/sigmod/LeisBK014].

Many in-memory DBs don't even implement sort-merge join, because of results from research showing hashing is faster than sorting on parallel hardware [@DBLP:journals/pvldb/BalkesenATO13].

Concurrent Hash Map based on [Parlaylib](https://github.com/cmuparlay/parlaylib) that is growable [implementation](https://github.com/cmuparlay/parlayhash).
