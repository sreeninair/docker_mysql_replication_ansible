# docker-mysql-replica

This is an ansible project to create a replica of mysql(5.7) master(centos) in a ubuntu base docker instance. The setup automatically setup a docker environment, create a custom container in docker instance with mysql 5.7 base, copy mysqldump from master and restore it. Finally configure replication. I am working on fully automated ssl replication slave setup.
