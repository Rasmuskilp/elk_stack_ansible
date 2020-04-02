# This project creates a fully functional ELK stack for monitoring.
## It is done using ansible
### The project consists of the main.yml file which instructs which folders/ELK stack properties to use.
### To ensure that the code is built using the smallest functional segments, the stack was separated.
### THere is the main elasticsearch, then filebeat and logzio, java, kibana and finally metricbeat.
#Brief overview of the ELK stack and its use
## The ELK stack consists of three software products: E for elasticsearch, L for logstash and K for kibana
### elasticsearch is used to store logs
### Logstash is used to both ship, process and store logs
### Kibana is a visualisation tool
## ELK Stack is designed to allow users to take to data from any source, in any format, and to search, analyze, and visualize that data in real time.
## The ELK stack is used to take data, from whatever source and format, and be able to search, analyse and visualise it in real time.
## ELK stack is beneficial as it allows for a centralized system which can be used to identify issues within the network. It streamlines the error logging by having it in a single place as well as it enables to have oversight over multiple serves.
### ELK provides centralized logging that be useful when attempting to identify problems with servers or applications. It allows you to search all your logs in a single place. It also helps to find issues that occur in multiple servers by connecting their logs during a specific time frame.
