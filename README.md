# zabbix-java-gateway

This is a forked docker container for zabbix-java-gateway.

The instructions for configuring and running the container can be found in the original version: https://hub.docker.com/r/zabbix/zabbix-java-gateway/.

This fork contains only alpine version and adds the following fixes to the original version:

* https://support.zabbix.com/browse/ZBXNEXT-4558 - ability to monitor string values of custom JMX mbeans
