# cassandra-cluster

**connect cassandra cluster**     
```
$ docker run -it --rm bitnami/cassandra:latest cqlsh --username <user> --password <passwd> <host-ip> <port>

$ docker exec -it kong-api-appgw-cluster_cassandra-node2_1_ed12ea994e09 nodetool status
Datacenter: datacenter1
=======================
Status=Up/Down
|/ State=Normal/Leaving/Joining/Moving
--  Address     Load       Tokens       Owns (effective)  Host ID                               Rack
DN  172.18.0.2  100.65 KiB  256          64.0%             486748fd-cd06-4b7e-931e-a7508ee08bf8  rack1
UN  172.18.0.3  69.93 KiB  256          70.1%             b99bbf70-41fd-497c-b34e-3ffc928899da  rack1
UN  172.18.0.4  111.43 KiB  256          65.8%             4659cfeb-b65b-4f5d-9a0b-a8b9dee76f4b  rack1
```
**output**    
```
Welcome to the Bitnami cassandra container
Subscribe to project updates by watching https://github.com/bitnami/bitnami-docker-cassandra
Submit issues and feature requests at https://github.com/bitnami/bitnami-docker-cassandra/issues


Warning: Cannot create directory at `/.cassandra`. Command history will not be saved.

Connected to cassandra-cluster at <host>:<port>.
[cqlsh 5.0.1 | Cassandra 3.11.3 | CQL spec 3.4.4 | Native protocol v4]
Use HELP for help.
<login-user>@cqlsh>
```
