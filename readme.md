# TASK: A2 architecture 
## 1) Read the systems design primer thoroughly! 
You find it here: https://github.com/donnemartin/system-design-primer

Most questions can be answered by searching for the keyword in the system design primer, then copy & paste or put it in your own words.

The general idea is: Learn stuff about distributed systems. And how to scale them. How to design as distributed system, that can become a popular distributed system and will not collapse when the number of people using it increases and becomes BIG.

Why do we learn this? The system design primer has a paragraph on the system design interview. But going to youtube and looking at the viedeos for this keyword is even more interesting. You might start with this one:
https://www.youtube.com/watch?v=umWABit-wbk&t=1009s (Uber system design explained)
https://www.youtube.com/watch?v=UzLMhqg3_Wc (Interview prep with all the keywords from this task. maybe a bit dry.)

In distributed systems you have a distributed system / computers connected  via some kind of network, like the internet (yeah!). And they need to communicate: This is done through sharing (one or multiple) database(s) (old) or messaging / streaming (new!). The system design primer is focused on the "traditional" approach using databases and is not so much about messaging / streaming (which will be at the center of the kafka task).

Thinking about Consistency, Availability and Partition tolerance when describing or designing a distributed system is key! The CAP model is about these three things - it's key for the homework!

For each question a few sentences are required... only a few sentences :-) since the whole thing only should have 2 pages.

### a) What is the difference between latency and throughput?

### b) What would you design a AP or a CP System?
Yes, you need to know the CAP-model!

### c) What is replication, failover and how does Redis replication work?
* The paragraph on "availability pattern" in the system design primer has the info on replication and failover. Availability refers to the A in the CAP model :-)
* for redis-replication: rtfm https://redis.io/topics/replication and wrap your head around that.

### d) What would be the perfect database / database model for your SWT PET project if you would have to scale large and having some 10.000 clients?

### e) What are the advantages and disadvanteges of (web) caching?

### f) What is the difference between RPC and Rest?
RPC started last century, REST / REST APIs are more recent. But actually, hip companies move away from REST API and 
use other technology. GraphQL made by facebook is a keyword here, and monday.com explains why: https://support.monday.com/hc/en-us/articles/360005144659-Does-monday-com-have-an-API-
(This should not be required to get the homework done ...)

### g) How many cores does the Stackoverflow Servers have, with what chip Hz and how many MB L2 cache?
* use the link in the system design primer, it is from 2009 :-)
http://highscalability.com/blog/2009/8/5/stack-overflow-architecture.html
* but there is newer info out there. I found something from 2016:
https://nickcraver.com/blog/2016/02/17/stack-overflow-the-architecture-2016-edition/

## 2) GPU (1 page): Do a little research on GPU &TPU.
This is not in the system design primer :)

### How would you get a simple GPU "Hello World" Example run on Google or AWS? (theoretically. Not practically!)
Check out https://colab.research.google.com (Big thank you to Roman!)
