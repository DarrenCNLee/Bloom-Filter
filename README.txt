Darren Lee
CSE107 Winter 2022

Project III: Bloom filters

-------------------------------------------------------------------------------------

Program Description
This program implements a bloom filter using hash functions for quick lookup 
time to check if an element is added to the filter or not. The add() and contains()
functions are implemented by me. Since some elements may map to bits that are 
already set by the hash functions, there can be false positives reported by
the contains() function.

The add() function adds an element to the bloom filter by setting 
the bits in the array to true using the hash functions.

The contains() function just checks if the bits for an element 
are set to check if the element might be added or not. If contains()
returns false, the element is definitely not in the set. If contains()
return true, the element might be in the set, but there is a chance of 
a false positive.

-------------------------------------------------------------------------------------

Instructions to compile/run program

python bloom_filter.py

-------------------------------------------------------------------------------------

Files

bloom_filter.py - contains the program code for the bloom filter
