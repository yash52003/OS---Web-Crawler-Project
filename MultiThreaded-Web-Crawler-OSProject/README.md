# Web_Crawler_OS_Project
THEORY:
A multi-threaded web crawler involves several operating system concepts. Here are 
some of them:

Process and threads: The web crawler may run as a process with several threads 
running simultaneously to fetch and process web pages. The operating system 
provides the necessary support to create and manage these threads.

Synchronization: The threads running in the web crawler may need to synchronize 
their access to shared resources such as the queue of URLs to crawl or the data 
structure used to store the crawled data. The operating system provides 
synchronization primitives such as mutexes, semaphores, and condition variables to 
enable this.

Memory management: The web crawler may need to allocate and deallocate 
memory dynamically as it crawls more pages and accumulates more data. The 
operating system provides memory management services such as virtual memory, 
memory mapping, and garbage collection to manage the crawler's memory usage.

I/O operations: The web crawler performs I/O operations such as reading data from 
the network and writing data to disk. The operating system provides APIs for these 
operations and may also use techniques such as buffering and caching to improve 
performance.

Network stack: The web crawler relies on the operating system's network stack to 
communicate with web servers and retrieve web pages. The network stack provides 
services such as TCP/IP, DNS resolution, and socket management.
Process scheduling: The operating system schedules the threads of the web 
crawler to run on the available CPUs. The scheduler may use techniques such as 
pre-emption, time slicing, and priority-based scheduling to allocate CPU time fairly 
among the threads.

Error handling: The web crawler may encounter errors such as network timeouts, 
server errors, or malformed web pages. The operating system provides mechanisms 
for error handling and recovery, such as signal handling and exception handling.
