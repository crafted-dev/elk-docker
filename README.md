# Elasticsearch, Logstash, Kibana (ELK) Docker image for Synology

[![](https://images.microbadger.com/badges/image/sebp/elk.svg)](https://microbadger.com/images/sebp/elk "Get your own image badge on microbadger.com") [![Documentation Status](https://readthedocs.org/projects/elk-docker/badge/?version=latest)](http://elk-docker.readthedocs.io/?badge=latest)

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

### Pre-installation 

Log into your DSM by ssh and increase the maximum virtual memory areas.
    sudo sysctl -w vm.max_map_count=262144 

Also the following to /etc.default/sysctl.conf to make the change persistent over reboots
    vm.max_map_count = 262144


### Further Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.


### About

Written by [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).
