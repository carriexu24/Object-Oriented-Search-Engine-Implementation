# Object Oriented Search Engine Implementation

A reusable library of a hash table implementation.

## Examples

The following examples all create a hashtable, then set the value associated with the key "parrt" and the value 99.

```
from htable_oo import HashTable

#create a hash table
table = HashTable(5) 

#put an association with key 'parrt' and value 99 into the table
table.put('parrt', 99) 

#print the hash table
print(table.buckets_str())

#print all associations in the hash table
str(table)
```
