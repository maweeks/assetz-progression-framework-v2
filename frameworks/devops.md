---
path: '/frameworks/devOps'
title: '♾️ DevOps Framework'
sidebarTitle: '♾️ DevOps'
sidebarGroup: 'Frameworks'
yaml: true
levels: 4
homepage: true
topics:
  - name: 'aws'
    title: '☁️ AWS'
    content:
      - level: 1
        criteria:
          - 'Aware of the purpose of each of our AWS services'
      - level: 2
        criteria:
          - 'Can explain what each of the AWS services that we use does and understands how we have them configured'
          - 'Makes minor modifications to AWS services'
          - 'Assists more experienced engineers on the design and implementation of larger infrastructure changes'
      - level: 3
        criteria:
          - 'Understands the AWS services to a deeper level including ones that we do not use'
          - 'Explains all aspects of our use of the AWS platform to new engineers'
      - level: 4
        criteria:
          - 'Serves as a technical authority on usage of a / multiple AWS services'
  - name: 'continuousIntegration'
    title: '♻️ Continuous Integration'
    content:
      - level: 1
        criteria:
          - 'Learns to create and configure simple CI/CD jobs in TeamCity, following guidance and training materials'
          - 'Fixes simple issues with TeamCity builds'
      - level: 2
        criteria:
          - 'Creates and configures simple jobs in TeamCity following accepted best practices'
          - 'Understands and can explain the TeamCity pipeline for each of our products'
      - level: 3
        criteria:
          - 'Identifies and fixes performance issues with TeamCity builds and AWS services'
          - 'Explains all aspects of our CI/CD implementation to new engineers'
      - level: 4
        criteria:
          - 'Serves as a technical authority on TeamCity usage'
          - 'Implements performance improvements that impact multiple services'
          - 'Uncovers and fixes tricky issues that have previously evaded detection'
  - name: 'networksAndSecurity'
    title: '🛠️ Networks & Security'
    content:
      - level: 1
        criteria:
          - 'Learns simple network security concepts'
        exampleCriteria:
          - criteria: 'Understands network infrastructure elements and how they connect together'
            examples:
              - 'DMZ'
              - 'DNS'
              - 'Firewalls'
              - 'Load balancers'
              - 'Proxy servers'
              - 'Routers and switches'
              - 'Storage'
      - level: 2
        criteria:
          - 'Applies network security knowledge to Assetz infrastructure with the help of others to make improvements'
      - level: 3
        criteria:
          - 'Identifies and fixes security vulnerabilities'
          - 'Proactively considers security implications of their work'
          - 'Applies network security knowledge to ensure Assetz infrastructure and services stay secure'
      - level: 4
        criteria:
          - 'Looks beyond the immediate security concerns and owns our future infrastructure roadmap'
          - 'Follows industry best practices to help ensure Assetz infrastructure is kept up to date with industry advancements and changing technologies where appropriate'
          - 'Promotes architectural thinking and good engineering practices at scale'
  - name: 'monitoring'
    title: '📊 Monitoring'
    content:
      - level: 1
        criteria:
          - 'Creates and updates graphs in Grafana when the data is already accessible by Grafana when guided on what to show'
      - level: 2
        criteria:
          - 'Adds and updates alerts in Grafana'
      - level: 3
        criteria:
          - 'Adds new tables and views as sources for new graphs in Grafana'
      - level: 4
        criteria:
          - 'Leads or contributes significantly to what and how services are monitored and alerted'
  - name: 'assetz'
    title: '🏢 @Assetz'
    content:
      - level: 1
        criteria:
          - 'Understands the purpose of each of our environments (dev, staging, mirror, prod) and can explain how changes get promoted between them'
      - level: 2
        criteria:
          - 'Understands the Assetz network infrastructure setup'
      - level: 3
        criteria:
          - 'Champions some technologies/components, and produces technical documentation to facilitate the learning of colleagues'
          - 'Understands the Assetz network infrastructure setup in detail and can explain it to others'
      - level: 4
        criteria:
          - 'Creates major contributions to our documentation, and creates documents that provide guidelines and best practices to other engineers'
          - 'Identifies and explores opportunities for service and business improvement'
  - name: 'docker'
    title: '🐳 Docker'
    content:
      - level: 1
        criteria:
          - 'Understands the benefits of docker and learns the basic commands and workflow of general docker use'
      - level: 2
        criteria:
          - 'Strong docker knowledge and understands how Assetz uses docker'
      - level: 3
        exampleCriteria:
          - criteria: 'Helps to maintain any docker images that Assetz uses'
            examples:
              - 'Bump node version'
              - 'Manage package versions'
              - 'Manage ECS contents and maintain container lists'
      - level: 4
        criteria:
          - 'Suggests and implements improvements to the way that docker is used and is a point of knowledge for other engineers regarding docker'
  - name: 'expertise'
    title: '🛠️ Expertise'
    content:
      - level: 3
        criteria:
          - 'Follows appropriate dev-ops best practices'
          - 'Identifies obvious deficiencies in the processes and supports activities to improve them'
          - 'Debugs complex issues at speed'
          - 'Implements solutions that are maintainable and scale reliably without intervention'
      - level: 4
        criteria:
          - 'Implements solutions that serve as definitive examples for new engineers'
          - 'Contributes to external technologies or libraries that we depend on'
          - 'Facilitates technical decision making in complex and ambiguous situations'
---

Become a master of the automated build, test, release, deployment and monitoring process of all of our products and services. ♾️

### Technologies

- AWS (services listed below)
- Docker
- Grafana
- Influx
- TeamCity

#### AWS Services we use

| Service                           | Description                                                                                                                                                                                                                                                                                                                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CloudWatch                        | AWS CloudWatch is a monitoring and observability service that provides you with data and actionable insights to monitor your applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health.                                                                                                                         |
| EC2 (Elastic Compute Cloud)       | AWS EC2 is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers.                                                                                                                                                                                                                             |
| ECS (Elastic Container Service)   | AWS ECS is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS.                                                                                                                                                                                                    |
| ElastiCache                       | AWS ElastiCache offers fully managed Redis and Memcached. Seamlessly deploy, run, and scale popular open source compatible in-memory data stores.                                                                                                                                                                                                                                           |
| Fargate                           | AWS Fargate is a compute engine for Amazon ECS that allows you to run containers without having to manage servers or clusters. With AWS Fargate, you no longer have to provision, configure, and scale clusters of virtual machines to run containers.                                                                                                                                      |
| RDS (Relational Database Service) | AWS RDS makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.                                                                                                                         |
| S3 (Simple Storage Service)       | AWS S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. |
| VPC (Virtual Private Cloud)       | AWS VPC lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.                                        |
| WAF (Web Application Firewall)    | AWS WAF helps protect your web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources. AWS WAF gives you control over which traffic to allow or block to your web applications by defining customizable web security rules.                                                                                  |
