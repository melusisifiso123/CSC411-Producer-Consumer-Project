 CSC411 – Producer Consumer Mini Project
University of Eswatini – Department of Computer Science

This project is an implementation of the classic **Producer–Consumer Problem
using:
- Python multi-threading  
- Semaphores and synchronization  
- XML data serialization  
- Socket programming (TCP client/server)  
- GitHub version control  


Project Description

The producer generates **random ITStudent objects**, converts them into XML, saves them as files, and inserts a reference into a shared buffer.  
The consumer reads the buffer, parses XML files, reconstructs student information, computes the average mark, and determines PASS/FAIL.

A socket-based version is also implemented where:
- The server acts as the producer.
- The client acts as the consumer.

Technologies Used
- Python 3
- XML (ElementTree)
- Threading and Semaphores
- Socket Programming (TCP)
- Git and GitHub

How to Run
Producer–Consumer Version
```bash
python producer_consumer.py
