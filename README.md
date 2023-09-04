
# Kubernetes Infrastructure for Service Clustering

This project aims to implement an infrastructure using Kubernetes for clustering various services. Each service will run in a dedicated container based on Alpine Linux for optimized performance.

## Components

The following components are required for this project:

1. **MetalLB**
   - Description: A Load Balancer to manage external access to the cluster's services, serving as the only entrance point to the cluster.

2. **Nginx**
   - Description: An HTTP and reverse proxy server, mail proxy server, and generic TCP/UDP proxy server.

3. **vsFTPd**
   - Description: A secure FTP server for Unix-like systems, including Linux.

4. **MariaDB**
   - Description: A database management system derived from MySQL, licensed under GPL.

5. **WordPress**
   - Description: A CMS (Content Management System) focused on creating web pages.

6. **phpMyAdmin**
   - Description: A free web-based tool to handle MySQL administration.

7. **InfluxDB**
   - Description: An open-source time series database developed by InfluxData.

8. **Telegraf**
   - Description: An open-source server agent for collecting metrics from stacks, sensors, and systems.

9. **Grafana**
   - Description: An open-source software for graphing and analyzing metrics from Time Series Database Storage (TSDB).

## Usage

To use this infrastructure, follow the instructions for deploying and configuring each component as per your requirements. Detailed setup instructions for each component can be found in their respective documentation.
