# Dockerwatch
Central repo for Dockerwatch which consists of 3 services:
- [Dockerwatch-web](https://github.com/shanel262/dockerwatch-web)
- [Dockerwatch-stats](https://github.com/shanel262/dockerwatch-stats)
- [Dockerwatch-influx](https://github.com/shanel262/dockerwatch-influx)

# What is Dockerwatch?
Dockerwatch is a Node.js application to monitor Docker containers and present the statistics, such as CPU and memory usage, to users, using a library called D3 that will visually display the data using graphs and charts. 

# Usage
Each of the Dockerwatch services README files contain instructions for installing and running them. 

To set up the Dockerwatch system you must firstly:
1. Set up MongoDB and InfluxDB (InfluxDB must have a database called 'dockerwatch' unless the services are configured with a different name)
2. Follow the instructions of each of the services

# Automated deployment
I have created an [Ansible playbook](https://github.com/shanel262/AnsibleFYP) for my Cloud Infrastructure module that automatically deploys the entire system using a single command.
