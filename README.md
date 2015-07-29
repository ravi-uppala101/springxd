I am planning for an experiment with springxd and mongodb / hdfs as databases. This will be multi-phase approach.

Phase 1: 

1.	Stream data using spring xd into mongodb
2.	Input source can be any log files or twitter event streaming ..we can try
3.	Output sink we can start with mongodb. 

Phase 2

1.	Adding more sink options like HDFS or Redis.
2.	Run some analytical programs on the data using mapreduce if it is hdfs.
3.	Run some programs by creating a framework fetching data from redis.

Today is starting day for this project.

1.	I would like to make this environment as portable. So today I will setup the environment using vagrant.
High level I am thinking following will be used to create environment.
1.	centos virtual box.
2.	Java8
3.	Maven 3.
4.	Mongo db
5.	Eclipse latest version.
