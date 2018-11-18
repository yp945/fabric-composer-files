#How to Start Docker
run 

```shell
docker-compose -f kafka.yaml -f peer.yaml up 
```

#How to Check kafka status
default the composer started a kafka-manager.
[http://localhost:9000](http://localhost:9000 "Title")


#How to stop Docker
run

```
docker-compose -f kafka.yaml -f peer.yaml down
```

#Data Storage
By default all the data has saved to host machine
if you wang a refresh start, run 

```
docker-compose -f kafka.yaml -f peer.yaml down
```

then delete all the files in folder data