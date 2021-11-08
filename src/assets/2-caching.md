# Caching

There are only two hard things in Computer Science: cache invalidation and naming things.

-- Phil Karlton

# What is a cache

A cache is any data store that can store and retrieve data quickly for future use, enabling faster response times and decreasing load on other parts of your system.

# Why we cache

# Where we cache and 

* DNS - TTL
* Browser - Etags
* File system cache / CDNs - Cloudflare, Cloudfront
* In-memory application cache - Spring-context, EHCache, just use a map of key / values
* Distirbuted cache - Memcache / Redis
* Database cache - integrated 

https://aws.amazon.com/caching/database-caching/
https://www.baeldung.com/spring-cache-tutorial

# A side track on memoization

Do fibonacci memoization

# Caching strategies

Optimal Replacement( Replace the block which is no longer needed in the future.)
First in First out(FIFO)
Least recently used (LRU)
Random Selection

