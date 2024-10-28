# Geoserver Cluster

Howto
- https://docs.geoserver.org/maintain/en/user/community/jms-cluster/index.html

actimemq
- mount rootless container, based on tomcat
- download URL: https://activemq.apache.org/components/classic/download/
- add postgresql jdbc driver on ActiveMQ: 
    - https://docs.geoserver.org/latest/en/user/community/jms-cluster/activemq/activemqBroker.html#postgres-datasource
    - https://activemq.apache.org/components/classic/documentation/jdbc-support

Example:
- https://github.com/geobeyond/geoserver-clustering-playground

Enhancements
- WARN: Changes on "Users, groups, roles" menu does not propagate into JMS cluster
- 