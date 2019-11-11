# M103 - Basic Cluster Administration

A MongoDB sharded cluster consists of the following components:

shard: Each shard contains a subset of the sharded data. As of MongoDB 3.6, shards must be deployed as a replica set.
mongos: The mongos acts as a query router, providing an interface between client applications and the sharded cluster.
config servers: Config servers store metadata and configuration settings for the cluster. As of MongoDB 3.4, config servers must be deployed as a replica set (CSRS).
