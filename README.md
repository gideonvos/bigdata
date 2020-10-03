# Big Data

Docker file for running Hadoop, Spark, Jupyterlab and Hue all on a small local cluster.

Docker setup:

This was tested on Ubuntu Linux 20.04 with Intel i9 and a lot of RAM. Edit the docker-compose.yml to reduce worker ram and cores to fit your needs.

Download docker-compose.yml and hadoop.env into a new folder.


Run "docker-compose up" to start the services. First time about 10GB of docker images will be downloaded.

Once started the console will keep dumping status messages. Services should be up in a minute or so.

A new "data" sub-directory will be created to contain and manage HDFS.

Press CTRL-C when you want to shut it all down.


Jupyterlab: http://localhost:8888/lab?

Hue: http://localhost:8088/

Hadoop Namenode: http://localhost:9870/

