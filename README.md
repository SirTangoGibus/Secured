# Secured
A two person project in C focused on securing information using hash functions and tables.

The project contains a hash function which fulfils the following requirements:

1. The output string is entirely determined by the hashed data.
2. All input data is used in hashing.
3. Two almost identical inputs give very different output values
4. The hash function evenly distributes the data in the hash table.

Additionally, it also contains a hash table with the following functions: the ability to create (and delete a hash table) and four table manipulation functions:

Dump: displays the state of a hash table.
Insert: inserts a new element in the hash table.
Delete: deletes a value from the table.
Search: takes a key as a parameter then hashes it to access the index. If the value matches the hash, the value is returned. 
