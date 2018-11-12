# cassandra-cluster

**connect cassandra cluster**     
```
docker run -it --rm bitnami/cassandra:latest cqlsh --username <user> --password <passwd> <host> <port>
```
**output**    
```
Welcome to the Bitnami cassandra container
Subscribe to project updates by watching https://github.com/bitnami/bitnami-docker-cassandra
Submit issues and feature requests at https://github.com/bitnami/bitnami-docker-cassandra/issues


Warning: Cannot create directory at `/.cassandra`. Command history will not be saved.

Connected to cassandra-cluster at 10.10.212.4:9042.
[cqlsh 5.0.1 | Cassandra 3.11.3 | CQL spec 3.4.4 | Native protocol v4]
Use HELP for help.
<login-user>@cqlsh>
```