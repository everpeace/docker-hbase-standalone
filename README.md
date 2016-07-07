## Docker HBase Standalone Dockerfile

This repository contains **Dockerfile** for [Docker's](https://www.docker.com/) [build](https://registry.hub.docker.com/u/everpeace/hbase-standalone/)

### Installation

1. Install [Docker](https://www.docker.com/)

2. Download [build](https://registry.hub.docker.com/u/everpeace/hbase-standalone/): `docker pull everpeace/hbase-standalone`


### Usage

    docker run -d -p 2181:2181 -p 60000:60000 -p 60010:60010 -p 60020:60020 -p 60030:60030 everpeace/hbase-standalone

Open http://docker.ip.add.ress:60010 in a browser

### Notes

This runs a patched version of HBase built from [this](http://github.com/zcox/hbase) fork of [HBase](http://github.com/cloudera/hbase)
