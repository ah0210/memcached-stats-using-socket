This is fork from [Harun Yayli's Memcached Stats](http://livebookmark.net/journal/2008/05/21/memcachephp-stats-like-apcphp/). I just wanted to change some codes to use this file to capture Memcached stats which uses Unix Sockets. This config might be risky to use in production and I have certainly not tested it in production. I use this in my development machine where I can test the stats of Memcached like APC. This file also doesn't offer flexible informations about used bins and memory chunks assigned to each slots. It just states how much resource Memcached is using and the served caches via Memcached.

This file is password protected, the credentials are:
username: memcache
password: memcache