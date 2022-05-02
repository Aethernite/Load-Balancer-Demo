
# Load Balancer Demo

Demo using nginx as a reverse proxy load balancing accross 2 web services.
Each of the services, and nginx itself, run inside docker containers, and 
are controlled using docker-compose. 

This repository was used for demonstration purposes during my bachelor's degree 
in Technical University of Sofia.

To start:

```
sudo docker-compose up -d
```

To stop:

```
sudo docker-compose stop
```

To remove:

```
sudo docker-compose rm 
```

By accessing localhost:8000 in a browser, and hitting refresh a few times,
you'll see the load balancer switching between server1 and server2. 
