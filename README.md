
# ThreadPooling Vs Multithreaded server

In this project we can know the performance differnce between Multithreaded  and ThreadPooling
 and how efficient are they.

 I have used Jmeter for the testing purpose and spawn about 600k threads in a minute .
 Below we can easliy see the deviation in the graph how there is less deviation in thread polling as comapred to Multithreaded.Beacuse of proper utilization of cpu in threadpooling ,it takes less time in completing the request 





## Screenshots


![Screenshot (19)](https://github.com/vrajtalati/MultiThreaded_Server/assets/77099540/6fc6ffc7-1e10-479d-9def-f11d05c8a712)
 Graph for Single threaded Server. We can see there are many request that failed and time goes as high as 300ms.





 
![Screenshot (21)](https://github.com/vrajtalati/MultiThreaded_Server/assets/77099540/f27f6203-afa7-4517-93df-d519883a4a4a)
Graph for Multithreded Server.It works way better than the single threaded Server .

![Screenshot (20)](https://github.com/vrajtalati/MultiThreaded_Server/assets/77099540/8f87d0bc-7726-44cc-902d-4895931602ba)
Graph for Thread pooling technique.We can see how it has less deviation compared to Multithreaded Server.This is when i used pool of 10 threads, it could be optimozed ahead.


## Key Learnings

- Mutlithreaded Server
- Thread Pooling
- TCP/HTTP
- Thread pool vs event loop
- Thread Block
- Context Switching

