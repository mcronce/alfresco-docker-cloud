# Alfresco Docker Cloud

The goal of this project is to provide a production-ready Alfresco system running in Docker.

This project includes 4 subprojects, one for each needed docker images to run Alfresco.

- <https://github.com/jeci-sarl/docker-alfresco-platform/>
- <https://github.com/jeci-sarl/docker-alfresco-share/>
- <https://github.com/jeci-sarl/docker-alfresco-solr/>
- <https://github.com/jeci-sarl/docker-alfresco-libreoffice/>

The corresponding docker images are automatically created by Docker Cloud :

- [jeci/alfresco-platform](https://hub.docker.com/r/jeci/alfresco-platform/)
- [jeci/alfresco-share](https://hub.docker.com/r/jeci/alfresco-share/)
- [jeci/alfresco-solr](https://hub.docker.com/r/jeci/alfresco-solr/)
- [jeci/alfresco-libreoffice](https://hub.docker.com/r/jeci/alfresco-libreoffice/)

## Quick Start (Ubuntu)

*1. Install Docker and Docker-Compose*

 -  <https://docs.docker.com/engine/installation/>
 -  <https://docs.docker.com/compose/install/>


*2. Running Alfresco*

```
wget https://raw.githubusercontent.com/jeci-sarl/alfresco-docker-cloud/master/docker-compose.yml

docker-compose up -d
```

*3. Play*

Your server is now available : http://localhost:8080/share/ with login `admin` / `admin`

When you have finished, stop all with `docker-compose down` command.


## Documentation

* Partial documentation is currently available on my own website : http://jeci.fr/projets/alfresco-docker-cloud.html


* Report issues in [github project](https://github.com/jeci-sarl/alfresco-docker-cloud/issues)


## Requirements

With default configuration you need at least 2GB of RAM and 2 CPU.
