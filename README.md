# packer-example

Packer Template that builds docker image with tomcat

## Getting Started
This little guide will run you through usage process

### Prerequisites

You need docker installed in your system

### Running

```
docker build template.json
docker run -d -p 8080:8080 --name tomcat tomcat:0.1
```