describe-lang
=============

The Describe programming language is a DSL, or Domain Specific Language, targeted at system engineer, system administrators,etc.
The goal is to provide a higher level language where the intended audience can express their ideas in natural language.

The goal is to describe an environment or its components and possible turn that description into actions or documentation

For example, Describe aims to make any of the following statements , valid and potentially actionable:

web servers should have apache installed.
machine x is a web server
on cluster 1 run uptime using mcollective and log its stdout to uptime.log
add node A to load balancer pool x
Dallas data center load balancer ip is a.b.c.d
frontends depends on memcached 


Sounds like a pipe dream, right ? :)



The language will be implemented using ruby . Descriptions will be written using your favorite editor and saved as text files

