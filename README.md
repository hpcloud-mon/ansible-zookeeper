#Zookeeper
Installs [zookeeper](http://zookeeper.apache.org/)

##Requirements
- zookeeper_hosts - comma separated list of host:port pairs, defaults to 'ansible_fqdn:2181' for a single node

For a cluster each node must have an id. This can be specified by setting zookeeper_id for each node, alternatively it is pulled from the order
of the zookeeper_hosts.

##License
Apache

##Author Information
Tim Kuhlman
Monasca Team email monasca@lists.launchpad.net
