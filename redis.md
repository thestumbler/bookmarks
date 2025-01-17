Redis
=====

* [joinc.co.kr/REDIS](https://www.joinc.co.kr/w/man/12/REDIS)
* [practice - architecture, usage tip](https://gist.github.com/hyunjun/4ab30f4ebd401bcb0e60aabbab0b97bc)
* [practice - logging](https://gist.github.com/hyunjun/4ab30f4ebd401bcb0e60aabbab0b97bc#file-logging-md)
* [practice - coupang 오류 관련 내용](https://gist.github.com/hyunjun/4ab30f4ebd401bcb0e60aabbab0b97bc#file-coupang-md)
* [Redis 자료구조](http://daddycat.blogspot.com/2017/07/redis.html)
* [Writing a Redis client in pure Bash](http://digitalserb.me/writing-a-redis-client-in-pure-bash/)
* [advanced-redis](https://github.com/iamtrk/advanced-redis)
* [How to take advantage of Redis just adding it to your stack](http://oldblog.antirez.com/post/take-advantage-of-redis-adding-it-to-your-stack.html)
* [Recovering Redis Data with GDB](http://bigeng.io/post/118963807718/recovering-redis-data-with-gdb)
* [Redis Hot Patch](http://benmmurphy.github.io/blog/2015/06/09/redis-hot-patch/)
* [How Twitter Uses Redis To Scale - 105TB RAM, 39MM QPS, 10,000+ Instances](http://highscalability.com/blog/2014/9/8/how-twitter-uses-redis-to-scale-105tb-ram-39mm-qps-10000-ins.html)
* [Keeping up with the cool databases we present: Redis](https://codepicnic.com/posts/keeping-up-with-the-cool-databases-we-present-redis-cedebb6e872f539bef8c3f919874e9d7)
* [Transactions in Redis](http://www.dr-josiah.com/2015/07/transactions-in-redis.html)
* [Redis on AWS](http://www.slideshare.net/charsyam2/redis-on-aws)
* [FAILOVER WITH REDIS SENTINEL](http://engineering.vinted.com/2015/09/03/failover-with-redis-sentinel/)
* [Clarifications about Redis and Memcached](http://antirez.com/news/94)
* [Lazy Redis is better Redis](http://antirez.com/news/93)
* [A few things about Redis security](http://antirez.com/news/96)
* [Lock and cache using redis](https://github.com/seamusabshere/lock_and_cache)
* [Recent improvements to Redis Lua scripting](http://antirez.com/news/97)
* [Atomic 처리와 cache stampede 대책을 위해 Redis Lua script를 활용한 이야기](https://engineering.linecorp.com/ko/blog/atomic-cache-stampede-redis-lua-script/)
* [Redis의 SCAN은 어떻게 동작하는가?](http://tech.kakao.com/2016/03/11/redis-scan/)
* [DNS 기반의 Redis HA 구현](http://tech.kakao.com/2016/03/18/redis-ha-dns/)
* [Redis Labs](http://www.slideshare.net/RedisLabs)
* [Redis in a Multi Tenant Environment–High Availability, Monitoring & Much More!](http://www.slideshare.net/RedisLabs/redis-in-a-multi-tenant-environmenthigh-availability-monitoring-much-more)
* [Redis 의 Sentinel](http://crystalcube.co.kr/m/post/177)
* [Redis Conf 2016: Redis in a Multi-Tenant Environmnet](https://www.youtube.com/watch?v=aZ64pM7OVaw)
* [RedisConf18: Building Light weight Microservices Using Redis - Redis Labs](https://www.youtube.com/watch?v=z25CPqJMFUk)
  * [Building Light-weight Microservices using Redis](https://medium.com/flywheel-tech/building-light-weight-microservices-using-redis-23f051624647)
* [Microservice Communication: A Spring Integration Tutorial with Redis](https://www.toptal.com/spring/spring-integration-tutorial-redis-microservices)
* [RedisConf18: Implementing a New Data Structure for Redis - Redis Labs](https://www.youtube.com/watch?v=pmxaztRsoF4)
* [RedisConf18 발표 후기](https://engineering.linecorp.com/ko/blog/detail/306)
* [Redis Networking Nerd Down: For Lovers of Packets and Jumbo Frames- John Bullard, Distil Networks](http://www.slideshare.net/RedisLabs)
* [입 개발 Redis 접속이 안되요!!! – Protected Mode](https://charsyam.wordpress.com/2016/07/11/%EC%9E%85-%EA%B0%9C%EB%B0%9C-redis-%EC%A0%91%EC%86%8D%EC%9D%B4-%EC%95%88%EB%90%98%EC%9A%94-protected-mode/)
* [Developing a Redis Module](https://www.youtube.com/watch?v=LPxx4QPyUPw)
* **[REDIS 데이터 모델들](http://www.popit.kr/redis-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%AA%A8%EB%8D%B8%EB%93%A4/)**
* [Redis cluster tutorial](https://redis.io/topics/cluster-tutorial)
* [Intro To Redis Cluster Sharding – Advantages, Limitations, Deploying & Client Connections](http://highscalability.com/blog/2019/2/19/intro-to-redis-cluster-sharding-advantages-limitations-deplo.html)
* [Radix? Redis!](https://tosslab.github.io/2017/05/09/radix_redis.html)
* [10. 데이터 폭풍이닷: 스크래핑으로 가져온 데이터 처리](https://highluck.github.io/#/project_k)
* 3개의 key column이 있으며, 하나의 key로 찾는 경우
  * scan or hash
  * C_B_A와 같이 key column을 조합해 문서 key로 쓰거나, C로 hash를 각각 만들어 사용
* 혀로그래머 charsyam은 구라쟁이
  * [샤딩은 쉬워요 샤딩하세요](https://charsyam.wordpress.com/2017/05/24/%ED%98%80%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8-charsyam%EC%9D%80-%EA%B5%AC%EB%9D%BC%EC%9F%81%EC%9D%B4-1-%EC%83%A4%EB%94%A9%EC%9D%80-%EC%89%AC%EC%9B%8C%EC%9A%94-%EC%83%A4%EB%94%A9%ED%95%98%EC%84%B8/)
  * [캐시 멤캐시나 레디스 쓰세요. 쉬워요](https://charsyam.wordpress.com/2017/05/27/%ED%98%80%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8-charsyam%EC%9D%80-%EA%B5%AC%EB%9D%BC%EC%9F%81%EC%9D%B4-2-%EC%BA%90%EC%8B%9C-%EB%A9%A4%EC%BA%90%EC%8B%9C%EB%82%98-%EB%A0%88%EB%94%94%EC%8A%A4-%EC%93%B0/)
  * [레디스 관련 Q&A](https://charsyam.wordpress.com/2017/05/28/%ED%98%80%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8-charsyam%EC%9D%80-%EA%B5%AC%EB%9D%BC%EC%9F%81%EC%9D%B4-qa-%EB%A0%88%EB%94%94%EC%8A%A4-%EA%B4%80%EB%A0%A8-qa/)
  * [Redis에 심플한 key-value 로 수 억개의 데이터 저장하기](https://charsyam.wordpress.com/2011/11/06/redis%EC%97%90-%EC%8B%AC%ED%94%8C%ED%95%9C-key-value-%EB%A1%9C-%EC%88%98-%EC%96%B5%EA%B0%9C%EC%9D%98-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%A0%80%EC%9E%A5%ED%95%98%EA%B8%B0/)
  * [spring-security-oauth의 RedisTokenStore의 사용은 서비스에 적합하지 않습니다](https://charsyam.wordpress.com/2018/05/11/%EC%9E%85-%EA%B0%9C%EB%B0%9C-spring-security-oauth%EC%9D%98-redistokenstore%EC%9D%98-%EC%82%AC%EC%9A%A9%EC%9D%80-%EC%84%9C%EB%B9%84%EC%8A%A4%EC%97%90-%EC%A0%81%ED%95%A9%ED%95%98%EC%A7%80-%EC%95%8A/)
  * [Redis 버그 – Dataset 사이즈가 200GB가 넘어가면 죽는다구요?](https://charsyam.wordpress.com/2019/08/26/입-개발-redis-버그-dataset-사이즈가-200gb가-넘어가면-죽는다구요)
* [Redis와 전자정부프레임워크 연동](http://daddycat.blogspot.com/2017/06/redis.html)
* [lua 사용 사례](http://knight76.tistory.com/entry/redis-lua-%EC%82%AC%EC%9A%A9-%EC%82%AC%EB%A1%80)
* `nc -v redis.mydomain.com 6379` [Linux - Install redis-cli only](https://stackoverflow.com/questions/21795340/linux-install-redis-cli-only)
* lock
  * [Transactions and Locks](http://intro2libsys.info/introduction-to-redis/transactions-and-locks)
  * [6.2.3 Building a lock in Redis](https://redislabs.com/ebook/part-2-core-concepts/chapter-6-application-components-in-redis/6-2-distributed-locking/6-2-3-building-a-lock-in-redis/)
  * [SETNX key value](https://redis.io/commands/setnx)
* [분산 웹 캐시 (Wcache)의 개선과정 - Part 1](http://tech.kakao.com/2017/10/23/wcache-1/)
* [분산 웹 캐시 (Wcache)의 개선과정 - Part 2](http://tech.kakao.com/2017/10/23/wcache-2/)
* [Replication](https://redis.io/topics/replication)
  * [redis-replicator](https://github.com/leonchen83/redis-replicator)
* [Redis Node와 연동하기](https://www.zerocho.com/category/NodeJS/post/5a3238b714c5f9001b16c430)
* [운영에 필요한 최소한의 지식](http://jybaek.tistory.com/711) List, Hash
* [Why Redis?](https://www.youtube.com/watch?v=OG610oe_kxs)
* **[Dave Nielsen: Top 5 uses of Redis as a Database](https://www.youtube.com/watch?v=jTTlBc2-T9Q)** 내부 구조 기초
* [Redis Labs and SQL Server](https://www.youtube.com/watch?v=XQ9QEgLZAcQ)
* [Redis tutorial for beginners](https://www.youtube.com/watch?v=z9OPBVe6tgc)
* [Redis Tutorial - A Brief Introduction to Redis](https://www.youtube.com/watch?v=qr4FVhBTq0I)
* [Redis Tutorial - Intro to Redis w/ Node.js Demo](https://www.youtube.com/watch?v=uJb4HjtvcIE)
* [Build A Node.js & Redis App From Scratch](https://www.youtube.com/watch?v=9S-mphgE5fA)
* [Redis Crash Course Tutorial](https://www.youtube.com/watch?v=Hbt56gFj998)
* [05 01 Implementing a Redis Cache](https://www.youtube.com/watch?v=ECz6Mv3T7Ec)
* [Why Your MySQL Needs Redis | Redis Labs](https://www.youtube.com/watch?v=_4HwUVNl9Nc)
* [Why and When You Should Use Redis](https://www.youtube.com/watch?v=CoQcNgfPYPc)
* [Scaling Redis at Twitter](https://www.youtube.com/watch?v=rP9EKvWt0zo)
* [Redis Use Patterns: An Introduction to the SQL Practitioner](https://www.youtube.com/watch?v=8Unaug_vmFI)
* [Amazon ElastiCache(Redis)를 이용한 채팅 애플리케이션 구성 방법](https://aws.amazon.com/ko/blogs/korea/how-to-build-a-chat-application-with-amazon-elasticache-for-redis)
* [EC2에 Redis CLI 설치하기](https://jojoldu.tistory.com/348)
* [You should revise your Redis max connections setting](https://medium.com/appaloosa-store-engineering/you-should-revise-your-redis-max-connections-setting-8136f063c916)
  * heroku에서 사용할 때 이야기라 server에 설치해서 쓸 때와는 조금 거리가 있지만 참고
* [redis-cli 에서 –rdb는 주의해서 사용하셔야 합니다](https://charsyam.wordpress.com/2019/10/07/입-개발-redis-cli-에서-rdb는-주의해서-사용하셔야-합니다/)

# Book
* [Redis in Action](https://redislabs.com/community/ebook/)

# Clojure
* [redis-get-set](https://github.daumkakao.com/todd-ddd/redis-get-set)

# Command
* [Redis 에서 zadd 와 zincrby 의 차이](https://charsyam.wordpress.com/2018/09/06/%ec%9e%85-%ea%b0%9c%eb%b0%9c-redis-%ec%97%90%ec%84%9c-zadd-%ec%99%80-zincrby-%ec%9d%98-%ec%b0%a8%ec%9d%b4/)
* BGSAVE
  * [practice - backup & restore](https://gist.github.com/hyunjun/cfce6fc1ea6d0ca8995417ed64347538)
* CONFIG
  * `config get maxclients` or `echo "config get maxclients" | nc -v <redis server> <redis port>` 현재 설정된 최대 접속 허용 client 개수
  * [Redis RENAME-COMMAND Parameter](http://redisgate.kr/redis/configuration/param_rename-command.php)
    * 성능저하 혹은 운영상 위험이 발생할 수 있는 명령의 이름을 바꾸는 방법
    * redis.conf에서 해당 명령을 변경 e.g. flushall -> xflushall, flushdb -> xflushdb
* [INFO](https://redis.io/commands/INFO) disk usage 등 여러가지 정보
  * `info, info('cpu'), info('memory'), ...` in python
  * `info clients` or `echo "info clients" | nc -v <redis server> <redis port>` connected clients 개수
* [HSCAN](https://redis.io/commands/hscan) `hash name 0 \[match pattern>\]` patern = \*pattern or pattern\* or \*pattern\*
  * `hscan_iter` in python
  * [How to search a key pattern in redis hash?](https://stackoverflow.com/questions/35850608/how-to-search-a-key-pattern-in-redis-hash)
* RENAME
  * [practice](https://gist.github.com/hyunjun/cfce6fc1ea6d0ca8995417ed64347538#file-rename-md) 앞의 hash를 뒤의 hash로 덮어씀. 앞의 hash는 삭제
* [SCAN](https://redis.io/commands/scan) `scan 0 \[match pattern\]` patern = \*pattern or pattern\* or \*pattern\* e.g. `scan 0 match *test*`
  * `scan_iter` in python
  * [Get all keys in Redis database with python](https://stackoverflow.com/questions/22255589/get-all-keys-in-redis-database-with-python)
  * **[패턴으로 TTL 적용하기](https://jojoldu.tistory.com/349)** scan으로 pattern match되는 key를 찾아 expire 적용하는 script

# Library
* [Gredis - Redis server built over grpc](https://github.com/voidabhi/gredis)
* [hiredis - Minimalistic C client for Redis >= 1.2](https://github.com/redis/hiredis)
* [KeyDB - A Multithreaded Fork of Redis https://keydb.dev ](https://github.com/JohnSully/KeyDB)
  * [A Multithreaded Fork of Redis That’s 5X Faster Than Redis](https://docs.keydb.dev/blog/2019/10/07/blog-post/)
* [Medis - a beautiful, easy-to-use Mac database management application for Redis. http://getmedis.com](https://github.com/luin/medis)
* [Redis Geo](https://matt.sh/redis-geo)
* [redis-rdb-tools Parse Redis dump.rdb files, Analyze Memory, and Export Data to JSON https://rdbtools.com ](https://github.com/sripathikrishnan/redis-rdb-tools)
* [redis-traffic-stats - a query analyzer for Redis](https://github.com/hirose31/redis-traffic-stats)
* ~[SerenityDB - disk storage and real transactions under Redis compatible protocol](http://serenitydb.org/)~
* [Spark-Redis - A library for reading and writing data from and to Redis with Apache Spark](https://github.com/RedisLabs/spark-redis)
  * [Give Spark a 45x speed boost with Redis](https://www.infoworld.com/article/3045083/analytics/give-spark-a-45x-speed-boost-with-redis.html)
  * [Spark-Redis - A library for reading and writing data from and to Redis with Apache Spark](https://github.com/oeegee/spark-redis) 2.2.0
* [Treat Redis Lists like Unix Pipes](https://github.com/lukasmartinelli/redis-pipe)
* [twemproxy - A fast, light-weight proxy for memcached and redis](https://github.com/twitter/twemproxy)
  * [recommendation](https://github.com/twitter/twemproxy/blob/master/notes/recommendation.md#server_connections--1)
  * [nutcracker-web - Web interface plugin for nutcracker-ruby (Twemproxy)](https://github.com/kontera-technologies/nutcracker-web)

# Python
* [How to Use Redis with Python 3 and redis-py on Ubuntu 16.04](https://www.fullstackpython.com/blog/install-redis-use-python-3-ubuntu-1604.html)
* [Write Fast Apps Using Async Python 3.6 and Redis](https://eng.paxos.com/write-fast-apps-using-async-python-3.6-and-redis)
  * [subconscious - redis-backed (in memory) db for python3 that is asyncio compatible](https://github.com/paxos-bankchain/subconscious)
* [Dave Nielsen: Top 5 uses of Redis as a Database | PyData Seattle 2015](https://www.youtube.com/watch?v=jTTlBc2-T9Q)
* [redis-python-simple-tutorial](https://github.com/jsrimr/redis-python-simple-tutorial)

## Python Library
* [aioredis - asyncio (PEP 3156) Redis client library](http://aioredis.readthedocs.io/)
  * [github.com/aio-libs/aioredis](https://github.com/aio-libs/aioredis)
  * [Python aioredis.Redis() Examples](https://www.programcreek.com/python/example/98948/aioredis.Redis)
  * [Python aioredis.create_redis_pool() Examples](https://www.programcreek.com/python/example/98950/aioredis.create_redis_pool)
  * [How to use aioredis in tornado](https://groups.google.com/forum/#!msg/aio-libs/HHGm2-NC3UA/mxVinwHKAAAJ)
  * [hello_asyncio.py](https://github.com/rudyryk/python-samples/blob/master/hello_tornado/hello_asyncio.py#L85-L99)
  * [streamis.py](https://github.com/mivade/streamis/blob/master/streamis.py)
* [asyncio-redis - Redis client for Python asyncio](https://github.com/jonathanslenders/asyncio-redis)
* [rb: A Redis parallelization toolkit for Python](http://blog.getsentry.com/2015/08/20/rb-redis-parallelization-toolkit.html)
* [redis - Python client for Redis key-value store](https://pypi.python.org/pypi/redis)
  * [redis-py](http://redis-py.readthedocs.io/)
  * [practice - `hgetall` vs. `hscan_iter`, `hmset` vs. `hset` encoding 문제 발생](https://gist.github.com/hyunjun/1a607507f420efb5bcbc3dd3ef37b7ee)
  * [practice - `hset hget hmset hgetall` + json dumps/loads](https://github.com/hyunjun/practice/tree/master/python/test-redis)
  * [fakeredis: A fake version of a redis-py](https://pypi.org/project/fakeredis/)
    * [practice - patch redis.StrictRedis -> fakeRedis.StrictRedis](https://github.com/hyunjun/practice/blob/master/python/test-unittest/test/common/src/test_common.py#L75)
  * [mockredis](https://github.com/locationlabs/mockredis) 뭘 잘못 입력했는지 잘 안됨
  * troubleshooting [`hset`이 <json string value>에 대해 동작하지 않음](https://gist.github.com/hyunjun/4ab30f4ebd401bcb0e60aabbab0b97bc#file-troubleshooting-md)
* [redis-hashring - A Python library that implements a consistent hash ring for building distributed apps](https://github.com/closeio/redis-hashring)
* [Tornado-Redis - Asynchronous Redis client that works within Tornado IO loop](https://github.com/leporo/tornado-redis)

# PubSub
* [Redis Tutorial for Beginners 11 - Redis Publish Subscribe](https://www.youtube.com/watch?v=33N1mgiRYK0)
* [RedisConf17 - How Roblox Keeps Millions of Users up to Date with Redis Pub/Sub - Peter Philips](https://www.youtube.com/watch?v=nXTxXSWBayg)
  * [RedisConf17 - Roblox - How Roblox Keeps Millions of Users Up to Date with Redis Pub/Sub](https://www.slideshare.net/RedisLabs/redisconf17-roblox-how-roblox-keeps-millions-of-users-up-to-date-with-redis-pubsub)
* [Advanced Redis: Subscribe Script to Pub/Sub Channel](https://matt.sh/advanced-redis-pubsub-scripts)

## PubSub Python
* **[Redis Pubsub and Message Queueing](https://stackoverflow.com/questions/27745842/redis-pubsub-and-message-queueing)**
* [Is non-blocking Redis pubsub possible?](https://stackoverflow.com/questions/7871526/is-non-blocking-redis-pubsub-possible)
* [Non-Blocking PubSub in Python using Redis](https://ravi.pckl.me/short/non-blocking-pubsub-in-python-and-redis/)
* [CREATE A SIMPLE CHAT ROOM WITH REDIS PUBSUB](http://programeveryday.com/post/create-a-simple-chat-room-with-redis-pubsub/)
* [github.com/r4vi/redis-pubsub](https://github.com/r4vi/redis-pubsub)
  * [Non blocking Redis PubSub in Python](https://www.youtube.com/watch?v=CG4ieKmnyWY)
* [basic redis python pubsub](http://chasemp.github.io/2013/03/26/basic-redis-python-pubsub/)
* [Python & Redis PUB/SUB](https://medium.com/@johngrant/python-redis-pub-sub-6e26b483b3f7)
* [A short script exploring Redis pubsub functions in Python](https://gist.github.com/jobliz/2596594)
* [LINE LIVE 채팅 기능의 기반이 되는 아키텍처](https://engineering.linecorp.com/ko/blog/detail/85)

# Queue
* [Benchmarking Message Queue Latency](https://bravenewgeek.com/benchmarking-message-queue-latency/)
* [Building a Message Queue Using Redis in Go](http://big-elephants.com/2013-09/building-a-message-queue-using-redis-in-go/)
* jedis
  * [Queuing tasks with Redis](https://blog.rapid7.com/2016/05/04/queuing-tasks-with-redis/)
  * [Spring-data-redis 에서 Jedis로 TLS를 쓰면서 인증서 체크는 Disable 하는 방법](https://charsyam.wordpress.com/2019/09/06/입개발-sprint-data-redis-에서-jedis로-tls를-쓰면서-인증서-체크는-disable-하/)
* Lettuce [Jedis 보다 Lettuce 를 쓰자](https://jojoldu.tistory.com/418)

## Queue Library
* [EasyRedisMQ - A Simple .Net Message Queue that Uses Redis for the back end](https://github.com/jkruer01/EasyRedisMQ)
* [Resque (pronounced like "rescue") - a Redis-backed library for creating background jobs, placing those jobs on multiple queues, and processing them later](https://github.com/resque/resque)
* [RSMQ - REDIS SIMPLE MESSAGE QUEUE](http://smrchy.github.io/rsmq/)

## Queue Library Python
* [Flask asynchronous background tasks with Celery and Redis](http://allynh.com/blog/flask-asynchronous-background-tasks-with-celery-and-redis/)
* [Simple Python Queue with Redis](http://peter-hoffmann.com/2012/python-simple-queue-redis-queue.html)
* [Basic Message Queue with Redis](http://flask.pocoo.org/snippets/73/)
* [kubernetes.io/docs/tasks/job/fine-parallel-processing-work-queue/rediswq.py](https://kubernetes.io/docs/tasks/job/fine-parallel-processing-work-queue/rediswq.py)
* [Task queues](https://www.fullstackpython.com/task-queues.html)
* [HotQueue - a Python library that allows you to use Redis as a message queue within your Python programs](https://github.com/richardhenry/hotqueue)
* [Pyres - a Resque clone](https://github.com/binarydud/pyres)
* [RESTMQ - Redis based message queue](https://github.com/gleicon/restmq)
* [RQ (Redis Queue) - a simple Python library for queueing jobs and processing them in the background with workers](http://python-rq.org/)
  * [github.com/rq](https://github.com/rq)
  * [Redis rq를 이용한 간단한 비동기 작업 큐](http://mcchae.egloos.com/11261352)
  * [Flask by Example – Implementing a Redis Task Queue](https://realpython.com/flask-by-example-implementing-a-redis-task-queue/)
  * [Walkthrough: Deploying a Flask app with Redis Queue (RQ) Workers and Dashboard using Kubernetes](http://tiao.io/posts/walkthrough-deploying-a-flask-app-with-redis-queue-rq-workers-and-dashboard-using-kubernetes/)
  * [Simple Job Queues with django_rq](https://www.imagescape.com/blog/2013/06/13/simple-job-queues-django_rq/)

# Streams
* [Introduction to Redis Streams](https://redis.io/topics/streams-intro)
* [Kafka & Redis Streams](https://hackernoon.com/introduction-to-redis-streams-133f1c375cd3)
* [Streams: a new general purpose data structure in Redis](http://antirez.com/news/114)
* [Redis Streams and the Unified Log](https://brandur.org/redis-streams)
* [The Design of Redis StreamsSalvatore Sanfilippo, Creator of Redis](https://www.youtube.com/watch?v=Ty1rQuRJijk)
