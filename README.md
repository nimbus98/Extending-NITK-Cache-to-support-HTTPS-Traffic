# Extending NITK Cache to support HTTPS Traffic

​Extending the Generic Cache developed at NITK to support caching of HTTPS traffic

## Course Code: CS300
## Assignment: # 29

### Overview

Typically within a University,some requests are similar,e.g. OS updates, Linux package installs, Python pip packages and others.These are huge data transfer requests ranging from MBs to GBs, and consume a large amount of bandwidth on external access links to the Internet. Redundant requests of this nature from a large user base lead to enormous wastage of bandwidth. A forward proxy with a generic cache has been setup at NITK Surathkal to address this concern. However, caching HTTPS traffic (e.g.,Python pip packages) is not trivial because of it send-to-end encryption semantics. The main aim of this project is to develop a strategy to cache HTTPS traffic.

### Team:
* Akash Nair - 171CO107
* Kevin George Joe - 171CO220
* Moaz Alam - 171CO223
