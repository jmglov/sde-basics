# Software Development Engineer Basics

I believe a successful software engineer typically has a [T-shaped skills profile](https://en.wikipedia.org/wiki/T-shaped_skills), meaning they have shallow but broad knowledge of most areas of software development, and deep knowledge of one or more. This document is my attempt to enumerate subjects that a developer should know at least a little about. My definition of "a little" is at least enough knowledge to recognise that a problem, situation, or design is related to a subject, and know what to search for to find out more. For example, recognising that a certain problem they're trying to solve is equivalent to the knapsack problem, and knowing where to find different solutions.

Inexperienced developers should focus on broadening their knowledge across the T, whilst deepening their knowledge of the subject(s) most applicable to their current project. More senior developers should devote time to deepening more areas of the T, corresponding to their interests. It's my opinion that you are best at what you're passionate about, so don't feel guilty about diving deep into a subject that has little to nothing to do with what you're currently working on.

Here's the list, in no particular order. I've added what I would consider the minimum knowledge of each subject.

* Mastery of at least one programming language, meaning once you have designed part of a system, you can translate your design into idiomatic code, choosing the appropriate constructs and leveraging the standard library of the language.
* Functional programming: map / reduce / filter; recursion
* Typed functional programming (e.g. the ML family: SML, O'Caml, Scala, Haskell, or F#, Erlang)
* Logic programming: Prolog, Kanren, etc.
* C: pointers, memory management (malloc / free), processes (fork / exec)
* Object oriented design
* [Networking](https://en.wikipedia.org/wiki/Internet_protocol_suite):
  * Layers: link, internet, transport, application
  * Common link layer protocols: MAC, ARP
  * Internet layer: IP, ICMP (used by ping and traceroute)
  * Transport layer: TCP, UDP
  * Application layer:
    * HTTP: most common methods (GET, POST, PUT), how headers work, classes of status codes, keepalive
    * DNS: root servers, zones, caching
    * FTP
    * Telnet
    * SSH
    * SMTP
  * Routing: BGP, OSPF, CIDR, [Dijkstra's algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
* Data structures: performance characteristics of arrays, vectors, linked lists, hash maps, sets, trees (especially red/black and other balanced trees)
* [Big O notation](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/): basic time complexity analysis of basic algorithms (quicksort, mergesort, bubble sort, etc.)
* Operating systems: basic parts of an OS, e.g. virtual filesystem, scheduling, protection, processes
* Linux / UNIX systems administration: partitioning, filesystems, users and groups, init scripts, shell scripting, process management
* AWS: common services (EC2, S3, SNS/SQS, DynamoDB, Route 53, Cloudwatch, Cloudfront, Lambda)
* Relational databases: SQL, common engines (MySQL, Postgres, Oracle, SQLite), schema design
* NoSQL databases: basic types (key-value store, document DB, graph DB)
