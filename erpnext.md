### ERPNext Minimum Specification to start server
1. OS: Ubuntu 22.04
2. CPU: 2 Core
3. RAM: 4 GB
4. HD: 50 GB


### ERPNext Specification Recommendation to support 1000 - 2000 Users simultaneously
1. OS: Ubuntu 22.04
2. CPU: 16 Core
3. RAM: 32 GB
4. HD: 500 GB 

### For Users from 2000 up we have to split server
All these server will be managed in Kubernets

1. The Python Server ( Front End & Workers ) ( Auto Scale )
2. The MariaDB Database Server ( Auto Scale )
3. The Redis Server ( Caching and Message Broker ) ( Auto Scale )
4. The Nginx Server ( For Real-Time Communication ) ( Auto Scale )
