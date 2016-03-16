:tocdepth: 1

This documents discusses the roadmap and architecture for SQuaRE's logging, monitoring and metrics system.

Motivation
==========

Advantages
==========

There are specific advantages to using a service.

Correlation and aggregation of events across multiple system layers.

Unified, consistent service to search for and analyze systems.

Better aggregation. More meaningful (control over field names and formats across system layers), while storing less data per event.

Filtering using broader criteria.

Architecture
============

The architecture should be highly available and reliable.

Roadmap
=======

ELK

Automated deploy using ansible and siim

ELK++

Discussion for why


Repositories
============

Panopticon ?

Packer repo

Ansible Deploy repo


Resources
=========

Logging as a service/system

ES docs

L, Beat, Reimann docs

Kibana docs

kafka

cassandra

