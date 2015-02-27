## OpsCenter Docker Image
This image contains OpsCenter 5.1.0 and is based on phusion/baseimage:0.9.13.
  
Run this using:

```
docker pull abh1nav/opscenter:latest
docker run -d --name opscenter abh1nav/opscenter:latest
```

You may also want to expose OpsCenter service ports:
```
docker run -d --name opscenter -p 8888:8888 -p 61620:61620 abh1nav/opscenter:latest
```

See https://github.com/abh1nav/cassandra for instructions on how to get a complete cluster running with OpsCenter in one line.
