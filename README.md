# bWAPP-dockercompose
![](img/bwapp.jpg)
--- 

```bash

# start up the docker compose
docker compose up -d 

# then bWAPP should be running 
http://localhost/install.php

# stop the docker compose
docker compose down

# check container running
docker ps -a 

```

**The good of this**
- If you want to modify the code of bWAPP you can just modify the code in `app/`, refresh the page you should see the changes immediately 
- Why docker-compose for volume? I am using Mac the path of docker storeing volume is tricky but if you using Linux, then you can just build volume without docker compose.
