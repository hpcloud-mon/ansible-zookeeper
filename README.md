#Zookeeper
Installs [zookeeper](http://zookeeper.apache.org/)

##Requirements
- zookeeper_hosts - comma separated list of host:port pairs, defaults to 'ansible_fqdn:2181' for a single node

##Optional
- zookeeper_id - Id to be used if one can't or shouldn't be derived from zookeeper_hosts. This will happen if zookeeper_hosts doesn't contain the fqdn but an alias

##License
Apache

##Author Information
Tim Kuhlman
Monasca Team email monasca@lists.launchpad.net
