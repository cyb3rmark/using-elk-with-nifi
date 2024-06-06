# Project: Use ElasticSearch/Kibana Together with Apache NiFi
This project will demonstrate the use of using part of the Elastic Stack, notably ElasticSearch and Kibana, together with Apache NiFi. This allows the use of NiFi pipelines to send data to ElasticSearch. This can be useful when receving data from multiple sources or when wanting to take data from one source and push it to multiple destinations. 

The project uses Apache NiFi version 2.0.0-M3 set up to use https from a remote browser. This version now defaults to https instead of http, however the config needed to be modified in order to work from other non-loopback interfaces (outside of localhost). All of the software used here is installed on an Ubuntu 24.04 LTS Server VM on a local Linux machine. Demonstrated is the use of local firewall, understanding the new default security configs of some of these applications as previously mentioned as well as proper service set-up for third party applications on Linux such as Apache NiFi.

Everything in this project is documented and detailed so it can be reproduced easily and proven to work for authenticity sake.

The entire project documentation (Google Doc) can be found here: [Project: Use ElasticSearch/Kibana Together with Apache NiFi](https://docs.google.com/document/d/1wIflGj09Ef6OfeR9yaob59MvyDjKuozpc3zQyEFkRN0/edit?usp=sharing) 
