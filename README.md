# MiniDockerServer
A mini multi-container scalable home media server...
## Table of Contents
- [MiniDockerServer](#minidockerserver)
  - [Table of Contents](#table-of-contents)
  - [Structure](#structure)

## Structure
 - Portainer Container Manager
 - NginX Webserver/Balancer
   - LAMP Stack
     - PHP
     - Apache
     - MySQL
   - Node.js Cluster [3000]
   - MiniDLNA
   - Sonarr & Radarr
     - Transmission
     - SABnzbd+
   - YoutubeDL Server
   - Alpine Linux VM
     - Java Ripper
     - FTP AutoUpload
   - Wordpress?
