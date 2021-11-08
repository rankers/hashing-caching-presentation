# What is Hashing

Etymology: (maybe) The term "hash" offers a natural analogy with its non-technical meaning (to "chop" or "make a mess" out of something).

or more concretely:

A hash function is any function that can be used to map data of arbitrary size to fixed-size values.

# Properties of a good hashing function

 1. It should be very efficient to compute.
 2. The function needs to be determinist; you get the same output for the same input each time it is run.
 3. It should avoid collisions, no two inputs should produce the same output. (Or
 4. For encryption purposes, the output should not give any indication of the input.
it should be practically impossible.)

# Example of a hash function

https://en.wikipedia.org/wiki/Hash_function

Repl here 

# Example Hashing functions

* MD5 
* SHA (Secure Hashing Algorithm), SHA1, SHA2, SHA3


# Git uses hashing 

Every time you comit something you get a lovely bug hash value


# Cryptographic hashing vs just normal hashing

A cryptographic hash function aims to guarantee a number of security properties.

Most importantly that it's hard to find collisions 
Output appears random 

Rainbow tables -https://en.wikipedia.org/wiki/Rainbow_table why we use salts

http://torvalds.cs.longwood.edu/courses/cmsc461/s20/files/josh.pdf