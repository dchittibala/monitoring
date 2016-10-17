
# Setting up Docker on Openstack

* Create 3 Instances to containerize elasticsearch, influxdb, Grafana.

* Using image name "docker", boot an instance. This has docker already setup. If image "Docker" is not present boot an instance with image ubuntu 14.04 and install docker, docker-compose and git on the machine and attach volume to it.

* ssh into the machine and `git clone git@git.target.com:EDABI-Core/Monitoring.git`

* To run a Monitoring (ElasticSearch/Grafana/Influxdb) container/s, Please look at Readme at each directory and start each container using the Readme
